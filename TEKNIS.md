# Teknis Cangkol

## Definisi
* entitas yang termasuk entitas adalah pemain dan meja.
* device adalah peralatan elektronik yang digunakan, dapat berupa PC, Laptop, Smartphone, Tablet, dll.

## Perlengkapan
1. Setiap entitas akan diwakili oleh sebuah device.
2. Sebuah permainan minimal melibatkan 2 buah pemain dan 1 buah meja.
3. Kartu remi baik model (representasi dalam pemrograman) dan tampilan (menggunakan gambar).

## API Permainan
1. Buat permainan baru.  
	Membuat permainan baru kemudian menunggu pemain lain untuk bergabung ke dalam permainan tersebut.
2. Lihat daftar permainan.
	Melihat seluruh permainan yang terdaftar tetapi permainan masih berstatus menunggu.
3. Gabung ke dalam permainan.
	Bergabung ke dalam permainan tertentu.
4. Mulai permainan.
	Memulai permainan. Permainan hanya dapat dimulai oleh pemain yang membuat permainan dan hanya dapat dimulai ketika jumlah pemain minimal 2 orang.
5. Permainan selesai.
	Permainan dinyatakan selesai. Tugas ini dilakukan oleh server untuk menjamin bahwa permainan memang benar-benar telah selesai.
6. Kocok kartu.
	Merandom urutan kartu yang digunakan pada permainan. Kegiatan ini di-trigger oleh pemain yang menciptakan permainan.
7. Bagi kartu ke setiap pemain.
	Membagikan kartu ke seluruh pemain. Kegiatan ini di-trigger oleh pemain yang menciptakan permainan.
8. Lempar kartu.
	Melempar kartu ke meja. Hanya dapat dilakukan oleh pemain pada saat gilirannya.
9. Cangkol.
	Mencangkol kartu dari tumpukan kartu yang tersedia. Jika tidak ada kartu maka pemain tersebut akan mengambil seluruh kartu yang ada dimeja.

## Requirement
1. Meja harus memiliki tempat menampung kartu yang akan dilemparkan oleh pemain dan tumpukan kartu sebagai cangkolan.
2. Pemain dapat mengambil kartu yang ada di atas meja ataupun kartu cangkolan
