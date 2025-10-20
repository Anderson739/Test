<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Portefeuille - Gestion des Paiements</title>
    <link rel="stylesheet" href="css/style.css"> 
</head>
<body>

    <header>
        <div class="logo">
            <a href="index.html">🛍️ **Mon E-shop**</a>
        </div>
        <nav>
            <ul>
                <li><a href="index.html">Accueil</a></li>
                <li><a href="shop.html">Produits</a></li>
                <li><a href="account.html" class="active">Mon Compte</a></li> 
            </ul>
        </nav>
        <div class="panier">
            <a href="panier.html">🛒 Panier (2)</a>
        </div>
    </header>

    <main class="wallet-page">
        <h1>💳 Mon Portefeuille</h1>

        <div class="account-dashboard">
            <aside class="account-sidebar">
                <ul>
                    <li><a href="account.html">Profil</a></li>
                    <li><a href="orders.html">Mes Commandes</a></li>
                    <li><a href="wallet.html" class="active">Portefeuille</a></li>
                    <li><a href="adresses.html">Adresses de Livraison</a></li>
                </ul>
            </aside>

            <section class="wallet-content">
                
                <div class="balance-card">
                    <h2>Solde du Compte</h2>
                    <p class="current-balance">**15,50 €**</p>
                    <button class="add-credit-btn">Ajouter des Crédits</button>
                </div>

                <div class="payment-methods">
                    <h2>Méthodes de Paiement</h2>
                    
                    <div class="method-card">
                        <span class="card-info">**Visa** - se terminant par **4242**</span>
                        <span class="expiry-date">Expire 12/26</span>
                        <div class="actions">
                            <button class="default-btn active">Défaut</button>
                            <button class="remove-btn">Supprimer</button>
                        </div>
                    </div>
                    
                    <div class="method-card">
                        <span class="card-info">**Mastercard** - se terminant par **1010**</span>
                        <span class="expiry-date">Expire 08/2
