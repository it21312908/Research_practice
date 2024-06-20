# Research_practice


## 1. count LOC
## Features

- Clone a Git repository to a local directory.
- Count lines of code in each file of the repository.

## Requirements

- Python 3.x
- `gitpython` library
- `pandas` library

## Installation

1. Clone this repository to your local machine.


git clone https://github.com/your-username/your-project.git
ex:- !git clone https://github.com/idealo/image-super-resolution.git

2. Go to the directory
!ls

cd your-project
!ls <- To get the directory

3. Count the Lines Of Codes
4. Store it in a csv file
5. Read the csv file by importing pandas



## 2. count CC - Cyclomatic Complexity

## Requirements

- Python 3.x
- `gitpython` library
- `pandas` library
- `radon` library

- ## Installation

1. Clone this repository to your local machine.


git clone https://github.com/your-username/your-project.git
ex:- !git clone https://github.com/idealo/image-super-resolution.git

2. Go to the directory
!ls

cd your-project
!ls <- To get the directory

3. Import libraries
   -!pip install radon
   -from radon.complexity import cc_visit
    -from radon.visitors import ComplexityVisitor 
4. Count the complexity
5. Store it in a csv file
6. Read the csv file by importing pandas
