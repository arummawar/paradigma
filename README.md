# paradigma
project
>>> class Person:
	def __init__(self, name, age):
		self.name = name
		self.age = age		
>>> p1 = Person("arum", 20)
>>> print(p1.name)
arum
>>> print(p1.age)
20
>>> 

//diatas adalah program yang membuat class dengan nama person yang didalamnya terdapat objek nama dan umur p1 sebagai variabel lalu fungsi print
digunakan untuk menampilkan seperti syntax diatas print(p1.name) maka akan menampilkan nama dan juga dengan umur.
Untuk memahami makna kelas, kita harus memahami fungsi __init __ () bawaan.
Semua kelas memiliki fungsi yang disebut __init __ (), yang selalu dijalankan ketika kelas sedang dimulai.


>>> class Complex:
	def __init__(self, realpart, imagpart):
		self.r = realpart
		self.i = imagpart

>>> x = Complex(3.0, -4.5)
>>> x.r, x.i
(3.0, -4.5)



>>> class hewan:
	kind = 'cat'
	def __init__(self, name):
		self.name = name

		
>>> d = hewan('kelinci')
>>> e = hewan('jerapah')
>>> d.kind
'cat'
>>> e.kind
'cat'
>>> d.name
'kelinci'
>>> e.name
'jerapah'
>>> 

//diatas adalah program yang membuat class dengan nama hewan yang didalamnya terdapat objek kind d dan e sebagai variabel. lalu 
digunakan untuk menampilkan seperti syntax diatas d = hewan('kelinci') berarti variabel d berisi hewan yang bernama kelinci, jika di panggil
dengan perintah d.name maka akan muncul kelinci karena nama dari variabel d adalah kelinci.
Untuk memahami makna kelas, kita harus memahami fungsi __init __ () bawaan.
Semua kelas memiliki fungsi yang disebut __init __ (), yang selalu dijalankan ketika kelas sedang dimulai.
