<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inscription - Mon E-commerce</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="signup-container">
        <h1>Créez votre compte</h1>
        <form id="signup-form">
            <div class="form-group">
                <label for="username">Nom d'utilisateur</label>
                <input type="text" id="username" name="username" required>
                <div class="error-message" id="username-error"></div>
            </div>

            <div class="form-group">
                <label for="email">Adresse e-mail</label>
                <input type="email" id="email" name="email" required>
                <div class="error-message" id="email-error"></div>
            </div>

            <div class="form-group">
                <label for="password">Mot de passe</label>
                <input type="password" id="password" name="password" required>
                <div class="error-message" id="password-error"></div>
            </div>

            <div class="form-group">
                <label for="confirm-password">Confirmer le mot de passe</label>
                <input type="password" id="confirm-password" name="confirm-password" required>
                <div class="error-message" id="confirm-password-error"></div>
            </div>

            <button type="submit" class="btn-signup">S'inscrire</button>
            <p class="login-link">
                Déjà un compte ? <a href="login.html">Connectez-vous ici</a>
            </p>
        </form>
    </div>

    <script src="script.js"></script>
</body>
</html>
