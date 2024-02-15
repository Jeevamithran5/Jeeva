input:

E = {0, 1, 2, 3, 4, 5, 6, 8}N = {0, 1, 3, 5, 6, 8}union_result = E.union(N)intersection_result = E.intersection(N)difference_result = E.difference(N)symmetric_difference_result = E.symmetric_difference(N)print("Union of E and N is", union_result)print("Intersection of E and N is", intersection_result)print("Difference of E and N is", difference_result)print("Symmetric difference of E and N is", symmetric_difference_result)

output:

 Union of E and N is {0, 1, 2, 3, 4, 5, 6, 8}
Intersection of E and N is {0, 1, 3, 5, 6, 8}
Difference of E and N is {2, 4}
Symmetric difference of E and N is {2, 4}
