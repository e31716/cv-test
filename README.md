[![Build Status](https://travis-ci.org/e31716/cv-test.svg?branch=master)](https://travis-ci.org/e31716/cv-test)

## Purpose
Deploy static page to GitHub Page after checking in by Travis CI

## Steps

1. Install module gh-pages: npm i gh-pages --save-dev
2. Add deploy script in package.json: ("deploy": "gh-pages -d dist")
3. Push the files above with your project to Github
4. Generate Gihub token (https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)
5. Add token to Travis CI's environment variables
6. Trigger build 
7. Check environment tab and view deployment

## Reference
https://github.com/nukc/how-to-use-travis-ci

## TEST