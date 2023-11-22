# TypeScript

--> TypeScript is a programming language to address shortcomming of JavaScript

--> javascript and typescript like two brothers,
    javascript dont have any discipline while typescript is javascript with more disciplined

--> TypeScript is build on top of javascript so, each javascript file   is  valid TS file 
    
# Benifits of TypeScript :
  1. Static typing
  2. code completion
  3. Refactoring
  4. Shorthand Notation

# Static typing : -
    TS made js from dynamically typing language to static type language where type of variable is declared at the time of the declaration so at the time of compilation it will not be changed .
    
   --> in javascript it is fine  
       let number = 10; -->int
       number ="abc"  ---> string
       This flexiblity is good, but creates problem sometime and cause of getting code crashed

   --> in typeScript: 
                   let x: number = 10;
                   x= "abc"  --> error (it will not consider in typescript);
       
    ---> typeScript's job  is mainly type checking

 # Drawbacks of TypeScript

 1. Complation : always have complie first to make .ts to .js file because brwser knows only javascript

2. More Discipline


# to complie typescript file => tsc file.ts
  this will genarate a js file => file.js

#   create a config file for ts copliler :
 -> tsc --init

# some most common config setting :

1.  "target":"es2016",  
                                /* Set the JavaScript language version for emitted JavaScript and include compatible library declarations. */

2.  "module":"commonjs",    
                               * Specify what module code is generated. */                                
3. // "rootDir": "./",         /* Specify the root folder within your source files. */              
                                if we have a src folder and we have all .ts file ther we can chnage rootDir from "./"  to "./src"

4. // "outDir": "./",          /* Specify an output folder for all emitted files. */    
                                if we want to all generated .js file will be stored in a dist folder we can chnage rootDir from "./"  to "./dist"

