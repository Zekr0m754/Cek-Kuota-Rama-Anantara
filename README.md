[# Program Mengecek Kuota Rama.py](https://github.com/user-attachments/files/21807009/Program.Mengecek.Kuota.Rama.py)# Cek-Kuota-Rama-Anantara
ribet sekali ce
[Uploading # Program Mengec# Program Mengecek Kuota Rama

# Input sisa kuota awal (MB)
sisa_kuota = int(input("Masukkan sisa kuota internet (MB): "))

# Input pemakaian hari ini
pemakaian = int(input("Masukkan pemakaian kuota hari ini (MB): "))

# Hitung sisa kuota setelah dipakai
sisa_kuota = sisa_kuota - pemakaian

# Cek apakah cukup untuk besok
if sisa_kuota >= 500:
    print("Masih cukup untuk besok")
else:
    print("Tidak cukup, harus libur internetan dulu nih!")

# Tampilkan sisa kuota
print("Sisa kuota sekarang:", sisa_kuota, "MB")ek Kuota Rama.py…]()
