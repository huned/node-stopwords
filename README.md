# Stopwords for node.js #

main repo: [https://github.com/huned/node-stopwords](https://github.com/huned/node-stopwords)

## Overview ##

Stopwords in multiple languages that you can easily use with your node.js
programs. Currently provides stopwords for the following languages:

* English
* French
* German
* Spanish

Stopwords in other languages are welcome as pull requests to
[https://github.com/huned/node-stopwords](https://github.com/huned/node-stopwords)

## Install ##

    npm install stopwords

## Usage ##
```es6
    // get an array of english stopwords
    require('stopwords').english;
    
    // get an array of french stopwords
    require('stopwords').french;

    // get an array of german stopwords
    require('stopwords').german;

    // get an array of spanish stopwords
    require('stopwords').spanish;
```
## Contributors

* Marcel Radischat (contributed German stopwords)
* Leonardo Giovanetti (contributed Spanish stopwords)
* Jean-Elie Barjonet (contributed French stopwords)
* Huned Botee (original author)

## License ##

MIT
