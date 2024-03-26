# Pada Tugas ini saya akan membersihkan data ('marketing_data.csv')
- Prinsip yang di gunakan adalah Basic OOP, Inheritance, Polymorphism

# Pada Soal No 1 
saya membuat sebuah class yaitu MarketingDataETL yang memiliki 3 metode:
1. Extraxt
2. transform
   - pada transform saya mengubah format tanggal, dan membershikan nilai NULL
3. store
   - membuat data store dengan data yang sudah di tranform kemudian dimasukan kedalam ('transformed_marketing_data.csv')
     jadi didalam file ('transformed_marketing_data.csv') berisi data yang sudah di ubah dan di bersihkan.

# Pada Soal No 2
- Saya membuat class TargetedMarketing ETL yang mewarisi dari Class MarketingDataETL
- kemudian saya menambahkan Metode Segment_customers dengan kriteria: Total_spending
- Total_spending = Mengelompokkan pelanggan berdasarkan jumlah harga produk yang dibeli
- kemudian hasil tersebut di simpan kedalam ('segmented_marketing_data.csv')
