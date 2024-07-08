
# KeyZen Miryoku Edition

## About

This is a fork of [Keyzen-Miryoku by bashu](https://github.com/bashu/keyzen-miryoku), modified for learning the [Canary](https://github.com/Apsu/Canary) keyboard layout in addition to the [Miryoku](https://github.com/manna-harbour/miryoku)layout. 

The key sequence focuses on learning the base layer alphas home row, then gradually introduces keys in the top and bottom rows. Common punctuation and web navigation characters are added to the mix after learning every lowercase letter. Alpha letters and uncommon punctuation marks are added last.

KeyZen automatically adds new characters to the mix as your errors decrease. Click on the character sequence at the top to increase or decrease difficulty.


## Hosted Version

You can use keyzen-canary without installing it. All you need is an internet connection:

http://adharm.github.io/keyzen-canary/


## Local Version/Installation

If you're offline, or GitHub Pages is not accessible, or want to modify some parts and run it locally, you could easily do that using a local web server. Here are samples using the mainstream Python/PHP utilities:


1. [Download the repo](https://github.com/adharm/keyzen-canary/archive/master.zip) and unzip it in your local.

2. Go to the unzipped folder, and start the local server.
    - Python
        - `python3 -m http.server`
    - PHP
        - `php -S 0.0.0.0:8000`

3. Go to `http://0.0.0.0:8000` in your browser.
