# Notes App menggunakan React

Ini adalah aplikasi catatan sederhana yang dibuat menggunakan React. Aplikasi ini memungkinkan pengguna untuk menambah, mengedit,mengarsipkan dan menghapus catatan.

## Fitur Utama

- **Tambah Catatan:** Pengguna dapat menambah catatan baru dengan judul dan konten tertentu.
- **Edit Catatan:** Memungkinkan pengguna untuk mengedit isi catatan yang sudah ada.
- **Hapus Catatan:** Pengguna dapat menghapus catatan yang tidak diperlukan lagi.
- **Penyimpanan Lokal:** Data catatan disimpan secara lokal di perangkat pengguna.

## Instalasi

Pastikan Node.js sudah terinstal di komputer Anda sebelum memulai.

1. Clone repositori ini ke komputer Anda.
2. Buka terminal dan masuk ke direktori proyek.
3. Jalankan perintah `npm install` untuk menginstal semua dependensi.
4. Setelah selesai, jalankan aplikasi dengan perintah `npm start`.
5. Aplikasi akan terbuka di browser pada alamat `http://localhost:3000`.

## Struktur Proyek

- **`src/`**: Direktori utama aplikasi.
  - **`components/`**: Komponen React seperti `Body`, `Header`, dll.
  - **`style.css`**: CSS dari Aplikasi.
  - **`index.jsx`**: File utama untuk merender aplikasi ke DOM.
- **`utils/`**: initial data yang diberikan pada  project

## Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan beberapa teknologi utama:

- **React**: Library JavaScript untuk membangun antarmuka pengguna.
- **vite**: Build tool yang digunakan untuk pengembangan aplikasi.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, berikut langkah-langkahnya:

1. Fork repositori ini.
2. Buat branch baru (`git checkout -b fitur-baru`).
3. Lakukan perubahan dan commit (`git commit -m 'Menambahkan fitur baru'`).
4. Push ke branch Anda (`git push origin fitur-baru`).
5. Buat pull request.

## Catatan Penting

Pastikan untuk memperbarui package dependencies (`npm install`) sebelum memulai kontribusi baru.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](https://opensource.org/licenses/MIT).
Projek ini dibuat sebagaimana kelas di Dicoding Indonesia, dan juga bagian dari Indosat Ooredoo Hutchison Camp 2023.


# Notes App using React (English)

This is a simple note-taking application built using React. The app allows users to add, edit, and delete notes.

## Key Features

- **Add Note:** Users can add a new note with a specific title and content.
- **Edit Note:** Allows users to modify the content of existing notes.
- **Delete Note:** Users can remove unnecessary notes.
- **Local Storage:** Note data is stored locally on the user's device.

## Installation

Ensure Node.js is installed on your computer before starting.

1. Clone this repository to your computer.
2. Open the terminal and navigate to the project directory.
3. Run the command `npm install` to install all dependencies.
4. Once done, start the application using `npm start`.
5. The app will open in the browser at `http://localhost:3000`.

## Project Structure

- **`src/`**: Main directory of the application.
  - **`components/`**: React components such as `NoteList`, `Note`, etc.
  - **`App.js`**: Main component rendering the application.
  - **`index.js`**: Main file rendering the application to the DOM.
- **`public/`**: Public directory for files like icons, HTML, etc.

## Technologies Used

This application is built using several key technologies:

- **React**: JavaScript library for building user interfaces.
- **localStorage**: For storing note data locally on the user's device.

## Contribution

If you wish to contribute to this project, here are the steps:

1. Fork this repository.
2. Create a new branch (`git checkout -b new-feature`).
3. Make changes and commit (`git commit -m 'Added a new feature'`).
4. Push to your branch (`git push origin new-feature`).
5. Create a pull request.

## Important Notes

Make sure to update package dependencies (`npm install`) before starting any new contributions.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
This project is made as a project for a class in Dicoding Indonesia, which is a part of Indosat Ooredoo Hutchison Camp 2023.