#### HTML Structure
section.wiki
div.container
img: Gambar logo Wikipedia
h3: Judul/teks yang menjelaskan fungsi pencarian
form.form: Formulir pencarian
input.form-input: Input teks untuk pencarian
button.submit-btn: Tombol untuk mengirim pencarian
div.results: Bagian untuk menampilkan hasil pencarian
div.articles: Daftar artikel yang ditemukan
a: Tautan menuju halaman Wikipedia
h4: Judul artikel
p: Deskripsi singkat dari artikel
div.Favorites: Daftar artikel yang telah difavoritkan
div.articles: Artikel favorit yang telah disimpan
a: Tautan menuju halaman Wikipedia
h4: Judul artikel
p: Deskripsi singkat artikel
button: Tombol untuk menghapus favorit dari daftar
background :untuk mempercantik tampilan
#### API DOCS

- [wiki docs](https://www.mediawiki.org/wiki/API:Main_page)

- ready to go url's

#### Initial Setup

- select form, input, results
- listen for submit events
- if empty value, display error
- create fetchPages()
- pass valid input value into the fetchPages()

#### Fetch Pages

- display loading while fetching
- construct dynamic url
- display if error
- display error no items
- create renderResults()
- pass valid results into renderResults()

#### Render Results

- iterate over the list
- pull out title, snippet, pageid
- setup a card
- set results with div.articles and list inside
