# Proses Gabung Anomali Sakernas

## Persiapan
- Lakukan instalasi python <link>https://www.python.org/</link> dan jupyter notebook melalui CMD <code>pip install notebook</code>
- Lakukan instalasi package yang diperlukan sbb
- <code>pip install pandas</code>
- <code>pip install zipfile</code>
- <code>pip install openpyxl</code>
- Lakukan download versi zip pada anomali yang telah dirun
- Jalankan Notebook dengan cara <code>jupyter notebook</code>

## Proses
- Lakukan Koordinasi dengan IPDS Provinsi untuk mendapatkan file [pada folder input ipds]
- Lakukan proses running dengan notebook untuk file set_petugas.ipynb untuk menghasilkan petugas.xlsx
- Jika ada perubahan kode anomali dari tim Pusat, lakukan perbaikan pada file Daftar Anomali & Metadata Sakernas Februari 2026.xlsx
- Dengan notebook buka file gabung.ipynb kemudian atur nama file berdasarkan input dari sosial, beserta tanggal anomali
- Jalankan file gabung.ipynb File anomali gabungan akan tergenerate secara otomatis di folder output/tgl_anomali
