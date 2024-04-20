# Sorting Algorithms in Rust

This project provides implementations of various sorting algorithms in Rust.

## Algorithms Implemented

### Quick Sort

Quick sort is a comparison-based sorting algorithm that divides the input array into smaller sub-arrays, recursively sorts them, and then combines them to produce a sorted output.
![image](https://github.com/zhanarys000/sortingb2/assets/124418761/488786ac-c5f4-4955-89e1-74a62793dd8f)

### Selection Sort

Selection sort is a simple comparison-based sorting algorithm. It divides the input array into two parts: the sorted and the unsorted subarray. Initially, the sorted subarray is empty, and the unsorted subarray contains all elements.
![image](https://github.com/zhanarys000/sortingb2/assets/124418761/26a0aeb4-fd00-4eb8-86b4-011eafe2ac70)

### Insertion Sort

Insertion sort is another simple comparison-based sorting algorithm. It builds the sorted array one element at a time by repeatedly taking elements from the unsorted part and inserting them into their correct position in the sorted part.
![image](https://github.com/zhanarys000/sortingb2/assets/124418761/d194813d-a19a-4ccb-88ee-dafe1f521791)

### Merge Sort

Merge sort is a divide-and-conquer sorting algorithm. It divides the input array into two halves, recursively sorts the halves, and then merges them to produce a sorted output.
![image](https://github.com/zhanarys000/sortingb2/assets/124418761/3176ccd5-82db-44fc-bc0d-026a5d9ed285)

## Usage

To use these sorting algorithms, import the desired functions from the `sorting` module and call them with a mutable reference to the array or vector you want to sort.

```rust
use sorting::{quick_sort, selection_sort, insertion_sort, merge_sort};


