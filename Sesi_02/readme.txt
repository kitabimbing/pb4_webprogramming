pembelajaran sesi 02
________________________________________
/ = slash
\ = back slash
________________________________________
<nametag>
content/text
</nametag>

menggunakan html 
> diawali:  > all element (menyesuaikan) 
            > mengenal attribut 
                > id > unix / primary key
                > name
                > data-id data-nama
                > readonly/disabled/hidden/dll

    <div>
    context/text
    </div>


    <input />
 
    <select>
    <option></option>
    </select>

    > backtick > `

method :
    > post
    > patch
    > delete
    > dll

menggunakan id : #
menggunakan class : .
________________________________________
<p id="" name="">
    Hello Paragraf
</p>
________________________________________

tabel:
    - client side >  tampil seluruh (pagination)
        > next data dari 10 ke 20 > tanpa internet
    - server side > pagination > load 10
        > total data 100 
        > yg akan di tampilkan 10

biodata siswa
no | nis | nama | jenis_kelamin
1  | 1   | arif | laki-laki
2  | 1   | arif | laki-laki
3  | 1   | arif | laki-laki
4  | 1   | arif | laki-laki
5  | 1   | arif | laki-laki
total data siswa : 5

<table>
    thead
    tbody
    tfoot
</table>

________________________________________

----------- index.html
----------- assets
            ---- images
            ---- css
            ---- script

________________________________________
contoh code tugas sesi 02: 

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tugas Mandiri Sesi 2 (Arif Setiawan)</title>
  </head>
  <body style="background-color: antiquewhite;">
    <h2>Arif Setiawan</h2>
    <a href="https://instagram.com/" target="_blank">Instagram</a>
    <a href="https://linkedin.com/" target="_blank">LinkedIn</a>
    <a href="https://github.com/arifswn" target="_blank">Portofolio</a>
    <h2>Profile</h2>
    <p>Lulusan S1 Teknik Informatika dengan spesialis di bidang Marketing.</p>
    <h2>Technical Skill</h2>
    <ol>
        <li>Golang</li>
        <li>ASP</li>
        <li>PHP</li>
    </ol>
    <h2>Education</h2>
    <ul>
        <li>SD 1</li>
        <li>SMP 1</li>
        <li>SMK 1</li>
    </ul>
    <h2>Inquiry</h2>
    <form action="">
        <div>
            <label for="">Email</label>
            <br>
            <input type="email" placeholder="Masukkan Email Anda">
        </div>
        <div>
            <label for="">Your Question</label>
            <br>
            <textarea name="" id="" placeholder="Masukkan Pertanyaan Anda" rows="5"></textarea>
        </div>
        <button type="submit">Simpan</button>
    </form>
    <p style="text-align: center; background-color: aqua; padding: 10px;">Copyright &copy; 2024 by Arif.</p>
  </body>
</html>

            