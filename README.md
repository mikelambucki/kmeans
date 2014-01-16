An node.js javascript implementation of Kmeans
=====

This is a javascript/node.js based implementation of the kmeans algorithm for clustering vectors. It was an opportunity for me to practice some skills. Hopefully it will be useful for some people trying to learn the theory behind kmeans!

 * Creating a javascript library
 * Experimenting with documentation via docco
 * Play with github pages!


Technical tutorial
---

The [code/tutorial][kt] for this library, created with [docco][doc],  explains the theory behind kmeans and shows how this library works!

[kt]:http://stevemacn.github.io/docs/cmeans.html
[doc]:https://github.com/jashkenas/docco

Setup
---
    npm install

Usage
---
    //Creating 3 clusters with vector dataset

    var vector = [
        [10, 2, 30],
        [30, 20, 2],
        [30, 30, 3],
        [10, 10, 1],
        [20, 1, 30],
        [1, 25, 30]
    ]
    
    kmeans(vector, 3, function(err, res) {
        if (err) throw new Error(err)

        //do something with the result
    })


Testing
---
    npm test
    
Disclaimer
---
This library was created mostly for practice and in my haste I may have missed something. Please submit issues if ANYTHING is wrong or even if you have suggestions on how ANYTHING can be improved!
