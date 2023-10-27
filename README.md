# Cpp-Searching

This repository provides C++ implementations and explanations of two common searching algorithms: Linear Search and Binary Search. Each algorithm is detailed with corresponding C++ code and usage instructions.

## Table of Contents
- [Linear Search](#linear-search)
- [Binary Search](#binary-search)
- [Usage](#usage)
- [Contributions](#contributions)

## Linear Search

Linear Search is a straightforward search algorithm that checks each element in the array sequentially until a match is found. It is suitable for unsorted data.

### Algorithm

1. Start from the beginning of the array.
2. Compare each element with the target value.
3. If a match is found, return the index; otherwise, continue to the next element.
4. Repeat until the end of the array is reached or the target value is found.

### Code
You can find the Linear Search code in the `linear search.cpp` file.

## Binary Search

Binary Search is an efficient search algorithm that is applicable to sorted data. It repeatedly divides the search interval in half and compares the target value with the middle element.

### Algorithm

1. Start with the entire array.
2. Calculate the middle index of the search interval.
3. Compare the middle element with the target value.
4. If the middle element matches the target, return its index.
5. If the middle element is greater than the target, search the left half.
6. If the middle element is less than the target, search the right half.
7. Repeat the process with the remaining half until the target is found or the search interval is empty.

### Code
You can find the Binary Search code in the `binary search.cpp` file.

## Linear Search: 
![Screenshot 2023-10-25 194046](https://github.com/Arjun378/Cpp-Searching/assets/74441883/2b0eaea3-d8e1-4be0-a7e7-2969c6abc480)

![Screenshot 2023-10-25 194127](https://github.com/Arjun378/Cpp-Searching/assets/74441883/8b5babf3-227f-4d9e-bfc1-fc34fb99a4b3)

## Binary Search:
![Screenshot 2023-10-25 194318](https://github.com/Arjun378/Cpp-Searching/assets/74441883/8eabe27f-5856-4378-ab02-b7ce9cfe9cf5)

![Screenshot 2023-10-25 194357](https://github.com/Arjun378/Cpp-Searching/assets/74441883/13bac56d-9c46-4792-b9de-b556bfec2da0)
