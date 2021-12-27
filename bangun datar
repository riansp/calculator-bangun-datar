import sys

def square ():
    print('==Menghitung_Persegi==')
    sisi = float(input("Panjang Sisinya Berapa: "))
    print('='*20)
    luas = sisi*sisi
    keliling = 4 * sisi
    print('===Hasilnya Adalah===')
    print('Luas Persegi:', luas,'cm')
    print('Luas Keliling Persegi:', keliling,'cm')
    back()

def rectangle ():
    print('==Menghitung_Persegi_Panjang==')
    panjang = float(input("Panjangnya Berapa: "))
    lebar = float(input("Lebarnya Berapa: "))
    print('='*20)
    luas = panjang * lebar
    keliling = 2 * (panjang+lebar)
    print('===Hasilnya Adalah===')
    print('Luas Persegi Panjang:', luas,'cm')
    print('Luas Keliling Persegi Panjang:', keliling,'cm')
    back()
    
def triangle ():
    print('==Menghitung_Segitiga==')
    Alas = float(input("Alasnya Berapa: "))
    Tinggi = float(input("Tingginya Berapa: "))
    print('='*20)
    luas = 0.5 * Alas * Tinggi 
    keliling = 3 * Alas
    print('===Hasilnya Adalah===')
    print('Luas Segetiga: ', luas,'cm')
    print ('Keliling Segitiga: ', keliling,'cm')
    back()
    
def circle ():
    print('==Menghitung_Lingkaran==')
    Diamter = float(input('Diameternya Berapa: '))
    print('='*20)
    r = Diamter / 2
    luas = 3.14 * r **2 
    keliling = 22/7 * Diamter
    print('===Hasilnya Adalah===')
    print('Luas Segetiga: ',luas, 'cm')
    print ('Keliling Segitiga: ', keliling,'cm')
    back()

def parallelogram ():
    print('==Menghitung_Jajar_Genjang==')
    #Sisi Alas = a
    #Sisi Miring = b
    #Tinggi = t
    a = float(input("Sisi Alasnya Berapa: "))
    b = float(input("Sisi Miringnya Berapa: "))
    t = float(input("Tingginya Berapa: "))
    print('='*20)
    luas = a * t
    keliling = 2 * (a+b)
    print('===Hasilnya Adalah===')
    print('Luas Jajar Genjang: ', luas,'cm')
    print ('Keliling Jajar Genjang: ', keliling,'cm')
    back()
    
def trapesium ():
    print('==Menghitung_Trapesium==')
    a = float(input("Sisi A Berapa: "))
    b = float(input("Sisi B Berapa: "))
    c = float(input("Sisi C Berapa: "))
    d = float(input("Sisi D Berapa: "))
    t = float(input("Tingginya Berapa: "))
    print('='*20)
    luas = (t * (a+b))/2
    keliling = a + b + c + d
    print('===Hasilnya Adalah===')
    print('Luas Trapesium: ', luas,'cm')
    print ('Keliling Trapesium: ', keliling,'cm')
    back()
    
def menu():
    print("Pilih Program Menghitung :")
    print("1. Menghitung Persegi")
    print("2. Menghitung Persegi Panjang")
    print("3. Menghitung Segitiga")
    print("4. Menghitung Lingkaran")
    print("5. Menghitung Jajar Genjang")
    print("6. Menghitung Trapesium")
    print("7. Selesai")

    pilih = int(input("Masukkan pilihan [1-7] : "))

    if pilih == 1:
        square()
    elif pilih == 2:
        rectangle()
    elif pilih == 3:
        triangle()
    elif pilih == 4:
        circle()
    elif pilih == 5:
        parallelogram()
    elif pilih == 6:
        trapesium()
    elif pilih == 7:
        print("Semoga Bermanfaat")
        sys.exit()
    else:
        print("Pilihan yang anda masukkan salah!")
        menu()

def back():
    back = input(" Ingin mengulang aplikasi lagi? [y/t] : ")
    if back == "y":
        menu()
    elif back == "t":
        sys.exit()
    else:
        print("Pilihan yang anda masukan salah!")

menu()
