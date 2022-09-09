# Array-Methods
List of array methods on JavaScript

1. The Filter Array Method: this method is used to filter or drain elements from an Array. This method returns random elements from the parent array as long as they fulfil the filter condition or criteria.
Syntax: arrayName.filter(arguement)
    e.g.
    let num = [2, 4, 6, 8, 1, 3, 5, 7, 9]
    let filteredResult = num.filter(x => x > 4)

    The "filteredResult" method when called will return = [6, 8, 5, 7, 9]
    
2. The Slice Array Method: this method cuts an array and gets a new part of the array. This method returns a part of an array but it is just a continous sub array.
Syntax: arrayName.slice(indexFrom, indexTo)
Note: The indexFrom is inclusive in the return array, while the indexTo is not inclusive
    e.g.
    let num = [2, 4, 6, 8, 1, 3, 5, 7, 9]
    let slicedResult = num.slice(2, 7)
    
    The "slicedResult" method when called will return = [6, 8, 1, 3, 5]

3. The Splice Array Method: this method can add, remove and return deleted elements in an array. This method returns a new array without the deleted elements.
Syntax: arrayName.splice(startIndex, deleteCount, itemsToBeInserted)
    e.g.
    let arr = ['s', 'u', 'm']
    arr.splice(2, 1, 'mit', 'sau')
    When we can the "arr" array, it returns an new array = ['s', 'u', 'mit', 'sau']

4. The Reduce Array Method: this method lessens an array, such that on each array element a single value out is gotten.
Syntax: arrayName.reduce(arguement)
    e.g.
    let num = [1, 5, 7, 55, 3, 32, 123]
    num.reduce((prv, cur) => prv + cur)
    This returns the value 226, which is the total of the array elements

5. The Map Array Method: this method is used to create a one-on-one correspondence to each element of an array such that something happens to every element of the array being mapped.
Syntax: arrayName.map(arguement)
    e.g.
    const num = [1, 2, 3, 4]
    const doubled = num.map(x => x*2)
    When the "double" constant is called, it returns the array = [2, 4, 6, 8]. What happens here is that each element of the array is multiplied by 2 to give a new value for each element.

6. The Push Array Method: this method is used for adding an element to the end of an array.
    e.g.
    let num = [1, 2, 3]
    num.push(4)
    With this, when the array "num" is called, it returns a new array = [1, 2, 3, 4]

7. The Pop Array Method: this method is used for removing an element from the end of an array.
    e.g.
    let num = [1, 2, 3, 4]
    num.pop()
    With this, when the array "num" is called, it returns a new array = [1, 2, 3]

8. The Shift Array Method: this method is used for removing and element from the beginning of an array.
    e.g.
    let num = [1, 2, 3]
    num.shift()
    With this, when the array "num" is called, it returns a new array = [2, 3]

9. The Unshift Array Method: this method is used for adding an element to the beginning of an array.
    e.g.
    let num = [2, 3]
    num.unshift(0)
    With this, when the array "num" is called, it returns a new array = [0, 2, 3]

10. The Join Array Method: this method converts an array to a string, but with an arguement that determines what stands between each element.
    e.g.
    let num = [0, 2, 3]
    num.join("-")
    With this, when the array "num" is now called, it returns a string = "0-2-3"