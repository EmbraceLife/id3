# id3
my learning path's questions and answers collected

-------------------

### Goal of 2016
1. d3 examples from beginner to advanced
2. node.js, React.js, React Native
3. understand d3 source code inside out
-------------------

### How to preview `.md` file on Atom?
`ctrl` + `shift` + `m`

-------------------

### How to download a single folder from a repo instead of the whole repo?
`svn checkout https://github.com/userName/RepoName/trunk/folderName`


-------------------
### How to setup env for running d3 with ES6 syntax on node.js ?

[checkout stackoverflow](http://stackoverflow.com/questions/38225993/how-to-setup-node-environment-to-run-es6-codes-involving-syntax-like-import)

**5 steps to set it up**

1. create a directory and run `npm init` at its terminal;
2. move inside this directory's terminal run:
     `npm install --save-dev PackageName`
   for the following packages:
     `browserify`, `babel-cli`, `babelify`, `babel-preset-es2015`;
3. run `npm install --save d3` or modules like `d3-color`;
4. to create `.babelrc` file:
    run `echo '{ "presets": ["es2015"] }' > .babelrc;`
5. In the terminal run scripts with:
    `./node_modules/.bin/babel-node script.js`


-------------------
### How to run `docco` for all JS scripts?

Online Resources:    

[video guide1](https://www.youtube.com/watch?v=1BEidZzIWjM)      
[video guide2](https://vimeo.com/91118854)   

** 4 steps to set it up**    

after the above 5 steps are done, install 3 packages globally with `npm`:    


1. `sudo npm install -g pygments`
2. `sudo npm install -g coffe-script`
3. `sudo npm install -g docco`
4. run `docco *.js` to create a folder `docs` with all html files for each JS file



-------------------
### What is the best debug and source study tool for d3?

combination: [bl.ocks](http://blockbuilder.org/about) and [tonic](https://tonicdev.com/)


-------------------
### How to understand Regular Expression?
paste and hover the regx pattern on [RegExr](http://regexr.com/)



-------------------
### Learn HTML and CSS basics
[12 min video on CSS](https://www.youtube.com/watch?v=0afZj1G0BIE)    
[12 min video on HTML](https://www.youtube.com/watch?annotation_id=annotation_1297474487&feature=iv&src_vid=bWPMSSsVdPk&v=KJ13lX20FqU)    
margin, padding, border    
 [video1](https://www.youtube.com/watch?v=qhiQGPtD1PQ)    
 [video2](https://www.youtube.com/watch?v=7sfft8InTPw)

### libraries to Learn:
1. React
2. React Native:
    1. [intro](https://www.youtube.com/watch?v=tJzZRhNs00I)
    2. [example]()





-------------------
### barChart examples

1. [barChart1 demo](http://bl.ocks.org/EmbraceLife/299f95496c6bddd88d5ddedf9a834c4c):
    1. [example for  manipulation](http://blockbuilder.org/EmbraceLife/299f95496c6bddd88d5ddedf9a834c4c): read with `cmd + option + i`
    1. How to find the above: search `EmbraceLife` [here](http://blockbuilder.org/search#user=EmbraceLife)
    2. [example src](https://gist.github.com/EmbraceLife/299f95496c6bddd88d5ddedf9a834c4c)
    3. [d3.selection.enter](https://tonicdev.com/rstrategyexplorer/578794754f7ba6120069abff)
    4. when `blockbuilder` is difficult to save, then save it in gist.

2. [barChart2 demo](https://bl.ocks.org/mbostock/7341714)
    1. [manipulation](http://blockbuilder.org/EmbraceLife/9245dc644a9cdf8b02f7a93339fa4c75)
    2. [d3.max](https://tonicdev.com/rstrategyexplorer/578ab15d3e25711400d0490d)
    3. [d3.selection.attr](https://tonicdev.com/rstrategyexplorer/578abe583a9f9b13009e4bb9)
    4. [d3.selection.datum](https://tonicdev.com/rstrategyexplorer/578ac80d3a9f9b13009e4dc8)   
    5. [d3.selection.data](https://tonicdev.com/rstrategyexplorer/578adfd798ae16120061983b)
    6. question1: use of x, y, dy:em?

3. [barChart3.a demon in v3](https://bl.ocks.org/mbostock/7452541):
    1. [manipulation](http://blockbuilder.org/EmbraceLife/ea98cae3b044803598b3b54fbb969abc)

4. [barChart3.b demo in v3](http://blockbuilder.org/EmbraceLife/96743288660fce0d41d253e3d5ee4521)
    1. [manipulation](http://blockbuilder.org/EmbraceLife/677054c8f535c77ddd95485523d97fcd)
    2.  [d3.scaleOrdinal.test](https://tonicdev.com/rstrategyexplorer/578c8b0866861a14000e4f5a)
    3. [d3.scaleBand.test](https://tonicdev.com/rstrategyexplorer/578cd99cebde48130007d32d)

5. [barChart3.c demo in v3](http://blockbuilder.org/EmbraceLife/fe0526cedbadbf1b434f9ddaf6a3b5b0)
    1. [manipulation](http://blockbuilder.org/EmbraceLife/645e9387c123986ea5cd290511b45562)
    2. [d3.axis.test](https://tonicdev.com/rstrategyexplorer/578e31b37fcd461300b5f894)

6. [barChart3.d demo in v3]()
    1. [manipulation](http://blockbuilder.org/EmbraceLife/460382bece9c49c11e6b91fa64cb2a9a)

### What is learnt on the above 6 barChart examples?
1. bind data
2. create svg rect for bars
3. create x-axis, y-axis
4. hover to change bar color
5. scaleBand to map bar width on canvas
6. scaleLinear to map bar height on canvas
-------------------


### Histogram [Example1](http://blockbuilder.org/EmbraceLife/46746758004aa5535da4cb32616f9307)
1. [d3.random md](https://github.com/d3/d3-random)
1. d3.randomBates: read src `bates.js` and `irwinHall.js`
2. [d3.format md](https://github.com/d3/d3-format)
2. [How to round to specific decimal points?](https://tonicdev.com/rstrategyexplorer/5790207e59017413003e4729)
3. [How to check inside a format specifier?](https://tonicdev.com/rstrategyexplorer/579028b4a7fc6613006b744e)
3. [How to create a histogram frame](https://tonicdev.com/rstrategyexplorer/57903d207bc70812004f99a6)

### Histogram [example2](http://blockbuilder.org/EmbraceLife/eed2f62f855854739ddf5e572d4322ed)
1. d3-time-format [md](https://github.com/d3/d3-time-format)

------------

### Line transition
1. d3.randomNormal [how to use](https://tonicdev.com/rstrategyexplorer/5790d4ef54df4e1300f9e006)
2. 
