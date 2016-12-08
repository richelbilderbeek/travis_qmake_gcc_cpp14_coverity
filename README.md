# travis_qmake_gcc_cpp14_coverity

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_coverity.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp14_coverity)
<a href="https://scan.coverity.com/projects/richelbilderbeek-travis_qmake_gcc_cpp14_coverity">
  <img alt="Coverity Scan Build Status"
       src="https://scan.coverity.com/projects/11101/badge.svg"/>
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
 * Use C++17: [travis_qmake_gcc_cpp17](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp17)
 * Add `Bio++`: [travis_qmake_gcc_cpp14_coverity_bpp](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_bpp)
 * Add `Boost`: [travis_qmake_gcc_cpp14_coverity_boost](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_boost)
 * Add `Boost.Test`: [travis_qmake_gcc_cpp14_coverity_boost_test](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_boost_test)
 * Add code coverage: [travis_qmake_gcc_cpp14_coverity_gcov](https://github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_gcov)
 * Add `gprof`: [travis_qmake_gcc_cpp14_coverity_gprof](https://github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_gprof)
 * Add `OCLint`: [travis_qmake_gcc_cpp14_coverity_oclint](https://github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_oclint)
 * Add `perf`: [travis_qmake_gcc_cpp14_coverity_perf](https://github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_perf)
 * Add `Qt`: [travis_qmake_gcc_cpp14_coverity_qt](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_qt)
 * Add `SFML`: [travis_qmake_gcc_cpp14_coverity_sfml](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_sfml)
 * Add `Rcpp`: [travis_qmake_gcc_cpp14_coverity_rcpp](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_rcpp)
 * Add `Urho3D`: [travis_qmake_gcc_cpp14_coverity_urho3d](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_urho3d)
 * Add `Wt`: [travis_qmake_gcc_cpp14_coverity_wt](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_coverity_wt)

Less complex builds:
 * Use C++98: [travis_qmake_gcc_cpp98_cov](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98)
 * Use C++11: [travis_qmake_gcc_cpp11](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11)
