# Втора лабораториска вежба по Софтверско инженерство
## Кристијан Лазаровски 153071
## Група на код:
Ја добив групата на код 4

## Control Flow Graph
![Kristijan Lazarovski 153071 Control Flow Graph](https://user-images.githubusercontent.com/52075405/84544045-cbd9b500-acfc-11ea-92b6-bc5abaf1a4ed.jpg)

## Цикломатска комплексност
Цикломатската комплексност на овој код е 13, истата ја добив преку формулата e-n+2P, каде што P е бројот на conected components,e е бројот на edges, а n е бројот на nodes. 

## Тест случаи според критериумот Every Branch
1. Kristijan12.
**A**,
**B**,
**C**,
**D**,
E,
**F**,
**G**,
**H**,
**I**,
**J**,
**K**,
**L**,
**M**,
**N**,
**O**,
P,

**A-B**,
**B-C**,
**C-D**,
D-E,
E-F,
**D-F**,
**F-G**,
**G-H**,
**H-I**,
G-I,
**I-J**,
**J-K**,
I-K,
**K-L**,
**L-M**,
K-M,
M-F,
**M-N**,
**N-O**,
**O-P**,
N-P,

2. tralala12
**A**,
**B**,
**C**,
**D**,
E,
**F**,
**G**,
**H**,
I,
J,
K,
L,
**M**,
N,
O,
**P**,


**A-B**,
**B-C**,
**C-D**,
D-E,
E-F,
**D-F**,
**F-G**,
**G-H**,
H-I,
G-I,
I-J,
J-K,
I-K,
K-L,
L-M,
K-M,
M-F,
M-N,
N-O,
O-P,
N-P,

3. tralalalalal
**A**,
**B**,
**C**,
**D**,
**E**,
**F**,
G,
H,
I,
J,
K,
L,
M,
N,
O,
**P**,


**A-B**,
**B-C**,
**C-D**,
**D-E**,
**E-F**,
D-F,
F-G,
G-H,
H-I,
G-I,
I-J,
J-K,
I-K,
K-L,
L-M,
K-M,
M-F,
M-N,
N-O,
O-P,
N-P


## Тест случаи според критериумот Multiple Condition


## Објаснување на напишаните unit tests
Најпрво земаме еден INPUT како за тест,во мојов случај јас го зедов како за пасворд „ Kristijan12.“.
Па низ секоја линија код според поставените услови гледав дали ке помине кодот и со тоа и ги болдирав буквите ( сите букви ми се поставени после линиите на кодот) .
