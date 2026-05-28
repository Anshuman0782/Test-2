# Project Overview
This repository provides an optimized implementation of Bubble sort for sorting arrays of integers.

## Tech Stack
* C programming language
* Standard Libraries:
	+ `stdbool.h` for boolean types and constants
	+ `stdio.h` for input/output operations

## Features
* **Bubble Sort**: An optimized version of Bubble Sort for sorting arrays of integers
* **Array Sorting**: Sorts an array of integers in ascending order

## Project Structure
The repository consists of a single file:
* `sort.c`: Contains the optimized implementation of Bubble Sort

## Local Setup
To build and run the code, follow these steps:
1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd <project_directory>`
3. Compile the code: `gcc sort.c -o sort`
4. Run the code: `./sort`

## Environment Variables
N/A

## Usage Flow
To use the Bubble Sort implementation:
1. Include the necessary headers: `#include <stdbool.h>` and `#include <stdio.h>`
2. Define the array to be sorted: `int arr[] = {64, 34, 25, 12, 22, 11, 90};`
3. Calculate the size of the array: `int n = sizeof(arr) / sizeof(arr[0]);`
4. Call the `bubbleSort` function: `bubbleSort(arr, n);`
5. Print the sorted array: `printArray(arr, n);`

## Safety Notes
Use secure input/output operations and handle errors properly when integrating this code into your project.

## Roadmap
There is no current roadmap for future development or updates. This repository provides a standalone implementation of Bubble Sort.

## Contributing
To contribute to this repository, fork the project and submit a pull request with your changes.
