<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marcelinium Inc</title>
    <link rel="stylesheet" href="styles.css">
    <style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #ffffff;
    }
    
    .navbar {
        display: flex;
        align-items: center;
        background-color: #000000;
        padding: 10px;
    }
    
    .menu-button, .news-button, .games-button, .search-button {
        background-color: #000000;
        color: #ffffff;
        border: none;
        padding: 10px;
        cursor: pointer;
        margin-right: 10px;
        border-radius: 5px;
        border: center;
    }
    
    .search-input {
        padding: 10px;
        border: none;
        border-radius: 5px;
        flex-grow: 1;
    }
    
    .main-content {
        display: flex;
        align-items: center;
        justify-content: center;
        height: calc(100vh - 60px);
        background-color: #ffffff;
    }
    
    h1 {
        font-size: 48px;
        font-weight: bold;
        color: #000000;
        background-color: #000000;
        color: #ffffff;
        padding: 20px;
        border-radius: 10px;
    }
    </style>
</head>
<body>
    <div class="navbar">
        <button class="menu-button">Home</button>
        <button class="news-button">News</button>
        <button class="games-button">Games</button>
        <input type="text" placeholder="Search" class="search-input">
        <button class="search-button">🔍</button>
    </div>
    <div class="main-content">
        <h1>Marcelinium Inc</h1>
    </div>
</body>
</html>
