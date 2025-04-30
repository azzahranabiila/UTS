# UTS PEMOGRAMAN WEB 2
# Nama : Azzahra Nabiila
# Nim : 312310367
# kelas : Ti.23.A4

Implementasi Sederhana: Eksperimen dengan WebAssembly
Untuk memahami cara kerja WebAssembly secara praktis, saya melakukan eksperimen sederhana

Fibonacci.c
![fibonacci c](https://github.com/user-attachments/assets/64da1c9b-11af-4398-8676-40b8b18def88)

Compile fibonacci.c ke WebAssembly
bash emcc fibonacci.c -o fibonacci.js -s WASM=1 -s EXPORTED_FUNCTIONS=’[“_fibonacci”]’ -s EXPORTED_RUNTIME_METHODS=’[“cwrap”]’

Ini akan menghasilkan fibonacci.js dan fibonacci.wasm.

Index HTML
![index html](https://github.com/user-attachments/assets/4611e114-0082-46f9-8e24-f5cbd8742080)

![main js 1](https://github.com/user-attachments/assets/508d0ab6-d27b-4acc-99ef-95cc4a8c4a17)
![main js 2](https://github.com/user-attachments/assets/7cadbb29-d3b2-4620-84d9-53ea62726518)

Hasil
![hasil 1](https://github.com/user-attachments/assets/4e416c65-0520-4acc-9526-a7c2e6f112b8)
![hasil 2](https://github.com/user-attachments/assets/913db306-07e8-4263-b77c-b3a49f0f5e6c)
