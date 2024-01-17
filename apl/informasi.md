### Aplikasi R dan Shiny untuk Mendemonstrasikan Teorema Limit Pusat

::: {style="text-align: justify;"}
Tujuan aplikasi interaktif ini adalah untuk mendemonstrasikan Teorema Limit Pusat untuk distribusi sampling proporsi dan rerata satu populasi. Beberapa ide penting statistik ditunjukkan oleh aplikasi ini. Ide-ide penting tersebut antara lain adalah sebagai berikut.
:::

::: {style="text-align: justify;"}
-   Jika ukuran sampelnya cukup besar, distribusi sampling proporsinya mendekati normal.

-   Distribusi sampling proporsi tersebut memiliki rerata sama dengan proporsi populasinya dan simpangan bakunya sama dengan akar kuadrat dari hasil kali antara proporsi populasi dan satu dikurangi proporsi tersebut kemudian dibagi dengan ukuran sampel.

-   Jika ukuran sampelnya cukup besar, distribusi sampling reratanya mendekati normal.

-   Untuk sampel yang berukuran kecil, distribusi sampling reratanya mendekati normal jika populasi dari sampel tersebut berdistribusi normal.

-   Distribusi sampling rerata tersebut memiliki rerata yang sama dengan rerata populasinya dan simpangan baku yang sama dengan simpangan baku populasi dibagi dengan akar kuadrat ukuran sampel.
:::

::: {style="text-align: justify;"}
Aplikasi interaktif ini dikembangkan dengan menggunakan bahasa pemrogram [R](https://www.R-project.org/) dan paket [Shiny](https://CRAN.R-project.org/package=shiny). Paket [shinylive](https://posit-dev.github.io/r-shinylive/) digunakan untuk mengekspor aplikasi ini agar dapat dijalankan di peramban web tanpa peladen R yang terpisah.

Aplikasi ini hampir seluruhnya terinspirasi oleh [aplikasi-aplikasi interaktif](https://github.com/ShinyEd/intro-stats) yang dikembangkan oleh Mine Çetinkaya-Rundel. Pengembang aplikasi ini adalah [Yosep Dwi Kristanto](https://people.usd.ac.id/~ydkristanto/), seorang dosen dan peneliti di program studi [Pendidikan Matematika,](https://usd.ac.id/s1pmat) [Universitas Sanata Dharma,](https://www.usd.ac.id/) Yogyakarta.
:::
