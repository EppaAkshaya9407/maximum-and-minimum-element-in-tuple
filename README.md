# maximum-and-minimum-element-in-tuple
tuple=(17,23,8,9)
n=len(tuple)
max=tuple[0]
min=tuple[0]
for i in range(n):
    if i<min:
        min=tuple[i]
    if i>max:
        max=tuple[i]
print("maximum eleement",max)
print("minimum eleement",min)
