##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select:
An array method that "selects" all elements passed that evaluates true value when passed through the method's block. It returns an array of all elements that return a true value. 

####reject:
Opposite of select: An array method that "rejects" all elements passed that evaluates false value when passed through the method's block. It returns an array of all elements that return a false value. 

####map:
An array method that takes each element of enumerator and runs it through the block once. Returns a new array of element outputs.

####detect:
Array method which runs all elements of array to "find/detect" elements with a true value to block. Returns an array of elements that result in true or nil if nothing is found.

####inject:
An array method that combines all elements to return a single element by combining the initial two elements together until one element is the result. The return is the final combination of the method.

####partition:
An array method that passes all elements through block and returns two separate arrays. The first array returns all elements that evaluate a true value and the second array returns elements evaluating a false vlaue.

####sort:
Array method that sorts the enumerator based on the parameters of the block passed or by its own method and returns the sorted array.

####one?:
An array method that returns either a true or false value. one? returns true when **only one** element of the enumerator is evaluated true when passed through block of method.
It returns a false when the opposite results—if **more than one** element is evaluated false.

####none?:
Similar to the one? method. none? method also returns either a true or false. Method returns true when every element of the enumerator passes the block's conditions and returns false when every element fails the block.

####all?:

####empty?:

####eql?:

####include?:

####nil?:

###Hash methods:

####key?:

####keys:

####delete:

####delete_if:
