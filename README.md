<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Catálogo de Vídeos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="catalog">
        <h1>Catálogo de Vídeos</h1>
        <div class="video-container">
            <div class="video-card">
                <video width="320" height="240" controls>
                    <source src="video1.mp4" type="video/mp4">
                    Seu navegador não suporta vídeos.
                </video>
                <h3>Título do Vídeo 1</h3>
            </div>
            <div class="video-card">
                <video width="320" height="240" controls>
                    <source src="video2.mp4" type="video/mp4">
                    Seu navegador não suporta vídeos.
                </video>
                <h3>Título do Vídeo 2</h3>
            </div>
            <div class="video-card">
                <video width="320" height="240" controls>
                    <source src="video3.mp4" type="video/mp4">
                    Seu navegador não suporta vídeos.
                </video>
                <h3>Título do Vídeo 3</h3>
            </div>
        </div>
    </div>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

.catalog {
    max-width: 1200px;
    margin: 50px auto;
    padding: 20px;
    text-align: center;
}

h1 {
    color: #333;
}

.video-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.video-card {
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin: 20px;
    padding: 20px;
    width: 320px;
    text-align: center;
}

h3 {
    color: #555;
}
