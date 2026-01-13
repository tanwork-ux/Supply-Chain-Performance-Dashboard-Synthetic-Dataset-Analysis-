📝 Conclusion & Analysis Limitations

Meskipun dashboard ini berhasil memvisualisasikan metrik operasional secara interaktif, terdapat beberapa temuan penting terkait karakteristik data:

    Data Anomaly: Terdapat ketidakseimbangan skala yang ekstrem antara biaya pengiriman (Shipping Cost) dan jumlah pesanan (Order Quantity). Sebagai contoh, biaya pengiriman bisa mencapai $1M sementara jumlah pesanan sangat rendah (mendekati 0).

    Synthetic Dataset: Analisis ini dilakukan pada dataset sintetis yang dihasilkan secara terprogram. Oleh karena itu, data ini tidak merepresentasikan logika bisnis riil atau pola transaksi dunia nyata secara utuh.

    Root Cause Limitation: Dikarenakan sifat datanya yang sintetis dan memiliki sebaran yang terlalu merata (berdasarkan df.describe), terdapat batasan dalam menentukan akar penyebab (root cause) dari anomali yang ditemukan secara definitif.

Namun apabila dataset ini adalah data asli, dan saya menemukan kasus serupa, saya akan melakukan cross check data dan berusaha mendapatkan klarifikasi untuk memastikan akar masalahnya, apakah masalahnya terletak pada salah satu pipeline data atau bahkan ekosistem data itu sendiri, atau, memang faktanya di lapangan terjadi hal hal yang perlu di usut lebih dalam untuk bisa merumuskan solusinya

## Dashboard and Tooltip Preview
![Supply Chain Dashboard](visuals/Dashboard_Final.png)
![Supply Chain Dashboard](visuals/Jakarta.png)
![](visuals/Tooltip_HomeDecor.png)

### 📊 Key Visualizations
* **Main Dashboard**: [View Image](./visuals/dashboard_Final.png)
* **Advanced Tooltip Analysis**: [View Image](./visuals/tooltip.png)
* **Full Gallery**: [Browse Folder](./visuals/)
