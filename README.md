<h1>Sample Code Socket Client</h1>
<p>Project ini berisi sampel code untuk mengakses server socket.io</p>
<p>versi socket.io yang digunakan adalah socket.io v2,</p>

<h3>Setting</h3>
<ul>
    <li>
        <h5>socketServerURL</h5>
        <p>Ganti dengan URL Server Socket yang akan digunakan</p>
    </li>    
    <li>
        <h5>client_id</h5>
        <p>Bagian ini sesuaikan dengan credential yang didapat dari admin</p>
    </li>    
    <li>
        <h5>client_secret</h5>
        <p>Bagian ini sesuaikan dengan credential yang didapat dari admin</p>
    </li>    
    <li>
        <h5>account_number</h5>
        <p>Ganti dengan nomor account yang dimiliki merchant.</p>
    </li>    
</ul>

<h3>Cara Menjalankan Aplikasi</h3>
<strong>PHP</strong> <br/>
php -S localhost:3001 index.html

<br/>
<br/>
<strong>NODEJS</strong> <br/>
Buat Project dengan nodejs, lalu serve index.html sebagai root staticnya

<br/>
untuk kebutuhan uji coba, pastikan menggunakan port 3001 untuk menjalankan project ini, atau host dan port sesuai dengan data whitelist atau credential yang telah dibuat oleh admin.
