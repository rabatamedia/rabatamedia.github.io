<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">

    <title>Rabata Server - Aplikasi SMS</title>
  </head>
  <body>
  
  <div class="container";>
  <form method="post" action="">
  		<h1> Aplikasi SMS - Rabata Server </h1>
        Efektif digunakan untuk pengumuman dan pemasaran
	      <div  class="mb-3">
		    <label for="exampleFormControlInput1" class="form-label"><strong>No. HP Tujuan</strong></label>
		    <input type="text" class="form-control" name="no_tujuan" placeholder="082331009919">
		  </div>
		  <div class="mb-3">
		     <label for="exampleFormControlTextarea1" class="form-label"><strong>Isi Pesan</strong></label>
		     <textarea class="form-control" name="isi_pesan" rows="3">Kpd Yth Anggota KSP CULT KC Bonti. Dapatkan fasilitas bunga kredit 0,92% Menurun utk Kredit dibawah Simpanan Muhunt. Siapkan KTP dan KK. Proses cepat. (Rabata)</textarea>
		  </div>
		  <div class="d-grid gap-2">
		      <button class="btn btn-primary" type="submit" name="bkirim">Kirim</button>
		   </div>
	</form>
</div>

<!-- Fungsi PHP -->
<?php
	//jika berhasil dalam kirim pesan 
	if (isset($_POST['bkirim'])) {
		$no_tujuan = $_POST['no_tujuan'];
		$isi_pesan = $_POST['isi_pesan'];
		$sending = sendsms($no_tujuan, $isi_pesan);
		if ($sending =="success") {	 
  			echo "Pesan Berhasil dikirim";
			} else {
				echo "Pesan Gagal dikirim";
			}
		}
	//fungsi untuk mengirim pesan
	function sendsms($no_tujuan, $isi_pesan) {
		$idmesin = "638";
		$pin = "20222022";

		//jika ada spasi ganti %20
		$isi_pesan = str_replace(" ", "%20", $isi_pesan);
                
		//persiapkan curl
		$ch = curl_init();
        
		//set url
		curl_setopt($ch, CURLOPT_URL, "https://sms.indositus.com/sendsms.php?idmesin=$idmesin&pin=$pin&to=$no_tujuan&text=$isi_pesan");
        
		//aktifkan curl
		curl_setopt($ch, CURLOPT_RETURNTRANSFER, 1);
        
		//mematikan verifikasi SSL
		curl_setopt($ch, CURLOPT_SSL_VERIFYHOST, 0);
		curl_setopt($ch, CURLOPT_SSL_VERIFYPEER, 0);
        
		//tampung data
		$output = curl_exec($ch);
        
		//tutup curl
		curl_close($ch);
        
        //selesai
        return $output;

	}
 ?>

<!-- Kode Fungsi PHP selesai -->

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
    -->
  </body>
</html>
