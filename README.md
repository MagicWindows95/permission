**How to set user IP**

Tulis setiap user satu baris diawali ###, lalu: NAMA TANGGAL_AKTIF IP [ON [KODE]] [VIP].

**Sintaks**

**### <NAMA> <YYYY-MM-DD> <IPv4> [ON [KODE]] [VIP]**

**Contoh:**

**============== OWNER ==============**

*### TEST 9999-01-01 149.129.216.29 ON VIP*

**============== USER RESELLER ==============**

*### TEST 2025-07-11 18.23.121.21*

**============== ADMIN RESELLER ==============**

*### TEST 2025-12-11 128.199.212.101 ON 99 VIP*

**Keterangan Cepat:**

• YYYY-MM-DD = tanggal berlaku sampai (mis. 2025-07-11).

• 9999-01-01 = permanen (khusus owner/akun khusus).

• ON [KODE] = jadikan reseller autoscript (opsional KODE,Penanda atau jumlah admin yang aktif mis. 1-99).

• VIP = aktifkan reseller IP (khusus admin).

> Tips: Gunakan huruf kapital untuk NAMA, pisahkan field dengan spasi, dan pastikan IP IPv4 valid.
