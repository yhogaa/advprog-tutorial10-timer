# Pemrograman Lanjut A
> Fadrian Yhoga Pratama - 2206819395

## Module 10 - Asynchoronous Programming

## 1.2. Understanding how it works.
![1.2](assets/img/1.2.jpg)
Berdasarkan gambar diatas, dapat dilihat bahwa print statement "hey hey" jalan lebih dulu kemudian baru "howdy!" dan "done!". Ini terjadi karena print statement "hey "hey" berada di main() bukan di asynchronous task. Jadi, meskipun task berada sebelum print statement "hey hey", namun task tersebut baru dieksekusi setelahnya oleh Executor. 