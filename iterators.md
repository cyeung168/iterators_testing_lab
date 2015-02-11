##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select:
An enumerator method that "selects" all elements passed that evaluates true value when passed through the method's block. It returns an array of all elements that return a true value. 

####reject:
Opposite of select: An enumerator method that "rejects" all elements passed that evaluates false value when passed through the method's block. It returns an array of all elements that return a false value. 

####map:
An enumerator method that takes each element of enumerator and runs it through the block once. Returns a new array of element outputs.

####detect:
Enumerator method which runs all elements of enumerator to "find/detect" elements with a true value to block's conditions. Returns an array of elements that result in true or nil if nothing is found.

####inject:
An enumerator method that combines all elements to return a single element by combining the initial two elements together until one element is the result. The return is the final combination of the method.

####partition:
An enumerator method that passes all elements through block and returns two separate arrays. The first array returns all elements that evaluate a true value and the second array returns elements evaluating a false vlaue.

####sort:
Enumerator method that sorts the enumerator based on the parameters of the block passed or by its own method and returns the sorted array.

####one?:
An enumerator method that returns either a true or false value. one? returns true when **only one** element of the enumerator is evaluated true when passed through block of method.
It returns a false when the opposite results—if **more than one** element is evaluated false.

####none?:
Similar to the one? method. none? method also returns either a true or false. Method returns true when every element of the enumerator passes the block's conditions and returns false when every element fails the block.

####all?:
Enumerator method that passes all elements through block to evaluate a true or false value. It returns a true value when all elements in the array pass the block's conditions otherwise false or nil.

####empty?:
Method that checks to if enumerator is has content and returns true or false. For example if an array has elements or if a hash contains any key/value pairs.

####eql?:
Method that compares if the enumerator has the same content as the parameter passed. It returns a true or false based on the evaluation of the method.

####include?:
Method that checks to see if the parameter is found in the enumerator. If parameter is "included" or passes the condition, method returns a true value and false for vice versa.

####nil?:
Checks to see if enumerator is nil. Only a nil object returns true for nil?.

###Hash methods:

####key?:
Method that checks if key parameter passed is contained within the hash. Method returns a boolean value.

####keys:
Method that lists the keys in a hash. Returns an array of keys contained in a hash.

####delete:
Method that takes a key as a parameter to delete the referencing key/value pair in the hash. Returns the values corresponding to the key parameter.

####delete_if:
Deletes all key/value pair that returns a true value when evaluating the block's conditions. Returns an array of key/value pairs remaining in the hash.
