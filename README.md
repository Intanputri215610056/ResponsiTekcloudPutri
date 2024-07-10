# ResponsiTekcloudPutri
1. Membuat direktori baru bernama website-profil.
   ```
        mkdir website-profil
   ```
   
3. Berpindah ke direktori website-profil.
   ```
        cd website-profil
   ```

4. Upload foto terlebih dahulu.
   
5. Membuat atau mengedit berkas index.html menggunakan editor teks nano.
   ```
        nano index.html
   ```
     
7. Membuat Jaringan Docker
   ```
        docker network create my-Intan-Putri-Predita-Sari-network
   ```

8. Membuat Dockerfile
   ```
        nano Dockerfile
   ```

9. Memeriksa Isi Direktori
   ```
        ls
   ```
   
10. Membangun Image Docker
    ```
         docker build -t website-profil .
    ```
   
11. Menjalankan Container Docker
    ```
         docker run -d --name website-profil --network my-Intan-Putri-Predita-Sari-network -p 8081:80 website-profil
    ```
     
12. Membuat Direktori dan Dockerfile untuk Website Utama
    ```
         mkdir website-utama
    ```

14. Berpindah ke direktori website-utama.
    ```
         cd website-utama
    ```

16. Membuat atau mengedit berkas Dockerfile dan index.html menggunakan editor teks nano.
    ```
         nano Dockerfile
         nano index.html
    ```

17. Membangun Image Docker untuk Website Utama
    ```
         docker build -t website-utama .
    ```

18. Menjalankan Container Docker untuk Website Utama
    ```
         docker run -d --name website-utama --network my-Intan-Putri-Predita-Sari-network -p 8080:80 website-utama
    ```


     
