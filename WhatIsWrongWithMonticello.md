What is wrong with Monticello? 

What is wrong with Monticello depends upon which Monticello you are talking about. 
There is nothing wrong with the Monticello that implements Smalltalk packages.
There is nothing wrong with the Monticello that implements version control for Smalltalk packages other than the fact that Monticello packages and Monticello version control are conflated into a single Monticello

## Monticello Packages

Monticello packages are based on the ideas first described by Allen Wirfs-Brock and Brian Wilkerson in their paper "[An overview of modular smalltalk'][2]" and summarized in Allen's paper "[A Declarative Model for Defining Smalltalk Programs][1]".

A Monticello package is defined as a collection of class and method definitions. 
To store a package on disk one needs only to serialize the collection of definitions to disk. 

[1]: www.smalltalksystems.com/publications/_awss97/SSDCL1.HTM
[2]: http://dl.acm.org/authorize?61095
