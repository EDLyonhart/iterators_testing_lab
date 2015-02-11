##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select:
	Returns a new array of the elements which met the criteria passed in, like 'even?' or '< 10' (returns a true value).

####reject:
	Returns a new array as above but for criteria which evaluates false.

####map:
	Invokes a block of code on each element of an enumerable. One Time each.
	
####detect:
	Passes each element of an array into a block. Returns the first element which evaluates to true (which is not false?).

####inject:
	Passes each element of an enumerable through a block and 'reduces' them all together to a single value.

####partition:
	Returns an array of two new arrays. One with all elements which evaluate true when passed through a block, one which evaluate false.

####sort:
	Returns a new array based on the comparison between the first two elements, compared using '<=>'.

####one?:
	Returns true if exactly one element passed into a block returns true when passed through a block.

####none?:
	Returns true if none of the elements passed into a block evaluate to true. Returns false if any of the elements evaluate true.

####all:
	Returns true if all of the elements passed into a block evaluate to true.

####empty?:
	Returns true if array is empty (has length of 0)

####eql?:
	Returns true if two arrays are exactly the same, length and content.

####include?:
	Returns true if array contains given char or string.

####nil?:
	Returns true only for 'nil' evaluation

###Hash methods:

####key?:
	Returns true is passed value is a key

####keys:
	Returns a new array populated with the keys.

####delete:
	Deletes a key/value pair from a hash matching the key fed in. Returns the value.

####delete_if:
	Deletes all key/value pairs which evaluate to true when passed through a block.
