###  FreeRTOS V8.2.3 for Arduino Samd21\Samd51 Boards  

####  This library will allow you to create FreeRtos Projects in the arduino IDE and run them on your Samd21 or Samd51 boards.  


***************************************************************************************************************
#### Tested Boards:  
 Sparkfun Samd21 Mini  
 Sparkfun Samd21 Dev  
 Adafruit Feather M0  
 Adafruit Itsy Bitsy M4
 Atmel Xplained Samd21 

 
***************************************************************************************************************

#### Optional Feature: Wrapped Memmory Functions. 

This linker setting change will allow all microcontroller malloc/free/realloc/calloc 
operations to be managed by FreeRtos. This could eliminate memory corruption issues on
c++ intensive projects, or projects that might be fragmenting the heap.

Implementation Guide can be found in: "wrapping memory functions\platform.local.txt"

 
 
