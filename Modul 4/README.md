 # Modul 4 - Halaman Ramadan dengan Bootstrap

# Kode Program

# index.html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ramadan Kareem</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-dark text-white">

    <div class="min-vh-100 d-flex flex-column align-items-center justify-content-center text-center py-5">

        <div class="mb-4">
            <p style="font-size:100px">🌙</p>
            <h1 class="display-3 fw-bold text-warning">Ramadan Kareem</h1>
            <p class="lead text-light">Marhaban Ya Ramadan 1446 H</p>
        </div>

        <div class="container">
            <div class="row justify-content-center g-4">
                <div class="col-md-4">
                    <div class="card bg-secondary text-white h-100">
                        <div class="card-body text-center">
                            <p class="fs-1">🕌</p>
                            <h5 class="card-title text-warning">Perbanyak Ibadah</h5>
                            <p class="card-text">Bulan penuh berkah untuk memperbanyak sholat, dzikir, dan membaca Al-Quran.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card bg-secondary text-white h-100">
                        <div class="card-body text-center">
                            <p class="fs-1">⭐</p>
                            <h5 class="card-title text-warning">Malam Lailatul Qadar</h5>
                            <p class="card-text">Malam yang lebih baik dari seribu bulan, raihlah di 10 malam terakhir Ramadan.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card bg-secondary text-white h-100">
                        <div class="card-body text-center">
                            <p class="fs-1">🤲</p>
                            <h5 class="card-title text-warning">Perbanyak Sedekah</h5>
                            <p class="card-text">Ramadan adalah bulan berbagi, perbanyak sedekah dan bantu sesama.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="container mt-5">
            <div class="card bg-secondary text-white mx-auto" style="max-width:600px">
                <div class="card-body">
                    <p class="text-warning fst-italic fs-5">"Barang siapa yang berpuasa di bulan Ramadan dengan penuh keimanan dan mengharap pahala, maka dosa-dosanya yang telah lalu akan diampuni."</p>
                    <p class="text-light small">- HR. Bukhari & Muslim</p>
                </div>
            </div>
        </div>

        <div class="mt-5">
            <p class="text-warning fs-5">✨ Selamat Menunaikan Ibadah Puasa ✨</p>
            <p class="text-light small">Semoga amal ibadah kita diterima Allah SWT</p>
        </div>

    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

## Deskripsi
Membuat halaman web untuk merayakan bulan Ramadan menggunakan Bootstrap 5 semaksimal mungkin dan meminimalkan penggunaan native CSS.
- HTML
- Bootstrap 5
- Sedikit Native CSS (cuma buat ukuran emoji dan max-width card)

## Penjelasan Penggunaan Bootstrap
Hampir seluruh styling pada halaman ini menggunakan class Bootstrap, diantaranya:

- bg-dark dan text-white untuk warna background dan teks
- min-vh-100, d-flex, align-items-center, justify-content-center untuk layout tengah layar
- display-3, fw-bold, text-warning, lead untuk styling teks dan judul
- container, row, col-md-4, g-4 untuk sistem grid dan layout kartu
- card, card-body, card-title, card-text untuk komponen kartu
- bg-secondary untuk warna kartu
- fst-italic, fs-1, fs-5, small untuk ukuran dan style teks
- mt-5, mb-4, py-5, p-4 untuk jarak antar elemen

## Native CSS yang Digunakan
Sesuai tugas yaitu sebisa mungkin tanpa menggunakan native CSS, native CSS yang digunakan hanya sebatas dua hal yaitu font-size pada emoji karena Bootstrap tidak menyediakan ukuran emoji sebesar itu, dan max-width pada card quote agar tampilannya tidak terlalu lebar di layar besar.

## Hasil
![Hasil Halaman Ramadan](screenshot-modul-4.png)