# Jekyll Starter Project

## What is this?

View the demo at [http://shanetheboland.github.io/jekyll-starter](http://shanetheboland.github.io/jekyll-starter "Jekyll Starter - Pretty much nothing but the bare necessities. The simple bare necessites.")

Jekyll Starter is a blank project template to help you rapidly create Jekyll projects.
It handles most of the boring things I find myself doing, every project, over and over again.

## Features

* sass compilation
* css minification
* local server for serving a static site (jekyll serve)
* browser reload on filesave (jekyll serve --watch)

## Getting Started

* Create a new repo for your project on Github
* In terminal run
```bash
    git clone git@github.com:shanetheboland/jekyll-starter.git yourNewRepoName
    cd yourNewRepoName
    rm -rf .git
    git init
    git remote add origin git@github.com:yourUserName/yourNewRepoName.git
```

* git remote -v will allow you to check that you have changed the remote origin correctly. The output should look like:
```bash
    origin git@github.com:yourUserName/yourNewRepoName.git (fetch)
    origin git@github.com:yourUserName/yourNewRepoName.git (push)
```

## Dev Environment
To set up a convenient dev environment run this at the root of mnml

```bash
jekyll serve --watch
```

now open your favorite web browser and navigate to http://127.0.0.1:4000

```
great job, you did it.
```


* Once you add & commit files you are ready to publish run:
```bash
git push origin master
```

# Author

[Shane Boland](http://shaneboland.com "Shane Boland - Frontend Developer")

# License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

