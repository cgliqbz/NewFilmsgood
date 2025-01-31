# NewFilmsgood
NewFilmsgood
/movie_website
  /index.html
  /style.css
  /script.js
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Перегляд Фільмів</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Кінотеатр Онлайн</h1>
            <p>Дивись свої улюблені фільми онлайн прямо зараз!</p>
        </div>
    </header>

    <main>
        <div class="movies">
            <div class="movie-card">
                <img src="https://via.placeholder.com/250x375" alt="Фільм 1">
                <h3>Фільм 1</h3>
                <p>Опис фільму 1. Захоплююча історія про...</p>
                <button class="watch-button">Дивитись</button>
            </div>

            <div class="movie-card">
                <img src="https://via.placeholder.com/250x375" alt="Фільм 2">
                <h3>Фільм 2</h3>
                <p>Опис фільму 2. Найкраща комедія року...</p>
                <button class="watch-button">Дивитись</button>
            </div>

            <div class="movie-card">
                <img src="https://via.placeholder.com/250x375" alt="Фільм 3">
                <h3>Фільм 3</h3>
                <p>Опис фільму 3. Драматична історія про...</p>
                <button class="watch-button">Дивитись</button>
            </div>
        </div>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Кінотеатр Онлайн. Всі права захищені.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f9f9f9;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
    text-align: center;
}

header {
    background-color: #1e90ff;
    color: white;
    padding: 30px 0;
}

h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

p {
    font-size: 1.2rem;
}

main {
    padding: 40px 0;
}

.movies {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.movie-card {
    background-color: white;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    width: 250px;
    margin-bottom: 30px;
    padding: 10px;
    text-align: center;
}

.movie-card img {
    width: 100%;
    height: auto;
    border-radius: 5px;
}

h3 {
    font-size: 1.5rem;
    margin: 15px 0;
}

p {
    font-size: 1rem;
    margin-bottom: 15px;
}

button {
    background-color: #1e90ff;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    font-size: 1rem;
}

button:hover {
    background-color: #4682b4;
}

footer {
    background-color: #1e90ff;
    color: white;
    padding: 20px 0;
}
// Слухач події для кнопок "Дивитись"
const watchButtons = document.querySelectorAll('.watch-button');

watchButtons.forEach(button => {
    button.addEventListener('click', function() {
        alert('Перехід до фільму ще не реалізовано. Це просто демонстрація!');
        // Тут можна додати функціональність для перегляду фільму, наприклад, перенаправлення на окрему сторінку або вбудоване відео.
    });
});
