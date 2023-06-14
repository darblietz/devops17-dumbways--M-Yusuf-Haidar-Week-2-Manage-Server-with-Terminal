# Task Manage Terminal
#### 1. Penjelasan text manipulation beserta step by step
- Cat adalah salah satu perintah dasar dalam sistem operasi Linux yang paling sering digunakan. Fungsinya untuk mencantumkan, menggabungkan, dan menulis konten atau isi file dalam output standar.<br/>
 Contoh :<br/>
 1. ``$ cat (file-name)`` fungsinya untuk menampilkan isi dari file1.<br/><br/>![1  Cat](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/abc8cd89-db32-4ac5-a5db-a78de658b476)<br/><br/>
 2. ``$ cat > (file-name)`` fungsinya untuk membuat file sekaligus membuat isi berupa teks untuk file tersebut. Jika sudah mengisi bisa keluar dengan ``CTRL + C``.<br/><br/>![2  Cat](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/b14f7c40-6876-40e4-ac7c-82a3283fb24a)<br/><br/>
 3. ``$ cat (file-name) (file-name) > (file-name)`` untuk membuat file dan menggabungkan 2 isi buah file lalu menyisipkan isi ke file yang baru.<br/><br/>![3  Cat](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/7e489aad-4bcc-42b4-adb8-63e1268462e6)<br/><br/>
 4. ``$ sed -i 's/Halooooo/Hai/g' file3`` Sed untuk mengubah/memanipulasi sebuah teks dalam sebuah file.<br/><br/>![4  Sed](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/fe32ce84-a9ef-4c9f-b79b-d30711df3c4b)<br/><br/>
 5. ``$ grep Rommel file2``untuk melakukan pencarian sebuah text dalam sebuah file yang telah dibuat.<br/><br/>![5  Grep](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/c3e89fb2-2594-4e2c-bc19-d1d2ea2ee07a)<br/><br/>
 6. ``$ grep -c Rommel file2``memberitahu jumlah kata "Rommel" pada file2<br/><br/>![6  Grep](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/f5b0a67d-a493-41f7-869f-b9d4bb6a363b)<br/><br/>
 7. ``$ grep Rommel *`` fungsinya untuk mencari ke semua file yang valuenya "Rommel".<br/><br/>![7  Grep](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/51d2ffc0-d4ec-4897-8a1d-c4247e5d46d3)<br/><br/>
 8. ``$ sort (file-name)`` untuk mengurutkan berdasarkan ascending<br/><br/>![8  Sort](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/55aee661-ab7c-47d8-be8c-c53aaf51a86d)<br/><br/>
 9. ``$ sort -r (file-name)`` untuk mengurutkan secara reverse atau descending <br/><br/>![9  Sort -r](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/d0810781-67d2-42fb-9cd7-7f07181e31ae)<br/><br/>
 10. ``$ echo "Reichmarschall!!"`` digunakan untuk mencetak string / pesan dari hasil perintah lain.<br/><br/>![10  echo](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/7c275936-b608-4903-a698-f345bee5440d)<br/><br/>
 11. ``$ echo "Reichmarschall! >> file5`` untuk mencetak kata "Reichmarschall!" di file3<br/><br/>![11  echo](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/1e61855a-8b13-4349-b57d-b57ff3566e2e)<br/><br/>
 12. ``$ echo "Capital!" > file5`` fungsinya untuk mereplace semua data di file5.<br/><br/>![12  echo](https://github.com/darblietz/devops17-dumbways--M-Yusuf-Haidar-Week-2-Manage-Terminal/assets/98991080/166f0084-5709-4e3c-812c-2ed288496b9a)<br/><br/>
 

 









#### 2. Penjelasan tool htop atau nmon
