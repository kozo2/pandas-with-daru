# pandas-with-daru
How can I do this pandas example with daru?

## "10 Minutes to pandas" with daru

### Object Creation
Creating a Vector by passing a list of values, letting daru create a default integer index:
```
[1] pry(main)> require 'daru'
=> true
[2] pry(main)> s = Daru::Vector.new([1,3,5,nil,6,8])
=> 
#<Daru::Vector:21505100 @name = nil @metadata = {} @size = 6 >
    nil
  0   1
  1   3
  2   5
  3 nil
  4   6
  5   8
```
