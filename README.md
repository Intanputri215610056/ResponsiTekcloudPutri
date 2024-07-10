# ResponsiTekcloudPutri
1. Membuat direktori baru bernama website-profil.
     'mkdir website-profil'
   
2. Berpindah ke direktori website-profil.
     'cd website-profil'

3. Upload foto terlebih dahulu.
   
4. Membuat atau mengedit berkas index.html menggunakan editor teks nano.
     'nano index.html'
     
5. Membuat Jaringan Docker
     'docker network create my-Intan-Putri-Predita-Sari-network'

6. Membuat Dockerfile
     'nano Dockerfile'

7. Memeriksa Isi Direktori
   'ls'
   
8. Membangun Image Docker
   'docker build -t website-profil .'
   
9. Menjalankan Container Docker
   'docker run -d --name website-profil --network my-Intan-Putri-Predita-Sari-network -p 8081:80 website-profil'
     
10. Membuat Direktori dan Dockerfile untuk Website Utama
    'mkdir website-utama'

11. Berpindah ke direktori website-utama.
    'cd website-utama'

13. Membuat atau mengedit berkas Dockerfile dan index.html menggunakan editor teks nano.
    'nano Dockerfile'
    'nano index.html'

15. Membangun Image Docker untuk Website Utama
    'docker build -t website-utama .'

17. Menjalankan Container Docker untuk Website Utama
    'docker run -d --name website-utama --network my-Intan-Putri-Predita-Sari-network -p 8080:80 website-utama'


     
