# libdate
liveCode library to handle date and time functions

## Usage

To use this library, don't use *string* for date, but just *commas*. 

For example this is **wrong**:

    put "2010,1,1" into temp
    put  libDate_DayNumber(temp)

On the contrary this is **correct**:

    put 2010,1,1 into temp
    put  libDate_DayNumber(temp)

## Installation

Copy the the content of **libdate.script** from in stack script of your program
