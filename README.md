# Error-Handler
This Class is contain all errors that may happen when you use the Package , It is a layer that contain all Errors handlers to any class in ChartsLab Package . let's go in details with this class .

## What is the Variables And The Numbers ??
This numbers is expresses the error and it's Description : 
let's talk about it in more **details** 
~~~~
VECTORS_NOT_CONFORM_M  = 100 ;
VECTORS_NOT_CONFORM_D = 101 ;
VECTORS_NOT_CONFORM_A = 102 ;
MATRIXS_NOT_CONFORM_M = 103 ;
MATRIXS_NOT_CONFORM_D = 104 ;
MATRIXS_NOT_CONFORM_A = 105 ;
~~~~
~~~~
VECTORS_NOT_CONFORM_M : 
This mean that the Vector1 Dosen't Conform with Vector2 in Function Multiply .
VECTORS_NOT_CONFORM_D : 
This mean that the Vector1 Dosen't Conform with Vector2 in Function Devation .
VECTORS_NOT_CONFORM_A : 
This mean that the Vector1 Dosen't Conform with Vector2 in Function Addation .
MATRIXS_NOT_CONFORM_M :
This mean that the Matrix1 Dosen't Conform with Matrix2 in Function Multiply .
MATRIXS_NOT_CONFORM_D :
This mean that the Matrix1 Dosen't Conform with Matrix2 in Function Devation .
MATRIXS_NOT_CONFORM_A :
This mean that the Matrix1 Dosen't Conform with Matrix2 in Function Addation .
~~~~

## How You Add New Exceptions :
Just add New Headr with new number and new Description in the Head Matrix and Description Matrix .
`Error.error(Error.Header)` : this will return `Error.Number , Error.Header , Error.Description`
![Alt](https://raw.githubusercontent.com/ChartsLab/Error-Handeler/master/Screenshot%20from%202017-03-23%2019-49-25.png)
