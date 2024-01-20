## Introduction
* This repository provides implementations of our algorithm for fair k-center clustering with outliers, published in AISTATS2024.

## How to use

### Dataset
* Put "_dataset" directory.
* Format is easy to see from adult_gender.csv
    * The first d rows are numeric attribute values, and the last row is group.
* Dataset ID follows:
    * adult-gender: 0
    * adult-race: 1
    * covertype: 2
    * diabetes-gender: 3
    * diabetes-race: 4
    * mirai: 5
    * kdd-cup: 6
    * Due to the size limitation, we omit Mirai and synthetic datasets.

### Parameter
* They are controllable by .txt files.
* See `parameter` directory.

### Ours
* If you wanna activate random sampling, use "ours_sampling.hpp" instead of "ours.hpp".

### Result
* See `output_result()`.

### Execution
* Compile: g++ -O3 -o xxx.out main.cpp
* Run: ./xxx.out
* Note: xxx can be arbitrary.
