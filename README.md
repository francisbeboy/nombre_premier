# nombre_premier
# Cet exercice permet de donner la liste des nombre premier plus petit que 100 avec la boucle for et while
# creer deux programme avec la boucle for et la boucle while
# qui affiche les 100 premiers nombres entiers premiers.
"""
for num in range(0, 101):
    for i in range(2, num):
        if num % i == 0:
            print(num)
             """
```python
#avec la boucle for 
for i in range(2,101):
     trouver=0
     for j in range(2,i):
          if i%j==0:
               trouver=1
     if trouver==0:
          print(f" {i}  " )



```
# avec la boucle while
```python

n= 101
trouver =0
i= 2
j=0
while i<n:
     j+=1
     if i%j==0:
          trouver=1
if trouver==0:
     print(i)


```
