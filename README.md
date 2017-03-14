# travis_qmake_gcc_cpp14_coverity

Branch|[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_coverity.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_coverity)
coverity_scan|[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_coverity.svg?branch=coverity_scan)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_coverity)

<a href="https://scan.coverity.com/projects/richelbilderbeek-travis_qmake_gcc_cpp14_coverity">
  <img alt="Coverity Scan Build Status"
       src="https://scan.coverity.com/projects/12045/badge.svg"/>
</a>

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * Build system: `qmake`
 * C++ compiler: `gcc`
 * C++ version: `C++14`
 * Libraries: `STL` only
 * Code coverage: none
 * Source: one single file, `main.cpp`

More complex builds:
 * Use C++17: [travis_qmake_gcc_cpp17_coverity](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17_coverity)

Less complex builds:
 * No Coverity Scan: [travis_qmake_gcc_cpp14](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14)
 * Use C++98: [travis_qmake_gcc_cpp98_coverity](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_coverity)
 * Use C++11: [travis_qmake_gcc_cpp11_coverity](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_coverity)
