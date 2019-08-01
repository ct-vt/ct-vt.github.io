# Knowledge Components for Collection Based Iteration in Python

* KC001: Integers and floats are different numeric types
* KC002: The iteration property takes on the type of the elements of the list
* KC003: The iteration property is NOT the list
* KC004: Numeric types are different from strings
* KC005: Numeric types are different from booleans
* KC006: The iteration property takes on each value of the list
* KC007: The iteration property is a single item
* KC008: The list is multiple items
* KC009: The iteration property and the list should be different
* KC010: Initializations for sums should be 0
* KC011: Initializations for accumulators should be 0
* KC012: The sum and the list are two different items
* KC013: The accumulator and the list are two different items
* KC014: A property shouldn't be used before it's initialized
* KC015: A property shouldn't be initialized to itself
* KC016: An initialization for sums isn't an update
* KC017: An initialization for accumulators isn't an update
* KC018: Update for sum is accumulator = accumulator + iteration property
  * KC018-(1-3) locations of accumulator (x2) and iteration property
  * KC018-(4-6) presence of accumulator and iteration property and no presence of list
* KC019: Update for accumulation is accumulator = accumulator + X
  * KC019-(1-3) locations of accumulator (x2) and accumulator_modifier
  * KC019-(4-6) presence of accumulatorm accumulator_modifier and no presence of list
* KC020: numbers and lists are two different things numbers can't be added to lists might be one as well
* KC022: The list is not used in accumulation
* KC023: The list is not used as an accumulator
* KC024: The iteration property is not an accumulator
* KC025: for each loop is for iter_prop in list
* KC026: Update for counting is counter = counter + 1
  * KC026-(1-3) locations of counter (x2) and 1
  * KC026-(4-6) presence of counter and 1 and no presence of list
* KC027: for filtering, if statement goes inside loop
  * KC027-(1-2) location and presence of if statement
* KC028: list is not used for filtering
* KC029: filtering should use the iteration property
* KC030: The syntax of an empty list
* KC031: A new list should be different from the old list
* KC032: Building a new list is different from accumulating
* KC034: filtering should be done on old list
* KC035: the key word next does not exist
* KC036: List filtering is not an accumulation pattern
* KC037: Need to call append
* KC038: modifications should be done on new list
* KC038: Modifications should be done on new list
* KC039: Transformations happen on old values
* KC040: Transformed values are appended to the new list (could probably make generalizations to list building patterns)
* KC041: Meaningful list name
* KC042: Menngiful accumulator name
* KC043: meaningful iteration property name
* KC044: Knows to create an iteration property
* KC045: Knows to output response
* KC046: Knows to create an accumulator
* KC047: Knows to create a list property
* KC048: Differentiates between count and sum when summing a list of countable items
* KC049: Initializations for counts should be 0
* KC050: Initialize list from data block
* KC051: The count and the list are two different items
* KC052: An initialization for count isn't an update
* KC053: string types and lists are two different things
