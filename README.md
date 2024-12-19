<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enquête de Satisfaction - Infographie sur la Gestion des Conflits</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
        }
        label {
            display: block;
            margin-bottom: 10px;
        }
        input[type="text"], input[type="email"], textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .rating input {
            margin-right: 10px;
        }
        .submit-btn {
            display: block;
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 16px;
            cursor: pointer;
        }
        .submit-btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Enquête de Satisfaction - Infographie sur la Gestion des Conflits</h1>
    </header>
    <div class="container">
        <h2>Votre avis compte !</h2>
        <p>Nous vous remercions de prendre quelques minutes pour remplir cette enquête de satisfaction. Vos réponses nous aideront à améliorer nos supports et à mieux répondre à vos attentes.</p>
        <form action="#" method="POST">
            <label for="name">Nom (optionnel)</label>
            <input type="text" id="name" name="name">

            <label for="email">Email (optionnel)</label>
            <input type="email" id="email" name="email">

            <label for="clarity">1. L'infographie était-elle claire et facile à comprendre ?</label>
            <div class="rating">
                <input type="radio" id="clarity-1" name="clarity" value="1"><label for="clarity-1">1</label>
                <input type="radio" id="clarity-2" name="clarity" value="2"><label for="clarity-2">2</label>
                <input type="radio" id="clarity-3" name="clarity" value="3"><label for="clarity-3">3</label>
                <input type="radio" id="clarity-4" name="clarity" value="4"><label for="clarity-4">4</label>
                <input type="radio" id="clarity-5" name="clarity" value="5"><label for="clarity-5">5</label>
            </div>

            <label for="usefulness">2. L'infographie vous a-t-elle semblé utile pour gérer les conflits ?</label>
            <div class="rating">
                <input type="radio" id="usefulness-1" name="usefulness" value="1"><label for="usefulness-1">1</label>
                <input type="radio" id="usefulness-2" name="usefulness" value="2"><label for="usefulness-2">2</label>
                <input type="radio" id="usefulness-3" name="usefulness" value="3"><label for="usefulness-3">3</label>
                <input type="radio" id="usefulness-4" name="usefulness" value="4"><label for="usefulness-4">4</label>
                <input type="radio" id="usefulness-5" name="usefulness" value="5"><label for="usefulness-5">5</label>
            </div>

            <label for="overall">3. Quelle est votre évaluation générale de l'infographie ?</label>
            <div class="rating">
                <input type="radio" id="overall-1" name="overall" value="1"><label for="overall-1">1</label>
                <input type="radio" id="overall-2" name="overall" value="2"><label for="overall-2">2</label>
                <input type="radio" id="overall-3" name="overall" value="3"><label for="overall-3">3</label>
                <input type="radio" id="overall-4" name="overall" value="4"><label for="overall-4">4</label>
                <input type="radio" id="overall-5" name="overall" value="5"><label for="overall-5">5</label>
            </div>

            <label for="comments">4. Avez-vous des suggestions ou commentaires à propos de l'infographie ?</label>
            <textarea id="comments" name="comments" rows="4"></textarea>

            <button type="submit" class="submit-btn">Envoyer votre avis</button>
        </form>
    </div>
</body>
</html>
