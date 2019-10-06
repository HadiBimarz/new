# new
#!/usr/local/bin/python3.4

a,b =2,3


if a < b:
 print('a ({}) is less than b ({})'.format(a, b))
else:
 print('a ({}) is not less than b ({})'.format(a, b))

print("a less than b" if a < b else "b more than a" )
