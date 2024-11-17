# Implementasi Himpunan Matematika Diskrit
Projek ini bertujuan untuk mengimplementasikan konsep-konsep dasar himpunan dalam bahasa pemrograman python.

## Magic Methods
- `__len__(self)` : Mengembalikan jumlah elemen dalam himpunan (ukuran himpunan).
- `__contains__(self, item)` : Mengembalikan True jika suatu elemen ada dalam himpunan, dan False jika tidak ada.
- `__eq__(self, other)` : Mengecek apakah dua himpunan sama. Return Boolean
- `__le__(self, other)` : Mengecek apakah suatu himpunan merupakan subset dari himpunan lain. Return Boolean
- `__lt__(self, other)` : Mengecek apakah suatu himpunan merupakan proper subset dari himpunan lain. Return Boolean
- `__ge__(self, other)` : Mengecek apakah suatu himpunan merupakan superset dari himpunan lain. Return Boolean
- `__floordiv__(self, other)` : Mengecek apakah dua himpunan ekuivalen (memiliki elemen yang sama, meskipun urutannya berbeda). Return Boolean

## Other Methods
- **Irisan (Intersect)** : Menggunakan operator `/` untuk menghitung irisan antara dua himpunan.
- **Gabungan (Union)** : Menggunakan operator `+` untuk menghitung gabungan antara dua himpunan.
- **Selisih (Difference)** : Menggunakan operator `-` untuk menghitung selisih antara dua himpunan.
- **Komplemen (Complement)** : Nama method `complement()`  untuk menghitung komplemen dari suatu himpunan dengan input himpunan Semesta.
- **Selisih Simetris (Symmetric Difference)** : Menggunakan operator `*` untuk menghitung selisih simetris antara dua himpunan.
- **Cartesian product** : Menggunakan operator `**` untuk menghitung hasil cartesian product dari dua himpunan
- **Himpunan Kuasa (Power Set)** : Menggunakan `abs()` untuk menghitung himpunan kuasa (semua subset dari himpunan).
- **Anggota Himpunan Kuasa** : Nama method  `PowerSet()` Menampilkan list himpunan kuasa yang mungkin dibuat dari suatu himpunan.

## Library "himpunan-team7"
Untuk menggunakan package `himpunan-team7`, lakukan instalasi dengan menggunakan command berikut:
```cmd
pip install himpunan-team7
```

Lalu lakukan import package ke dalam file:
```python
from himpunan_team7 import *
```

Link PyPI: https://pypi.org/project/himpunan-team7/

## Credit
by **Team 7** IMT UCM 2023
- Aaron Jevon Benedict Kongdoh | 0806022310014
- Derick Norlan | 0806022310005
- Excel Marcello Parinussa | 0806022310029
