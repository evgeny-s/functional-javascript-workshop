# Functional Javascript Workshop

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/nodeschool/discussions?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
<img alt="NodeSchool Discussions" src="https://f.cloud.github.com/assets/43438/1368315/63919ad8-3997-11e3-909e-8193f5a94b59.png" align="right">

### Teaching fundamental functional programming features of Javascript.

#### No libraries required (i.e. no underscore), just ES5.

<a href="https://nodei.co/npm/functional-javascript-workshop/" ><img src="https://nodei.co/npm/functional-javascript-workshop.png?downloads=true&stars=true"><br />
<img src="https://nodei.co/npm-dl/functional-javascript-workshop.png?months=12">
</a>



[![Gittip](http://img.shields.io/gittip/timoxley.png)](https://www.gittip.com/timoxley/)
## Mission

Many functional programming learning resources will teach you to write functional code, but it's often highly indirect,
deeply abstracted, requires understanding complex relationships between custom library calls, and doesn't represent
the reality of how people actually write JavaScript.

The goal of this workshop is to create realistic problems that can be solved using terse, vanilla, idiomatic JavaScript.

**Please read the exercises thoroughly and obey all conditions, they are there to help you learn!**

## Installation & Update

```
$ npm install
```

Some npm installations require use of `sudo` in the above command. Recommend to instead [reinstall node/npm so you don't need sudo](https://gist.github.com/isaacs/579814).

## Usage Instructions

#### 1. Selecting a problem to work on

Once the workshop is installed, run `functional-javascript-workshop` to print a menu
where you can select a problem to work on.

```
$ npm run start
```

Problems are listed in rough order of difficulty. You are advised to complete them in order, as later problems
will build on skills developed by solving previous problems.

#### 2. Writing your solution

Once you have selected a problem, the workshop will remember which problem you are working on.
Using your preferred editor, simply create a file to write your solution in. Most problems will
supply some boilerplate with which to get started. Copy this from the problem description to your
solution file.

#### 3. Testing your solution

Use the workshop's `run` command to point the workshop at your solution file. Your solution will be loaded 
and passed the problem input. This usually won't perform any validation, it will only show the program output.

```
$ npm run test ./my-solutions/solution.js
```

#### 4. Verifying your solution

Your solution will be verified against the output of the 'official' solution.
If all of the output matches, then you have successfully solved the problem!

```
$ npm run verify ./my-solutions/solution.js
```

## Screenshots

![screen shot 2013-09-27 at 5 18 45 pm](https://f.cloud.github.com/assets/43438/1225514/08c87a70-276a-11e3-8db7-485e3c760373.png)
![screen shot 2013-09-23 at 9 13 02 pm](https://f.cloud.github.com/assets/43438/1191466/f289f38a-2451-11e3-9ba5-a3c224b5ca97.png)
