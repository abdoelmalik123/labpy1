# labpy1
## latihan1.py : menentukan nilai terbesar dari 3 bilangan yang di inputkan
1. menginputkan nilai ke variable a,b,c 

a = int(input ("masukan nilai  a : "))
b = int(input ("masukan nilai  b : "))
c = int(input ("masukan nilai  c : "))

2. membandingka nilai terbesar antara variable a dan b
  - jika nilai variable a adalah nilai terbesarnya, maka variable a dibandingkan lagi dengan variable c
    - jika nilai variable a lebih besar dari c, maka yang tercetak adalah nilai a
    - jika nilai variable c lebih besar dari a, maka yang tercetak adalah nilai c
3. jika nilai variable b lebih besar dari variable a, maka nilai b akan dibandingkan lagi dengan variable c
  - jika variable b lebih besar dari c, maka yang tercetak adalah nilai b
  - jika variable c lebih besar dari b, maka yang tercetak adalah nilai c
4. jika nilai c lebih besar dari bariable a dan b, maka yang tercetak adalah nilai c
5. selesai

berikut kode lengkapnta : 
a = int(input ("masukan nilai  a : "))
b = int(input ("masukan nilai  b : "))
c = int(input ("masukan nilai  c : "))

if a > b :
    if a > c :
        print ("nilai terbesarnya adalah", a)
    else :
        print("nilai terbesarnya adalah", c)
elif b > c :
    print("nilai terbesarnya adalah", b)
else :
    print("nilai terbesarnya adalah", c)
    
berikut flowchartnya :
![latihan1](https://user-images.githubusercontent.com/44388133/52486173-0608e300-2bed-11e9-8488-7300bbc2806b.jpg)

berikut hasil screenshotnya :
![latihan1](https://user-images.githubusercontent.com/44388133/52486206-191bb300-2bed-11e9-95dd-75366463ab26.png)
