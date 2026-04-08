<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Majgo Games</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #0f0f0f;
        color: #e6e6e6;
    }

    header {
        padding: 40px 20px;
        text-align: center;
        background: #1a1a1a;
        border-bottom: 2px solid #333;
    }

    header h1 {
        margin: 0;
        font-size: 2.4rem;
        letter-spacing: 1px;
    }

    header p {
        margin-top: 10px;
        font-size: 1.1rem;
        color: #cfcfcf;
    }

    .content {
        display: flex;
        padding: 30px;
        gap: 40px;
    }

    .sidebar {
        width: 200px;
        min-width: 200px;
    }

    .sidebar h2 {
        margin-top: 0;
        font-size: 1.4rem;
        border-left: 4px solid #4fa3ff;
        padding-left: 10px;
    }

    .games {
        flex: 1;
        display: flex;
        flex-direction: column;
        gap: 20px;
    }

    .game-card {
        background: #1b1b1b;
        padding: 20px;
        border-radius: 8px;
        border: 1px solid #333;
        transition: 0.2s;
    }

    .game-card:hover {
        border-color: #4fa3ff;
        transform: translateY(-3px);
    }

    .game-card h3 {
        margin: 0 0 10px 0;
        font-size: 1.3rem;
    }

    .game-card a {
        color: #4fa3ff;
        text-decoration: none;
        font-weight: bold;
    }

    .game-card a:hover {
        text-decoration: underline;
    }

    @media(max-width: 700px) {
        .content {
            flex-direction: column;
        }
        .sidebar {
            width: 100%;
        }
    }
</style>
</head>

<body>

<header>
    <h1>Majgo Games</h1>
    <p>We create small but polished HTML games — puzzle, RPG, and simulation experiences.</p>
</header>

<div class="content">
    <div class="sidebar">
        <h2>Games</h2>
    </div>

    <div class="games">

        <div class="game-card">
            <h3>Nebula Dash</h3>
            <p>A fast-paced cosmic runner where precision and timing decide your fate.</p>
            <a href="https://majgo.itch.io/nebula-dash" target="_blank">Play on itch.io</a>
        </div>

        <div class="game-card">
            <h3>Rail Recall</h3>
            <p>A logic puzzle where you rearrange rails to guide the train safely to the goal.</p>
            <a href="https://majgo.itch.io/rail-recall" target="_blank">Play on itch.io</a>
        </div>

    </div>
</div>

</body>
</html>
