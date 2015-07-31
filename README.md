jest-no-less
============

Enforces minimum code coverage for Jest test output.

## Installation

    npm install jest-no-less --save-dev

## Usage

    # Draconian mode
    jest --coverage | jest-no-less --min-lines 100 --min-funcs 100 --min-stmts 100
    
    # Just 80% of statements
    jest --coverage | jest-no-less --min-stmts 80


`--min-lines <value>`
Minimum line coverage percentage.

`--min-funcs <value>`
Minimum function coverage percentage.

`--min-stmts <value>`
Minimum statement coverage percentage.
