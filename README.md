<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Yully 💖</title>

<style>
    body {
        margin: 0;
        padding: 0;
        font-family: 'Segoe UI', sans-serif;
        background: linear-gradient(135deg, #ff4e8a, #ff9acb);
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        color: white;
        overflow: hidden;
    }

    .card {
        background: rgba(0, 0, 0, 0.5);
        padding: 40px;
        border-radius: 20px;
        max-width: 600px;
        box-shadow: 0 0 30px rgba(0,0,0,0.4);
        animation: fadeIn 2s ease-in-out;
    }

    h1 {
        font-size: 2.5rem;
        margin-bottom: 20px;
    }

    p {
        font-size: 1.2rem;
        line-height: 1.7;
    }

    .heart {
        font-size: 2rem;
        animation: pulse 1.5s infinite;
    }

    button {
        margin-top: 20px;
        padding: 12px 25px;
        font-size: 1rem;
        border: none;
        border-radius: 30px;
        background: #ff2e63;
        color: white;
        cursor: pointer;
        transition: 0.3s;
    }

    button:hover {
        background: #ff004c;
        transform: scale(1.1);
    }

    @keyframes pulse {
        0% { transform: scale(1); }
        50% { transform: scale(1.2); }
        100% { transform: scale(1); }
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
    }
</style>
</head>

<body>

<div class="card">
    <h1>Happy Valentine’s Day, Yully 💖</h1>

    <p>
        From the first moment I met you, I knew you were different.  
        You’re not just someone I like… you’re someone I see in my future.
    </p>

    <p>
        I love you till the day that I die.  
        No games. No pretending. Just real love.
    </p>

    <p>
        This little website is just a small piece of how much you mean to me.
    </p>

    <div class="heart">❤️</div>

    <button onclick="playMusic()">Play Our Song 🎶</button>

    <audio id="bgMusic" loop>
        <source src="PUT_YOUR_MP3_LINK_HERE.mp3" type="audio/mpeg">
    </audio>
</div>

<script>
function playMusic() {
    document.getElementById("bgMusic").play();
}
</script>

</body>
</html>