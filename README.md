# SEMANTIC-HTML
Latihan Praktikum 1 Semantik HTML
##penjelasan
1. ada dan tidak nya struktur penting untuk html seperti tag `html`,`head`,`body`yang ber efek beberapa fitur mungkin tidak akan berfungsi optimal  di bandingkan yang lengkap karna beberapa browser ada yang memiliki standart HTML5.
2. fungsi penting yang terlewati ketika tag <head> tidak ada karna tag <head> memiliki beberapa fungsi penting seperti metadata yang mengatur encoding `<meta charset="UTF-8"` dan viewport `<meta name="viewport" content="width=device-width,initial-scale=1.0">` yang ber efek menampilkan karakter dengan benar terutama ketika ada symbol tertentu, tampilan akan lebih responsif dan akan lebih enak dilihat.
3. ketidak adaan tag `body` akan membuat browser kebingungan ketika memproses tag `header`, `nav`, `section`, `footer` karena keberadaan elemen tersebut seharusnya berada di dalam tag `body`.
4. refresi ke css juga penting dalam hal ini, karena tanpa adanya refresi ke css `style.css` tampilan yang seharusnya sudah di atur di folder css tidak akan terhubung ke source code html dan tidak akan di tampilkan ketika di run
