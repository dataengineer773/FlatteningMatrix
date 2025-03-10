We need to transform a matrix into a one-dimensional array, The solution is Use flatten, flatten is a simple method to transform a matrix into a one-dimensional array. Alternatively, we can use reshape to create a row vector
One more common method to flatten arrays is the ravel method. Unlike flatten which returns a copy One more common method to flatten arrays is the ravel method. Unlike flatten which returns a copy lets us flatten lists of arrays,
which we can’t do with the flatten method. This operation is useful for flattening very large arrays and speeding up code.
