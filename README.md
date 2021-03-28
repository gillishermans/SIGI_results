# Shape Inference and Grammar Induction from Three-Dimensional Buildings: Examples and Results
Images of buildings examples and new generated buildings for SIGI https://github.com/gillishermans/SIGI.

We generated 5 unenclosed and enclosed buildings for each example with 20 and 50 production steps.
Results can differ a lot with different shape inference parameters. Here we chose quite straightforward parameters that lead to reasonable results for a lot of the examples. The manual effort of generating these examples was thus relatively low.

Notes: 
 - Slanted roofs (E3,5,9) and cylindrical shapes (E6) are especially problematic for SIGI.
 - Non-existant images occur for empty productions, such as buildings reduced to nothing by the enclosure constraint.
 - Some enclosed buildings contain buildings seperate from each other. These were connected by one or multiple uncenclosed shapes that were removed during enclosure.

## Results
For each example we show the example, an unenclosed buildings and an enclosed building (if available). 

### Example 1
With alpha = 1.0, rectangular shapes, merge operations, overlap allowed.
<p float="left">
  <img src="https://github.com/gillishermans/sigi_results/blob/main/examples/example1.png" height="200" />
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example1_results/Example1_20steps/2021-03-20_23.16.31.png" height="200" /> 
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example1_results/Example1_20steps_enclosed/2021-03-20_16.27.15.png" height="200" />
</p>


### Example 2
With alpha = 1.0, rectangular shapes, merge operations, overlap allowed.
Additional post split applied, that splits large shapes when cut in half by other shapes.

<p float="left">
  <img src="https://github.com/gillishermans/sigi_results/blob/main/examples/example2.png" height="200" />
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example2_results/Example2_50steps/2021-03-28_11.40.30.png" height="200" /> 
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example2_results/Example2_50steps_enclosed/2021-03-28_11.41.10.png" height="200" /> 
</p>

Fencing on the roof has been removed by enclosure.


### Example 3
With alpha = 1.0, rectangular shapes, merge operations.
<p float="left">
  <img src="https://github.com/gillishermans/sigi_results/blob/main/examples/example3.png" height="200" />
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example3_results/Example3_50steps/2021-03-27_14.21.01.png" height="200" /> 
</p>

No suitable enclosed buildings were found for these parameters.



### Example 4
With alpha = 1.0, rectangular shapes, merge operations, overlap allowed.
<p float="left">
  <img src="https://github.com/gillishermans/sigi_results/blob/main/examples/example4.png" height="200" />
  <img src="" height="200" /> 
  <img src="" height="200" /> 
</p>



### Example 5
With alpha = 1.0, planar shapes and both operations.
<p float="left">
  <img src="https://github.com/gillishermans/sigi_results/blob/main/examples/example5.png" height="200" />
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example5_results/Example5_20steps/2021-03-27_15.38.58.png" height="200" /> 
</p>

No suitable enclosed buildings were found for these parameters.

### Example 6
With alpha = 1.0, planar shapes and merge operations.

<p float="left">
  <img src="https://github.com/gillishermans/sigi_results/blob/main/examples/example6.png" height="200" />
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example6_results/Example6_50steps/2021-03-27_16.49.51.png" height="200" /> 
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example6_results/Example6_50steps_enclosed/2021-03-27_16.51.39.png" height="200" /> 
</p>

### Example 7
With alpha = 1.0, planar shapes and merge operations.

<p float="left">
  <img src="https://github.com/gillishermans/sigi_results/blob/main/examples/example7.png" height="200" />
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example7_results/Example7_50steps/2021-03-28_12.20.37.png" height="200" /> 
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example7_results/Example7_50steps_enclosed/2021-03-28_12.23.20.png" height="200" /> 
</p>

### Example 8
With alpha = 1.0, planar shapes and merge operations.

<p float="left">
  <img src="https://github.com/gillishermans/sigi_results/blob/main/examples/example8.png" height="200" />
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example8_results/Example8_50steps/2021-03-27_14.36.47.png" height="200" /> 
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example8_results/Example8_20steps_enclosed/2021-03-27_14.47.11.png" height="200" />
</p>

In this case, planar shapes are horizontal slices of the example building, thus allowing protruding balconies in the enclosed buildings.

### Example 9
With alpha = 1.0, rectangular shapes and merge operations.
<p float="left">
  <img src="https://github.com/gillishermans/sigi_results/blob/main/examples/example9.png" height="200" />
  <img src="https://github.com/gillishermans/sigi_results/blob/main/example9_results/Example9_50steps/2021-03-27_12.13.58.png" height="200" /> 
</p>

No suitable enclosed buildings were found for these parameters.
