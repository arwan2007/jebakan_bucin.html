# jebakan_bucin.html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jebakan Bucin</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffe6e6;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #ff3366;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #ff3366;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff6699;
        }
    </style>
</head>
<body>
    <h1>Hai Sayang! 💖</h1>
    <p>Aku punya pertanyaan penting buat kamu!</p>
    <button onclick="jebakan()">Klik di sini</button>

    <script>
        function jebakan() {
            alert("Apapun jawabanmu, aku tetap sayang kamu selamanya! 🥰💕");
            document.body.innerHTML = `
                <h1>Aku Sayang Kamu! 💘</h1>
                <p>Kamu itu alasan kenapa hariku selalu ceria.</p>
                <p>Terima kasih sudah ada di hidupku. 😘</p>
            `;
        }
    </script>
</body>
</html>
