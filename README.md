# Gaming-zone<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaming Zone</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="top-bar">
            <span>11:49 AM</span>
            <div class="icons">
                <span>4G</span>
                <span>80%</span>
            </div>
        </div>

        <div class="game-card">
            <div class="game-image">
                <img src="game.jpg" alt="Game Image">
                <div class="play-button">▶ Play</div>
            </div>
            <div class="game-info">
                <h2>Gaming Zone</h2>
                <p>Play with the champions</p>
                <div class="rating">⭐ 5.6</div>
                <div class="status-bars">
                    <div class="bar red"></div>
                    <div class="bar green"></div>
                    <div class="bar yellow"></div>
                </div>
                <div class="stats">
                    <div class="stat"><span>Played</span> <span>87</span></div>
                    <div class="stat"><span>Win</span> <span>35</span></div>
                    <div class="stat"><span>Draw</span> <span>09</span></div>
                    <div class="stat"><span>Lost</span> <span>43</span></div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>

CSSbody {
    font-family: Arial, sans-serif;
    background-color: #0b0f1f;
    color: white;
    margin: 0;
    padding: 0;
}

.container {
    width: 90%;
    max-width: 400px;
    margin: auto;
    padding-top: 20px;
}

.top-bar {
    display: flex;
    justify-content: space-between;
    font-size: 14px;
    margin-bottom: 10px;
}

.icons {
    display: flex;
    gap: 10px;
}

.game-card {
    background: #162248;
    border-radius: 15px;
    overflow: hidden;
    padding-bottom: 15px;
}

.game-image {
    position: relative;
}

.game-image img {
    width: 100%;
    display: block;
}

.play-button {
    position: absolute;
    bottom: 10px;
    left: 10px;
    background: rgba(255, 255, 255, 0.2);
    padding: 5px 10px;
    border-radius: 5px;
    cursor: pointer;
}

.game-info {
    padding: 15px;
}

h2 {
    margin: 0;
    font-size: 22px;
}

.rating {
    font-size: 18px;
    color: #e2b714;
    margin-top: 5px;
}

.status-bars {
    display: flex;
    gap: 5px;
    margin: 10px 0;
}

.bar {
    height: 10px;
    flex: 1;
    border-radius: 5px;
}

.red {
    background: red;
}

.green {
    background: green;
}

.yellow {
    background: yellow;
}

.stats {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

.stat {
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid rgba(255, 255, 255, 0.2);
    padding-bottom: 5px;
}
