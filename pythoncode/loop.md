while
格式 (repeating action until condition is met)
  while condition:
    expression

for
格式(for each car in seq, execute expression)
  for var in seq:
    expression
enumerate
  for index, height in numerate(fam):
    print("index"+str(index)+":"+str(height))
  output: index 0:1.73......

loop in dictionary
  for key, value in world.items():
    print(key+"--"+str(value))
 
loop in 2D numpy arrays
  for val in means:
    print(val)   (結果是每一個array)
   for val in np.nditer(means):
    print(val)   (結果是每一個array中的每個元素)