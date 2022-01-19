
# KeyZen Colemak-DH


## About

This project was inspired by [KeyZen Colemak](http://first20hours.github.com/keyzen-colemak/), which was implemented by Josh Kaufman, and featured in his [**The First 20 Hours**](https://first20hours.com/) book (one of his personal challenges is to learn Colemak in 20 hours in which he succeeded).

Kaufman's project is based on [KeyZen](https://github.com/wwwtyro/keyzen) which has numerous changes since he cloned it. So, I've used the original KeyZen repo and based my fork from it and added features/improvements that I think were lacking. Personally, I use this everyday upon waking up to strengthen my grasp of the entire alphabet since most of the time I practice on common letters only (i.e. bigrams, trigrams, Top 200 words, etc).

Aside from my added features, I modified also the default sound files for correct/incorrect keys for better user experience, and updated the `jQuery` library to latest version since the bundled version is 10 years old already. This will make it easier for others to extend the code.


## Features
* Character sequences are generated randomly, new letters are introduced as your level increases. Home row, top row, then bottom row.
* If you commit mistakes, the letters will be reintroduced again to maximize training.
* Characters could be reset/skipped by clicking on it.
* Intensity/rigor could be adjusted.
* Speed/accuracy stats are displayed.
* There's a timer once you start typing to keep track your progress, or for better planning.
* Useful for beginners to familiarize the keys.
* Useful for experienced ones to strengthen their weaknesses (e.g. specific letters, capital letters, punctuations, etc).
* Keyboard layout could be chosen. **Colemak-DH** (angle mod) is the default/recommended.
* Keyboard layout images are displayed accordingly as a handy reference.
* QWERTY is included for legacy purposes and for promoting touch typing to people.
* Custom layout/limited set of characters could be specified (specific punctuations, numbers, capitalized letters, etc).


## Hosted Version
If you're online, you could access it here:
https://ranelpadon.github.io/keyzen-colemak-dh/


## Local Version/Installation
If you're offline, or GitHub Pages is not accessible, or want to modify some parts and run it locally, you could easily do that using a local web server. Here are samples using the mainstream Python/PHP utilities:


1. [Download the repo](https://github.com/ranelpadon/keyzen-colemak-dh/archive/master.zip) and unzip it in your local.

2. Go to the unzipped folder, and start the local server.
    - Python
        - Python 2
            - `python -m SimpleHTTPServer`
        - Python 3
            - `python3 -m http.server`
    - PHP
        - `php -S 0.0.0.0:8000`

3. Go to `http://0.0.0.0:8000` in your browser.


