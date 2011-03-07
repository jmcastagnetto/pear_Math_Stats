Math_Stats
==========

Package to calculate statistical parameters of numerical arrays
of data. The data can be in a simple numerical array, or in a 
cummulative numerical array. 

A cummulative array, has the value as the index and the number 
of repeats as the value for the array item, e.g. 
    $data = array(
                3=>4, 
                2.3=>5, 
                1.25=>6, 
                0.5=>3
                );

Nulls can be rejected, ignored or handled as zero values.

This is old code I wrote for [PEAR](http://pear.php.net). 
Originally it was tracked in CVS, then it was moved to SVN, 
and now I am importing it to git :-)

-- Jesus M. Castagnetto
