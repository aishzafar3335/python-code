# python-code

A left rotation operation on an array of size  shifts each of the array's elements  unit to the left. Given an integer, , rotate the array that many steps left and return the result.

def LeftRotation(d, arr):
  for i in range(d):
    a=arr.pop(0)
    arr.append(a)
  return arr





