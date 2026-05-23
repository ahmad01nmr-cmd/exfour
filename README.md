# 1. VARIABEL & TIPE DATA
nama_film = "Petualangan Coding"  # Tipe data: String (teks)
harga_tiket = 35000              # Tipe data: Integer (angka)
kuota_kursi = 3                  # Tipe data: Integer


# 2. PERCABANGAN (IF-ELSE)
# Mengecek apakah masih ada kursi yang tersedia
if kuota_kursi > 0:
    print("=== Selamat Datang di Bioskop ===")
    print("Film yang diputar hari ini:", nama_film)
    print("Harga per tiket: Rp", harga_tiket)
    print("---------------------------------")
    
    # 3. PERULANGAN (LOOP)
    # Anggap ada 3 orang di antrean yang membeli tiket satu per satu
    for antrean ke range(1, kuota_kursi + 1):
        print("Mencetak tiket untuk penonton ke-", antrean)
        
    print("---------------------------------")
    print("Semua tiket untuk sesi ini sudah terjual habis!")

else:
    # Bagian ini jalan kalau kuota_kursi sama dengan 0 atau kurang
    print("Maaf, tiket untuk film", nama_film, "sudah habis.")
