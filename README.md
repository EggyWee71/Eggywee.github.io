# Eggywee.github.io
background-image: url('https://www.example.com/your-image.jpg');
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Digital</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-image: url('https://www.example.com/your-image.jpg'); /* Ganti dengan gambar latar belakang */
            background-size: cover;
        }

        .invitation-card {
            background-color: rgba(255, 255, 255, 0.8); /* Efek transparan */
            border-radius: 10px;
            padding: 30px;
            max-width: 600px;
            width: 100%;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .invitation-card h1 {
            color: #ff6347; /* Warna merah untuk judul */
            font-size: 3em;
            margin: 0;
        }

        .invitation-card p {
            font-size: 1.5em;
            color: #333;
            margin: 20px 0;
        }

        .invitation-card .details {
            font-size: 1.2em;
            color: #555;
            margin-bottom: 20px;
        }

        .invitation-card .rsvp-button {
            background-color: #ff6347;
            color: white;
            padding: 15px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.2em;
            transition: background-color 0.3s ease;
        }

        .invitation-card .rsvp-button:hover {
            background-color: #d84e2f; /* Warna gelap saat hover */
        }
    </style>
</head>
<body>

    <!-- Undangan Card -->
    <div class="invitation-card">
        <h1>Selamat Bergabung!</h1>
        <p>Dengan senang hati kami mengundang Anda untuk merayakan acara spesial kami.</p>

        <div class="details">
            <p><strong>Acara:</strong> Pernikahan Eggy & Indah</p>
            <p><strong>Tanggal:</strong> 20 Desember 2024</p>
            <p><strong>Lokasi:</strong> Hotel ABC, Jakarta</p>
        </div>

        <a href="https://www.example.com/rsvp" class="rsvp-button">RSVP Sekarang</a>
    </div>

</body>
</html>
