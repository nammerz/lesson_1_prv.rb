lesson_1_prv.rb
===============

#Lesson 1 Pass by reference vs value

array = ['nam', 'linda', 'bunny', 'panda']
p array[0]
p array

array_2 = ['go', 'go', 'tea', 'tea', 'leaf', 'leaf', 'academy', 'academy']
p array_2
array_2.uniq!
p array_2

# on the first array, I called (0), which gives me nam and then called
# the array, which did not mutate the caller permanently.

# on the second array, I called the array first, which gives me the 
# doubled words but once I put the uniq! (the "!" permanently changes the array)
# and called the caller, it made a new array without the dupication.
