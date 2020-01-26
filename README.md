# 2D-Binary-Index-Tree
This is a 2 Dimensional Binary Index Tree implemented in Python. We Can use this 2 Dimensional Binary Index Tree to find the sum between two different values in a 2 Dimensional Tree.

We first Create an object of the FenwickTree Class and give it it's size for both dimensions.
We use the Print function on the object which prints the values of the array and sends it to Construct to construct an Array to be used to work on. It is used as ObjectName.Print(Matrix)
The Construct function updates the data in the array. (The Print Function calls it itself)
Summation is called to update Queries to be used by giving values as Summation(x1,y1,x2,y2) to get the sum between the two locations.
LSB is the Least Significant Bit formula stored to be used.
