### Description
This example works but there is an issue with vtkImageAccumulate. 

It appears the maximum frequency of a histogram generated by 
vtkImageAccumulate, when that frequency corresponds to the value of 0,
cannot be disabled by setting ignore zero to true!  See lines
245 and 218 in vtkImageAccumulate.cxx