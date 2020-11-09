# MiniProject_IMDB

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/ba7459d0ef614d4eab38b5d174f42a8d)](https://www.codacy.com/gh/99002625/MiniProject_IMDB/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=99002625/MiniProject_IMDB&amp;utm_campaign=Badge_Grade)      ![Unit Test](https://github.com/99002625/MiniProject_IMDB/workflows/Unit%20Test/badge.svg)
 ![cppcheck-action](https://github.com/99002625/MiniProject_IMDB/workflows/cppcheck-action/badge.svg?branch=master)
 ![Valgrind](https://github.com/99002625/MiniProject_IMDB/workflows/Valgrind/badge.svg?branch=master)
 ![C/C++ CI](https://github.com/99002625/MiniProject_IMDB/workflows/C/C++%20CI/badge.svg?branch=master)

# Design
* Base class Movies
    * Data Membes :
        -   Title
        -   Creators
        -   Country   
        -   Year
        -   Genre
    

    * Derived Class IMDB
        * Data Members
            - rating
            - totalVotes
`

# Commands

g++ test.cpp imdb.cpp movies.cpp -c
g++ test.o imdb.o movies.o -lgtest -lgtest_main -lpthread -o out
./out

g++ testDB.cpp imdbDB.cpp imdb.cpp movies.cpp -c
g++ testDB.o imdbDB.o imdb.o movies.o -o out
g++ testDB.cpp imdbDB.cpp imdb.cpp movies.cpp -o out
