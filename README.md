# codlab4

•	HashMap<String,Integer> inventori = new HashMap<>() berfungsi untuk membuat variabel inventori bertipe hashmap untuk menyimpan inventori toko yang memiliki key bertipe String dan value bertipe Integer. 
•	Inventori.put(“Pensil”, 50) yaitu menambah barang ke dalam variabel inventori yang bertipe hashmap yang mempunyai key Pensil(string) dan value 50(integer). 
•	Inventori.get(“Pensil”) memiliki arti mengambil data dari hashmap inventori yang memiliki key “Pensil” 
•	Inventori.put(“Pensil”, inventori.get(“Pensil”) + 20) yaitu merubah value dari hashmap inventori yang memiliki key “Pensil” menjadi value dari key “Pensil” ditambahkan dengan 20, sekarang value dari key “Pensil” adalah 50 + 20 yaitu 70 
•	Inventori.remove(“Penghapus”) artinya adalah menghapus data dari hashmap inventori yang mempunyai key “Penghapus” 
•	cariBarang(inventori, barang) adalah melakukan pemanggilan function cariBarang yang diisi dengan hashmap inventori dan barang dimana barang adalah inputan dari user 
•	If(Inventori.containsKey(barang)) yaitu melakukan pengecekan apakah di dalam hashmap inventori memiliki key dari variabel barang yang dimana barang didapatkan dari parameter function cariBarang 
