> DISCLAIMER: this is (I hope obviously) a joke.

# Chad is Wrong

Chad is wrong, but he believes he is right. But the truth is that he is in fact wrong, and I'm in fact right.

## Proof of Chad being Wrong

Chad claims that having test files next to your code causes consumers of that package to get a "polluted" autoloader.
While Chad is very convinced he is right, he is in fact wrong. To prove Chad is wrong, I've installed `league/flysystem`,
dumped an optimized autoloader, and committed the entire vendor directory.

Even though `league/flysystem` has tests in its `src` folder, they are not present here, because they are excluded in 
the [`.gitattributes` file](https://github.com/thephpleague/flysystem/blob/3.x/.gitattributes#L29).

## Frank is Right

As can be seen in this directory, Frank is in fact right about test classes not ending up in the autoloader, and there
is actually no "pollution" of the autoloader happening.

## Q/A

Q: I am Chad, am I wrong?<br/>
A: Yes, you are _f*cking_ wrong.

Q: I am Frank, am I wrong?<br/>
A: No, you are actually right. Chad is _f*cking_ wrong.
