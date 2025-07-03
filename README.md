# swinn99!DOCTYPE html
html lang=en
head
    meta charset=UTF-8
    meta name=viewport content=width=device-width, initial-scale=1.0
    titleGame Websitetitle
    link rel=stylesheet href=style.css
head
body
    div class=container
        h1Game Websiteh1
        div class=game-controls
            button id=roll-diceRoll Dicebutton
            div id=dice-resultdiv
        div
        div class=game-result
            h2Result span id=resultspanh2
        div
    div
    script src=script.jsscript
body
html
[Uploaddocument.getElementById('roll-dice').addEventListener('click', function() {
    // Tạo số ngẫu nhiên từ 1 đến 6
    let diceRoll = Math.floor(Math.random() * 6) + 1;

    // Hiển thị kết quả
    document.getElementById('dice-result').textContent = 'You rolled: ' + diceRoll;
    document.getElementById('result').textContent = 'You rolled a ' + diceRoll + '!';
});
ing script.js…]()
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    text-align: center;
}

.container {
    max-width: 600px;
    margin: 50px auto;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

button {
    padding: 15px 30px;
    font-size: 16px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

.game-result {
    margin-top: 30px;
    font-size: 24px;
}
