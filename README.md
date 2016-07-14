# id3
my learning path's questions and answers collected

### How to preview `.md` file on Atom?
`ctrl` + `shift` + `m`


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
### List of my study examples and codes?

1. [barChart1 demo](http://bl.ocks.org/EmbraceLife/299f95496c6bddd88d5ddedf9a834c4c):
    1. [example for  manipulation](http://blockbuilder.org/EmbraceLife/299f95496c6bddd88d5ddedf9a834c4c): read with `cmd + option + i`
    1. How to find the above: search `EmbraceLife` [here](http://blockbuilder.org/search#user=EmbraceLife)
    2. [example src](https://gist.github.com/EmbraceLife/299f95496c6bddd88d5ddedf9a834c4c)
    3. [d3.selection.enter](https://tonicdev.com/rstrategyexplorer/578794754f7ba6120069abff)
