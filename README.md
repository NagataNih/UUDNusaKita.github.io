<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UUD Nusa Kita</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #E9ECEF;
            margin: 0;
            padding: 0;
        }

        .header {
            background-color: #002366;
            color: rgb(255, 255, 255);
            padding: 20px 0;
            font-size: 24px;
            font-weight: bold;
        }

        .sub-header {
            background-color: #007BFF;
            color: black;
            padding: 10px 0;
            font-size: 20px;
        }

        .form-container {
            margin: 20px auto;
            max-width: 600px;
            padding: 20px;
            background-color: #1E90FF;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        input[type="text"] {
            width: 80%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }

        .info-box {
            background-color: #EAF4FF;
            color: black;
            padding: 15px;
            margin: 10px 0;
            font-size: 18px;
            font-weight: bold;
        }

        .submit-button {
            background-color: #87CEEB;
            color: #002366;
            padding: 10px 20px;
            border: #000000;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }

        table {
            margin: 20px auto;
            border-collapse: collapse;
            width: 90%;
        }

        table, th, td {
            border: 1px solid black;
        }

        th, td {
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: #6495ED;
        }

        .section-title {
            background-color: #00FFFF;
            color: black;
            padding: 10px;
            margin: 20px 0;
            font-size: 20px;
            font-weight: bold;
        }

        .footer {
            margin-top: 20px;
            font-size: 14px;
        }

        .footer a {
            color: blue;
            text-decoration: none;
        }

        .result-box {
            margin: 20px auto;
            padding: 20px;
            background-color: #ffffcc;
            border: 1px solid #ccc;
            font-size: 18px;
            display: none;
            max-width: 600px;
            text-align: left;
        }
    </style>
</head>
<body>
    <div class="header">Kitab Undang-Undang Hukum Pidana Kota Nusa Kita</div>
    <div class="sub-header">
        <span>&#129332; Kepolisan Kota Arivena &#129332;</span>
    </div>

    <div class="form-container">
        <form id="mainForm">
            <label for="name">Nama Suspect :</label><br>
            <input type="text" id="name" name="name" placeholder="Masukkan nama...">

            <div class="info-box">
                MAXIMAL JAIL 90 BULAN, BOLEH DILEBIHKAN KALAU SUSPECT TIDAK MEMBAYAR INVOICE/INVOICE MENUMPUK.
            </div>

            <div class="info-box">
                PENJARA KASUS DPO PENJARA 120 BULAN.
            </div>

            <button type="button" class="submit-button" onclick="displayResult()">Submit</button>
        </form>
    </div>

    <div class="result-box" id="resultBox"></div>

    <div class="section-title">TINDAK PIDANA TERHADAP NYAWA</div>
    <table id="offenseTable1">
        <tr>
            <th>PASAL(AYAT)</th>
            <th>CEKLIS</th>
            <th>PELANGGARAN</th>
            <th>DENDA($)</th>
            <th>MASA TAHANAN(BULAN)</th>
        </tr>
        <tr>
            <td>7(1)</td>
            <td><input type="checkbox" value="7.2"></td>
            <td>Terorisme</td>
            <td>100000</td>
            <td>99999</td>
        </tr>
        <tr>
            <td>7(2)</td>
            <td><input type="checkbox" value="7.2"></td>
            <td>Percobaan Terorisme</td>
            <td>80000</td>
            <td>90</td>
        </tr>
        <tr>
            <td>8(1)</td>
            <td><input type="checkbox" value="8.1"></td>
            <td>Pembunuhan</td>
            <td>78000</td>
            <td>90</td>
        </tr>
        <tr>
            <td>8(2)</td>
            <td><input type="checkbox" value="8.2"></td>
            <td>Percobaan Pembunuhan</td>
            <td>60000</td>
            <td>45</td>
        </tr>
        <tr>
            <td>9(1)</td>
            <td><input type="checkbox" value="9.2"></td>
            <td>Penodongan Pada Warga Sipil</td>
            <td>56000</td>
            <td>30</td>
        </tr>
        <tr>
            <td>9(2)</td>
            <td><input type="checkbox" value="9.2"></td>
            <td>Penyanderaan</td>
            <td>50000</td>
            <td>30</td>
        </tr>
    </table>

    <div class="section-title">TINDAK PIDANA TERHADAP HARTA BENDA</div>
    <table id="offenseTable2">
        <tr>
            <th>PASAL(AYAT)</th>
            <th>CEKLIS</th>
            <th>PELANGGARAN</th>
            <th>DENDA($)</th>
            <th>MASA TAHANAN(BULAN)</th>
        </tr>
        <tr>
            <td>10(1)</td>
            <td><input type="checkbox" value="10.1"></td>
            <td>Memberikan Informasi Palsu</td>
            <td>7000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>10(2)</td>
            <td><input type="checkbox" value="10.2"></td>
            <td>Melakukan Penipuan</td>
            <td>10000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>11(1)</td>
            <td><input type="checkbox" value="11.1"></td>
            <td>Pencurian</td>
            <td>18000</td>
            <td>20</td>
        </tr>
        <tr>
            <td>11(2)</td>
            <td><input type="checkbox" value="11.2"></td>
            <td>Percobaan Pencurian</td>
            <td>15000</td>
            <td>15</td>
        </tr>
        <tr>
            <td>12(1)</td>
            <td><input type="checkbox" value="12.1"></td>
            <td>Perampokan Warung</td>
            <td>45000</td>
            <td>30</td>
        </tr>
        <tr>
            <td>12(2)</td>
            <td><input type="checkbox" value="12.2"></td>
            <td>Perampokan Bank</td>
            <td>70000</td>
            <td>60</td>
        </tr>
    </table>

    <div class="section-title">TINDAK PIDANA TERHADAP SENJATA ILEGAL</div>
    <table id="offenseTable3">
        <tr>
            <th>PASAL(AYAT)</th>
            <th>CEKLIS</th>
            <th>PELANGGARAN</th>
            <th>DENDA($)</th>
            <th>MASA TAHANAN(BULAN)</th>
        </tr>
        <tr>
            <td>13(1)</td>
            <td><input type="checkbox" value="13.1"></td>
            <td>Kepemilikan Senjata Tajam/Tumpul Untuk Kejahatan</td>
            <td>4000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>13(2)</td>
            <td><input type="checkbox" value="13.2"></td>
            <td>Kepemilikan Senjata Api Illegal Laras Pendek</td>
            <td>8000</td>
            <td>15</td>
        </tr>
        <tr>
            <td>13(3)</td>
            <td><input type="checkbox" value="13.3"></td>
            <td>Kepemilikan Senjata Api Illegal Laras Menengah</td>
            <td>10000</td>
            <td>20</td>
        </tr>
        <tr>
            <td>13(4)</td>
            <td><input type="checkbox" value="13.4"></td>
            <td>Kepemilikan Senjata Api Illegal Laras Panjang</td>
            <td>20000</td>
            <td>25</td>
        </tr>
        <tr>
            <td>14(1)</td>
            <td><input type="checkbox" value="14.1"></td>
            <td>Perdagangan Senjata Api Illegal</td>
            <td>32000</td>
            <td>25</td>
        </tr>
        <tr>
            <td>14(2)</td>
            <td><input type="checkbox" value="14.2"></td>
            <td>Pembuangan Senjata Api Secara Sengaja</td>
            <td>15000</td>
            <td>25</td>
        </tr>
    </table>

    <div class="section-title">TINDAK PIDANA TERHADAP KEAMANAN DAN KETERTIBAN UMUM</div>
    <table id="offenseTable4">
        <tr>
            <th>PASAL(AYAT)</th>
            <th>CEKLIS</th>
            <th>PELANGGARAN</th>
            <th>DENDA($)</th>
            <th>MASA TAHANAN(BULAN)</th>
        </tr>
        <tr>
            <td>15(1)</td>
            <td><input type="checkbox" value="15.1"></td>
            <td>Tidak Membawa Kartu Identitas</td>
            <td>1000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>15(2)</td>
            <td><input type="checkbox" value="15.2"></td>
            <td>Berada Di TKP</td>
            <td>3000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>15(3)</td>
            <td><input type="checkbox" value="15.3"></td>
            <td>Pencemaran Nama Baik</td>
            <td>5000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>15(4)</td>
            <td><input type="checkbox" value="15.4"></td>
            <td>Perkelahian Di Tempat Umum</td>
            <td>4000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>15(5)</td>
            <td><input type="checkbox" value="15.5"></td>
            <td>Memakai dan Melakukan Hal Tidak Sesonoh</td>
            <td>4000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>15(6)</td>
            <td><input type="checkbox" value="15.6"></td>
            <td>Pengancaman Terhadap Warga</td>
            <td>6000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>15(7)</td>
            <td><input type="checkbox" value="15.7"></td>
            <td>Pembuangan Barang Bukti Secara Sengaja</td>
            <td>8000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>15(8)</td>
            <td><input type="checkbox" value="15.8"></td>
            <td>Kerusuhan DI Tempat Umum</td>
            <td>3000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>15(9)</td>
            <td><input type="checkbox" value="15.9"></td>
            <td>Penganiayaan Terhadap Warga</td>
            <td>8000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>15(10)</td>
            <td><input type="checkbox" value="16.1"></td>
            <td>Pembajakan</td>
            <td>7000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>15(11)</td>
            <td><input type="checkbox" value="16.2"></td>
            <td>Peperangan</td>
            <td>10000</td>
            <td>20</td>
        </tr>
        <tr>
            <td>16(1)</td>
            <td><input type="checkbox" value="16.3"></td>
            <td>Berada Di Zona Terlarang</td>
            <td>3000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>16(2)</td>
            <td><input type="checkbox" value="16.3"></td>
            <td>Pemburuan Illegal</td>
            <td>4000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>16(3)</td>
            <td><input type="checkbox" value="16.3"></td>
            <td>Membawa Hewan Dilindungi</td>
            <td>5000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>16(4)</td>
            <td><input type="checkbox" value="16.4"></td>
            <td>Perjudian Illegal</td>
            <td>2000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>16(5)</td>
            <td><input type="checkbox" value="16.5"></td>
            <td>Mabuk Di Tempat Umum</td>
            <td>2000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>16(6)</td>
            <td><input type="checkbox" value="16.6"></td>
            <td>Pelecahan Seksual</td>
            <td>8000</td>
            <td>30</td>
        </tr>
    </table>

    <div class="section-title">TINDAK PIDANA BARANG ILLEGAL DAN NARKOBA</div>
    <table id="offenseTable5">
        <tr>
            <th>PASAL(AYAT)</th>
            <th>CEKLIS</th>
            <th>PELANGGARAN</th>
            <th>DENDA($)</th>
            <th>MASA TAHANAN(BULAN)</th>
        </tr>
        <tr>
            <td>17(1)</td>
            <td><input type="checkbox" value="17.1"></td>
            <td>Penyalahgunaan Barang Netral</td>
            <td>8000</td>
            <td>15</td>
        </tr>
        <tr>
            <td>17(2)</td>
            <td><input type="checkbox" value="17.2"></td>
            <td>Memiliki atau Menyimpan Barang Illegal</td>
            <td>8000</td>
            <td>15</td>
        </tr>
        <tr>
            <td>17(3)</td>
            <td><input type="checkbox" value="17.3"></td>
            <td>Perdagangan Barang Illegal</td>
            <td>10000</td>
            <td>20</td>
        </tr>
        <tr>
            <td>17(4)</td>
            <td><input type="checkbox" value="17.4"></td>
            <td>Memproduksi Barang Illegal</td>
            <td>12000</td>
            <td>20</td>
        </tr>
        <tr>
            <td>17(5)</td>
            <td><input type="checkbox" value="17.5"></td>
            <td>Mengonsumsi Narkoba</td>
            <td>7000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>17(6)</td>
            <td><input type="checkbox" value="17.5"></td>
            <td>Pembuangan Barang Netral/Illegal Secara Sengaja</td>
            <td>15000</td>
            <td>20</td>
        </tr>
    </table>

    <div class="section-title">TINDAK PIDANA TERHADAP APARATUR NEGARA</div>
    <table id="offenseTable6">
        <tr>
            <th>PASAL(AYAT)</th>
            <th>CEKLIS</th>
            <th>PELANGGARAN</th>
            <th>DENDA($)</th>
            <th>MASA TAHANAN(BULAN)</th>
        </tr>
        <tr>
            <td>18(1)</td>
            <td><input type="checkbox" value="18.1"></td>
            <td>Menghalangi Tugas Perintah</td>
            <td>3000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>18(2)</td>
            <td><input type="checkbox" value="18.2"></td>
            <td>Menolak Surat Tilang atau Perintah Resmi</td>
            <td>3000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>18(3)</td>
            <td><input type="checkbox" value="18.3"></td>
            <td>Melarikan Diri</td>
            <td>4000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>18(4)</td>
            <td><input type="checkbox" value="18.4"></td>
            <td>Pengancaman Petugas</td>
            <td>5000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>18(5)</td>
            <td><input type="checkbox" value="18.5"></td>
            <td>Pencemaran Nama Baik Instansi Pemerintah</td>
            <td>4000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>18(6)</td>
            <td><input type="checkbox" value="18.6"></td>
            <td>Menyuap Aparat Pemerintah</td>
            <td>7000</td>
            <td>15</td>
        </tr>
        <tr>
            <td>18(7)</td>
            <td><input type="checkbox" value="18.7"></td>
            <td>Menyerang Petugas Secara Verbal/NonVerbal</td>
            <td>8000</td>
            <td>15</td>
        </tr>
    </table>

    <div class="section-title">TINDAK PIDANA LALU LINTAS</div>
    <table id="offenseTable7">
        <tr>
            <th>PASAL(AYAT)</th>
            <th>CEKLIS</th>
            <th>PELANGGARAN</th>
            <th>DENDA($)</th>
            <th>MASA TAHANAN(BULAN)</th>
        </tr>
        <tr>
            <td>19(1)</td>
            <td><input type="checkbox" value="19.1"></td>
            <td>Kelengkapan Berkendara</td>
            <td>1000</td>
            <td>0</td>
        </tr>
        <tr>
            <td>19(2)</td>
            <td><input type="checkbox" value="19.2"></td>
            <td>Pelanggaran Lalu Lintas</td>
            <td>1500</td>
            <td>0</td>
        </tr>
        <tr>
            <td>19(3)</td>
            <td><input type="checkbox" value="19.3"></td>
            <td>Batas Kecepatan</td>
            <td>2000</td>
            <td>0</td>
        </tr>
        <tr>
            <td>19(4)</td>
            <td><input type="checkbox" value="19.4"></td>
            <td>Parkir Illegal</td>
            <td>2300</td>
            <td>0</td>
        </tr>
        <tr>
            <td>19(5)</td>
            <td><input type="checkbox" value="19.5"></td>
            <td>Modifikasi Illegal</td>
            <td>2900</td>
            <td>0</td>
        </tr>
        <tr>
            <td>19(6)</td>
            <td><input type="checkbox" value="19.6"></td>
            <td>Kendaraan Berada Dizona Terlarang</td>
            <td>3500</td>
            <td>3</td>
        </tr>
        <tr>
            <td>19(7)</td>
            <td><input type="checkbox" value="19.7"></td>
            <td>Membahayakan Pengendara Lain</td>
            <td>3000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>19(8)</td>
            <td><input type="checkbox" value="19.9"></td>
            <td>Balapan Liar</td>
            <td>3000</td>
            <td>5</td>
        </tr>
        <tr>
            <td>19(9)</td>
            <td><input type="checkbox" value="19.10"></td>
            <td>Kendaraan Membawa Barang Illegal</td>
            <td>2000</td>
            <td>10</td>
        </tr>
        <tr>
            <td>19(10)</td>
            <td><input type="checkbox" value="19.11"></td>
            <td>Kendaraan Membawa Senjata Illegal</td>
            <td>3000</td>
            <td>10</td>
        </tr>
    </table>

    <div class="footer">
        Bantu Support HANSKUY <a href="https://lynk.id/hanskuy">Klik Disini</a><br>
        Developer By : &#129332; HANSKUY16 &#129332;
        Edited pasal By : Ujang Pangestu
    </div>

    <script>
        function displayResult() {
            const name = document.getElementById("name").value;
            const resultBox = document.getElementById("resultBox");
            resultBox.innerHTML = "";

            if (!name) {
                resultBox.style.display = "block";
                resultBox.textContent = "Harap Isi Nama Terlebih Dahulu..";
                return;
            }

            let uuList = [];
            let pelanggaranList = [];
            let totalDenda = 0;
            let totalPenjara = 0;

            const collectData = (tableId) => {
                const checkboxes = document.querySelectorAll(`#${tableId} input[type='checkbox']`);
                checkboxes.forEach((checkbox) => {
                    if (checkbox.checked) {
                        const row = checkbox.closest("tr");
                        uuList.push(row.cells[0].textContent);
                        pelanggaranList.push(row.cells[2].textContent);
                        totalDenda += parseInt(row.cells[3].textContent);
                        totalPenjara += parseInt(row.cells[4].textContent);
                    }
                });
            };

            collectData("offenseTable1");
            collectData("offenseTable2");
            collectData("offenseTable3");
            collectData("offenseTable4");
            collectData("offenseTable5");
            collectData("offenseTable6");
            collectData("offenseTable7");

            if (uuList.length === 0) {
                resultBox.style.display = "block";
                resultBox.textContent = "Harap Pilih Salah Satu Pelanggaran.";
                return;
            }

            resultBox.style.display = "block";
            resultBox.innerHTML = `Nama Suspect : ${name}<br>Pasal(Ayat) : ${uuList.join(", ")}<br>Pelanggaran : ${pelanggaranList.join(", ")}<br>Total Denda : ${totalDenda}<br>Total Penjara : ${totalPenjara} bulan`;
        }
    </script>
</body>
</html>
