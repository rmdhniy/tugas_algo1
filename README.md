#penyeleksian anggota tni tinggi badan dan umur
nama = str(input('Masukan Nama : '))
umur = int(input('Masukan Umur : '))
tinggiBadan = int(input('Tinggi Badan : '))
asalDaerah = str(input('Asal Daerah : '))

if umur <= 25 and tinggiBadan >= 170:
    print('SELAMAT ANDA LOLOS SELEKSI TNI!')
else:
    print('ANDA TIDAK LOLOS SELEKSI!')
