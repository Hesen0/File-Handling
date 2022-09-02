MyList = ['a ','b ','c ','d ','e ']
MyFile1 = open("F:\Hasan\TestFile1.txt","x")
MyFile2 = open("F:\Hasan\TestFile2.txt","x")

MyFile1 = open("F:\Hasan\TestFile1.txt","a")
MyFile2 = open("F:\Hasan\TestFile2.txt","a")
for i in MyList:
  MyFile1.write(i)
  MyFile1.write('\n')
MyFile1 = open("F:\Hasan\TestFile1.txt","r")

for i in MyFile1.readlines():
    MyFile2.write(i)

