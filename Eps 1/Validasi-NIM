# CODINGAN IF BERSARANG
judul = "PROGRAM SEDERHANA IF BERSARANG"
nama_sekolah = "SMKN 2 BEKASI"
jurusan = '''
        [1] TEKNIK ELEKTRONIKA INDUSTRI
        [2] TEKNIK SEPEDA MOTOR
        [3] REKAYASA PERANGKAT LUNAK
        [4] TEKNIK KOMPUTER JARINGAN
        [5] AKUNTANSI
        [6] TEKNIK ENERGI BIOMASA\n\n'''

nama_jurusan = {
    1: "TEKNIK ELEKTRONIKA INDUSTRI",
    2: "TEKNIK SEPEDA MOTOR",
    3: "REKAYASA PERANGKAT LUNAK",
    4: "TEKNIK KOMPUTER JARINGAN",
    5: "AKUNTANSI",
    6: "TEKNIK ENERGI BIOMASA"
}

nilai_minimal = {
    1: 24,
    2: 19,
    3: 20,
    4: 21,
    5: 24,
    6: 18
}

ucapan = "SELAMAT DATANG! CALON SISWA/I SMKN 2 BEKASI"

print("===============================")
print(judul)
print("===============================\n")
print(ucapan)
print("========================DAFTAR JURUSAN=========================")
print(jurusan)

while True:
    try:
        pilihan = int(input("PILIH JURUSAN YANG KAMU MINATI : "))
        if pilihan < 1 or pilihan > 6:
            print("ANGKA YANG KAMU PILIH TIDAK TERDAFTAR")
        else:
            break
    except ValueError:
        print("PILIHAN KAMU TIDAK ADA DI DAFTAR")

nama = input("SILAHKAN ISI NAMA LENGKAP KAMU  : ")
nilai_name = float(input("SILAHKAN MASUKAN NILAI NAME KAMU : "))

if nilai_name >= nilai_minimal[pilihan]:
    print(f"SELAMAT! {nama} KAMU DAPAT MENDAFTAR DI JURUSAN {nama_jurusan[pilihan]}")
else:
    print(f"MOHON MAAF! {nama} KAMU BELUM DAPAT MENDAFTAR DI JURUSAN {nama_jurusan[pilihan]}")
    print("SILAHKAN MEMILIH JURUSAN LAIN")
