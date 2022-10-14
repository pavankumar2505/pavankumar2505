# using np.sort()
import numpy as np
arr3 = np.array([[[2,1],[4,3]],[[6,5],[8,7]],[[10,9],[12,11]]])
arr3
print(np.sort(arr3))


# using np.where()
arr3 = np.array([[[1,2],[3,4]],[[5,6],[7,8]],[[9,10],[11,12]]])
x = np.where(arr == [5])
print(x) 
