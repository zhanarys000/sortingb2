# Sorting Algorithms in Rust

This project provides implementations of various sorting algorithms in Rust.

## Algorithms Implemented

### Quick Sort

Quick sort is a comparison-based sorting algorithm that divides the input array into smaller sub-arrays, recursively sorts them, and then combines them to produce a sorted output.

### Selection Sort

Selection sort is a simple comparison-based sorting algorithm. It divides the input array into two parts: the sorted and the unsorted subarray. Initially, the sorted subarray is empty, and the unsorted subarray contains all elements.

### Insertion Sort

Insertion sort is another simple comparison-based sorting algorithm. It builds the sorted array one element at a time by repeatedly taking elements from the unsorted part and inserting them into their correct position in the sorted part.

### Merge Sort

Merge sort is a divide-and-conquer sorting algorithm. It divides the input array into two halves, recursively sorts the halves, and then merges them to produce a sorted output.

## Usage

To use these sorting algorithms, import the desired functions from the `sorting` module and call them with a mutable reference to the array or vector you want to sort.

```rust
use sorting::{quick_sort, selection_sort, insertion_sort, merge_sort};

fn main() {
    let mut numbers = vec![9, 7, 5, 3, 0, 1, 4, 2, 8];
    quick_sort(&mut numbers);
    println!("Numbers Quick Sorted: {:?}", numbers);

    let mut words = vec!["mustang", "camaro", "corvette", "challenger", "civic"];
    selection_sort(&mut words);
    println!("Words Selection Sorted: {:?}", words);

    let mut floats = vec![1.5, 2.5, 3.5, 4.5, 6.5];
    insertion_sort(&mut floats);
    println!("Insertion Sorted: {:?}", floats);

    let mut characters = vec!['z', 'y', 'x', 'w', 'v'];
    merge_sort(&mut characters);
    println!("Characters Merge Sorted: {:?}", characters);
}
