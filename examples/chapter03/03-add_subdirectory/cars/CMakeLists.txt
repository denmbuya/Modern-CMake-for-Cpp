add_library(cars OBJECT
    car.cpp
#   car_maintenance.cpp
)
target_include_directories(cars PUBLIC .)
set(val 25)
if(${val} LESS 1)
  message("The number is greater")
endif()

set(List1 A B)
foreach(Loopvar IN LISTS List1)
   message("The values are ${Loopvar}")   
endforeach()




