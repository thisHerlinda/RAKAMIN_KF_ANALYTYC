# Rakamin_KF_Analytycs

Repository ini berisi analisis data transaksi Kimia Farma menggunakan Google BigQuery.

## Query: Perhitungan Nett Sales dan Nett Profit

File: [nett_profit_query.sql](https://github.com/username/Rakamin_KF_Analytycs/blob/main/nett_profit_query.sql)

### Deskripsi:
Query ini menghitung:
- Nett Sales (setelah diskon)
- Gross Profit Percentage berdasarkan rentang harga
- Nett Profit (nett sales * gross profit %)
- Format hasil ke dalam format mata uang Rupiah

### Struktur Data:
- *kf_final_transaction*: Data transaksi
- *kf_product*: Data produk
- *kf_kantor_cabang*: Data cabang Kimia Farma

### Contoh Output Kolom:
- transaction_id
- branch_name
- actual_price
- discount_percentage
- nett_sales
- nett_profit

### Format Rupiah:
Output menggunakan format Rp. 25.000,00 dengan koma desimal dan titik ribuan.

---

### Cara Menjalankan:
Jalankan query di BigQuery SQL editor setelah memilih dataset yang sesuai.
