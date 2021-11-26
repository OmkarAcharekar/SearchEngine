<h1 align="center">
  <br style="font-size:300%;">
  <p>Search Engine</p>
  <br>
</h1>

<h4 align="center">Project mimics the functionality of a Web Browsers Search Engine</h4>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![React_Native](https://img.shields.io/badge/react%20native-v0.66-orange)
[![Build Status](https://img.shields.io/badge/build-passing-green)](https://img.shields.io/badge/build-passing-green)
![Dependencies](https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-orange.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#download">Download</a> •
  <a href="#credits">Credits</a> •
  <a href="#related">Related</a> •
  <a href="#license">License</a>
</p>

## About

 Implemented Splay Tree data structure , to access recent Data Efficiently. Standard Implementation using structures, nodes and classes have been used to implement this project.Splay Trees operations such as insertion, look-up and removal are performed in O(log(n)) amortized time.

## Key Features

* We can Access our search history
* We can know the most frequently browsed site by us
* We can know the most recently browsed site.
* we get suggestion based on our previous searches
* We can delete our browser history.

## How To Use

To clone and run this application, you should have [Git](https://git-scm.com/downloads), [Mingw C++ Compiler](https://sourceforge.net/projects/mingw/) installed on your computer. If you don't have Mingw C++ Compiler see installation [here](https://medium.com/@ssaaziondebeat/how-to-use-and-installing-gcc-or-mingw-compiler-dcc9c503e217)

From your command line:

```bash
# Clone this repository
$ git clone https://github.com/OmkarAcharekar/SearchEngine

# Go into the repository
$ cd SearchEngine

# Compile Program
$  g++ search_engine_main.cpp -o search_engine_main

# Run Program
$ .\search_engine_main



## Demo

```bash

A:\CompetativeVisual\Search_Engine> g++ search_engine_main.cpp -o search_engine_main
A:\CompetativeVisual\Search_Engine>.\search_engine_main

**    SEARCH ENGINE    **

 A search engine is a software program that helps people find the information 
 they are looking for online using keywords or phrases. This allows to search 
 the World Wide Web in a systematic way for particular 
information specified in a textual web search query.


This Application mimics the working of the Today Modern Browser.
 It also show time of search along with the Data 

CONTINUE: Yes/No : Yes


                Select operation you want to perform :
                ------------------------------------- 

        1.Make a search 
        2.Remove your search from history 
        3.Access your search history 
        4.Most frequently browsed.
        5.Most recently browsed 
        6.To give suggestions. 
        7.Display search history 
        8.Empty the browser history 
        9.Clear browser history and Exit 
        10.Exit 

Enter your option: 1

Search or type a URL:  www.google.com

                        ** Search History: **
Fri Nov 26

                www.google.com :: 22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 1

Search or type a URL:  www.twitter.com

                        ** Search History: **
Fri Nov 26

                www.twitter.com :: 22:17:53
                www.google.com :: 22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 1   

Search or type a URL:  www.facebook.com

                        ** Search History: **
Fri Nov 26

                www.facebook.com :: 22:18:07
                www.twitter.com :: 22:17:53
                www.google.com :: 22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 1 

Search or type a URL:  www.google.com

                        ** Search History: **
Fri Nov 26

                www.google.com :: 22:18:45
                www.facebook.com :: 22:18:07
                www.twitter.com :: 22:17:53
                www.google.com :: 22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 1

Search or type a URL:  www.facebook.com

                        ** Search History: **
Fri Nov 26

                www.facebook.com :: 22:19:04
                www.google.com :: 22:18:45
                www.facebook.com :: 22:18:07
                www.twitter.com :: 22:17:53
                www.google.com :: 22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 1  

Search or type a URL:  www.google.com

                        ** Search History: **
Fri Nov 26

                www.google.com :: 22:19:21
                www.facebook.com :: 22:19:04
                www.google.com :: 22:18:45
                www.facebook.com :: 22:18:07
                www.twitter.com :: 22:17:53
                www.google.com :: 22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 1

Search or type a URL:  www.google.com

                        ** Search History: **
Fri Nov 26

                www.google.com :: 22:20:05
                www.google.com :: 22:19:21
                www.facebook.com :: 22:19:04
                www.google.com :: 22:18:45
                www.facebook.com :: 22:18:07
                www.twitter.com :: 22:17:53
                www.google.com :: 22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 3             

        Access searches:

                        ** Search History: **
Fri Nov 26

                www.google.com :: 22:20:05
                www.google.com :: 22:19:21
                www.facebook.com :: 22:19:04
                www.google.com :: 22:18:45
                www.facebook.com :: 22:18:07
                www.twitter.com :: 22:17:53
                www.google.com :: 22:17:39
                
  Enter your option: 3

        Access searches:

                        ** Search History: **
Fri Nov 26

                www.google.com :: 22:20:05
                www.google.com :: 22:19:21
                www.facebook.com :: 22:19:04
                www.google.com :: 22:18:45
                www.facebook.com :: 22:18:07
                www.twitter.com :: 22:17:53
                www.google.com :: 22:17:39


Enter keyword: www.google.com
                www.google.com :: 22:20:05
                www.google.com :: 22:19:21
                www.google.com :: 22:18:45
                www.google.com :: 22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 4

To check frequencies of searches made:



                The most frequently browsed searches:
        www.google.com :: 22:20:05 searched  1 times.

        www.google.com :: 22:19:21 searched  1 times.

        www.google.com :: 22:18:45 searched  1 times.

        www.google.com :: 22:17:39 searched  1 times.


                The least frequently browsed searches:
        www.facebook.com :: 22:19:04 searched  0 times.
        www.facebook.com :: 22:18:07 searched  0 times.
        www.twitter.com :: 22:17:53 searched  0 times.

                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 5


         Most recently accessed node:
 www.google.com :: 22:20:05

                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 6

        SUGGESTIONS:

Enter keyword (length 3)  :www
www.google.com  ::  22:20:05
www.google.com  ::  22:19:21
www.facebook.com  ::  22:19:04
www.google.com  ::  22:18:45
www.facebook.com  ::  22:18:07
www.twitter.com  ::  22:17:53
www.google.com  ::  22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 7

                        ** Search History: **
Fri Nov 26

                www.google.com :: 22:20:05
                www.google.com :: 22:19:21
                www.facebook.com :: 22:19:04
                www.google.com :: 22:18:45
                www.facebook.com :: 22:18:07
                www.twitter.com :: 22:17:53
                www.google.com :: 22:17:39


                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 8


 History is cleared!!!

                        ** Search History: **
Fri Nov 26



                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 3

        Access searches:

                        ** Search History: **
Fri Nov 26



Enter keyword: www.google.com

Search not found

                Select operation you want to perform :
                -------------------------------------

        1.Make a search
        2.Remove your search from history
        3.Access your search history
        4.Most frequently browsed.
        5.Most recently browsed
        6.To give suggestions.
        7.Display search history
        8.Empty the browser history
        9.Clear browser history and Exit
        10.Exit

Enter your option: 9

Browser History cleared!

THANK YOU! VISIT LATER TO CHECK THE SEARCH HISTORY! :)

## You may also like...

- [Netflix](https://github.com/amitmerchant1990/pomolectron) - A Netflix clone
- [Air Sense](https://github.com/amitmerchant1990/correo) - Air Quality Predictor and Weather Application


## License

MIT

---

> [omkaracharekar.com](https://www.amitmerchant.com) &nbsp;&middot;&nbsp;
> GitHub [OmkarAcharekar](https://github.com/OmkarAcharekar) &nbsp;&middot;&nbsp;
