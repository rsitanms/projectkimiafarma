[Kimia Farma Big Data Analytics Project.md](https://github.com/user-attachments/files/28378282/Kimia.Farma.Big.Data.Analytics.Project.md)
# Kimia Farma Big Data Analytics Project Based Internship Program

## Project Overview
Repository ini digunakan sebagai bukti pendukung dalam pengerjaan Final Task Perfomance Analysis pada Program Project Based Internship kolaborasi Rakamin Academy dan Kimia Farma Big Data Analytics

## Objective
Membuat tabel analisa, kolom-kolom mandatory pada tabel:
- transaction_id
- date
- branch_id
- branch_name
- kota
- provinsi
- rating_cabang
- customer_name
- product_id
- product_name
- actual_price
- discount_percentage
- persentase_gross_laba
- nett_sales
- nett_profit
- rating_transaksi

## Dataset
Dataset yang digunakan:
- [kf_final_transaction] (https://drive.google.com/file/d/1iDOBdKZ4-kkLhpklQWWrsFvACtI7MCz3/view)
- [kf_product] (https://drive.google.com/file/d/1739wO7BwtVStHCA4Dcj9xGhlc_blBNbT/view)
- [kf_inventory] (https://drive.google.com/file/d/1ihtG2t0V1AO0IAGkGwQaqtba6AxDEKDI/view)
- [kf_kantor_cabang] (https://drive.google.com/file/d/1vzaasqIeXqqe_jI99dNLaa8nxnoe9OWW/view)

## Hints Data Dictionary
### kf_final_transaction
| Column | Description |
|---|---|
| transaction_id | kode id transaksi |
| product_id | kode produk obat |
| branch_id | kode id cabang Kimia Farma |
| customer_name | nama customer yang melakukan transaksi |
| date | tanggal transaksi dilakukan |
| price | harga obat |
| discount_percentage | persentase diskon yang diberikan pada obat |
| rating | penilaian konsumen terhadap transaksi yang dilakukan|

### kf_product
| Column | Description |
|---|---|
| product_id | kode produk obat |
| product_name | nama produk obat |
| product_category | kategori produk obat |
| price | harga obat |

### kf_inventory
| Column | Description |
|---|---|
| inventory_ID | kode inventory produk obat |
| branch_id | kode id cabang Kimia Farma |
| product_id | kode id produk obat |
| product_name | nama produk obat |
| opname_stock | jumlah stok produk obat |

### kf_kantor_cabang
| Column | Description |
|---|---|
| branch_id | kode id cabang Kimia Farma |
| branch_category | kategori cabang Kimia Farma |
| branch_name | nama kantor cabang Kimia Farma |
| kota | kota cabang Kimia Farma |
| provinsi | provinsi cabang Kimia Farma |
| rating | penilaian konsumen terhadap cabang Kimia Farma |

## Steps by Steps
- Login ke Google Cloud Platform
- Buka Console GCP
- Navigasi ke BigQuery
- Buat Project "rakamin-kf-analytics-496202" di BigQuery
- Buat Dataset "kimia_farma" di dalam Project "rakamin-kf-analytics-496202"
- Importing Dataset ke BigQuery
- Menjalankan SQL Query Analisa pad Project
- Melakukan CREATE TABLE
- Melakukan SELECT AS 
- Melakukan CASE WHEN
- Melakukan LEFT JOIN
- RUN (Finish Query)
- Hubungkan Master Tabel ke Google Data Studio
- Visualisasi dan Analisis Data

## Tools
Tools yang digunakan:
- [Google Cloud Platform (BigQuery)] (https://cloud.google.com)
- [Github] (https://github.com)
- [Google Data Studio] (https://datastudio.google.com)

## Query
File SQL:
- Syntax_BigQuery_KF_RositaNurmalasari.sql

## Output
Tabel Analisa:
- kf_analysis

## Author
Rosita Nurmalasari
