# Collections: Counter, named tuple, OrderDict, defaultdict, deque
# Making the counter 
from collections import Counter
a = "aaabbbccc"
my_counter = Counter(a)
print(my_counter)
print(my_counter.most_common(1))
print(list(my_counter.elements()))
