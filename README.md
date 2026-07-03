<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sphynx d'Amour - Élevage & Adoption de Chats Sphynx en France</title>
    <meta name="description" content="Sphynx d'Amour, élevage familial de chats Sphynx LOOF situé en France. Découvrez nos chatons disponibles à l'adoption.">
    <style>
        :root {
            --rose: #d8a7b1;
            --beige: #f5f0e8;
            --gris: #3a3a3a;
            --blanc: #ffffff;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--gris);
            background: var(--beige);
        }
        header {
            background: var(--blanc);
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky; top: 0; z-index: 100;
        }
        nav {
            max-width: 1200px; margin: 0 auto;
            display: flex; justify-content: space-between; align-items: center;
            padding: 1rem 2rem;
        }
        .logo { font-size: 1.8rem; font-weight: 700; color: var(--rose); }
        .logo span { color: var(--gris); font-weight: 300; }
        nav ul { display: flex; gap: 2rem; list-style: none; }
        nav a { text-decoration: none; color: var(--gris); font-weight: 500; }
        nav a:hover { color: var(--rose); }
        
        .hero {
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url('https://images.unsplash.com/photo-1596854407944-bf87f6fdd49e?q=80&w=2080') center/cover;
            color: var(--blanc);
            text-align: center;
            padding: 8rem 2rem;
        }
        .hero h1 { font-size: 3rem; margin-bottom: 1rem; }
        .hero p { font-size: 1.2rem; margin-bottom: 2rem; }
        .btn {
            background: var(--rose); color: var(--blanc);
            padding: 0.8rem 2rem; border: none; border-radius: 50px;
            text-decoration: none; font-weight: 600; display: inline-block;
            transition: transform 0.2s;
        }
        .btn:hover { transform: translateY(-2px); }
        
        section { max-width: 1200px; margin: 4rem auto; padding: 0 2rem; }
        h2 { text-align: center; font-size: 2.2rem; margin-bottom: 3rem; color: var(--rose); }
        
        .grid {
            display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .card {
            background: var(--blanc); border-radius: 12px; overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.08);
        }
        .card img { width: 100%; height: 250px; object-fit: cover; }
        .card-content { padding: 1.5rem; }
        .card h3 { margin-bottom: 0.5rem; }
        .tag {
            display: inline-block; background: var(--beige); padding: 0.3rem 0.8rem;
            border-radius: 20px; font-size: 0.8rem; margin-bottom: 1rem;
        }
        
        .about {
            background: var(--blanc); border-radius: 12px; padding: 3rem;
            display: flex; gap: 3rem; align-items: center; flex-wrap: wrap;
        }
        .about img { flex: 1; min-width: 300px; border-radius: 12px; }
        .about-text { flex: 2; min-width: 300px; }
        
        form {
            background: var(--blanc); padding: 2rem; border-radius: 12px;
            max-width: 600px; margin: 0 auto;
        }
        .form-group { margin-bottom: 1.5rem; }
        label { display: block; margin-bottom: 0.5rem; font-weight: 600; }
        input, textarea {
            width: 100%; padding: 0.8rem; border: 1px solid #ddd;
            border-radius: 8px; font-family: inherit;
        }
        
        footer {
            background: var(--gris); color: var(--blanc); text-align: center;
            padding: 3rem 2rem; margin-top: 4rem;
        }
        footer a { color: var(--rose); text-decoration: none; }
        
        @media (max-width: 768px) {
            nav ul { display: none; }
            .hero h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Sphynx <span>d'Amour</span></div>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#chatons">Nos Chatons</a></li>
                <li><a href="#elevage">L'Élevage</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="accueil">
        <h1>Bienvenue chez Sphynx d'Amour</h1>
        <p>Élevage familial de chats Sphynx LOOF, situé au cœur de la France</p>
        <a href="#chatons" class="btn">Découvrir nos chatons</a>
    </section>

    <section id="chatons">
        <h2>Chatons Disponibles à l'Adoption</h2>
        <div class="grid">
            <div class="card">
                <img src="https://images.unsplash.com/photo-1606214174585-fe31582dc6ee?q=80&w=1974" alt="Chaton Sphynx mâle">
                <div class="card-content">
                    <span class="tag">Disponible</span>
                    <h3>Apollo</h3>
                    <p><strong>Né le:</strong> 12 Mai 2026<br>
                       <strong>Sexe:</strong> Mâle<br>
                       <strong>Couleur:</strong> Seal point</p>
                    <p>Pucé, vacciné, inscrit au LOOF. Sevré et prêt à rejoindre sa nouvelle famille.</p>
                </div>
            </div>
            <div class="card">
                <img src="https://images.unsplash.com/photo-1574158622682-e40e69881006?q=80&w=2080" alt="Chaton Sphynx femelle">
                <div class="card-content">
                    <span class="tag">Réservée</span>
                    <h3>Luna</h3>
                    <p><strong>Née le:</strong> 28 Avril 2026<br>
                       <strong>Sexe:</strong> Femelle<br>
                       <strong>Couleur:</strong> Blue</p>
                    <p>Caractère câlin et joueur. Partira avec son carnet de santé complet.</p>
                </div>
            <div class="card">
                <img src="https://images.unsplash.com/photo-1592194996308-7b43878e84a6?q=80&w=1974" alt="Chaton Sphynx">
                <div class="card-content">
                    <span class="tag">Option</span>
                    <h3>Néo</h3>
                    <p><strong>Né le:</strong> 12 Mai 2026<br>
                       <strong>Sexe:</strong> Mâle<br>
                       <strong>Couleur:</strong> Black</p>
                    <p>Très sociable, habitué aux enfants. Tests parents HCM et PKD négatifs.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="elevage">
        <h2>Notre Élevage</h2>
        <div class="about">
            <img src="https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?q=80&w=2043" alt="Élevage Sphynx d'Amour">
            <div class="about-text">
                <h3>Un élevage éthique et passionné</h3>
                <p>Sphynx d'Amour est un petit élevage familial déclaré, situé en Normandie, France. Nous sommes signataires de la charte d'élevage LOOF et tous nos reproducteurs sont testés HCM et PKD.</p>
                <p>Nos chatons grandissent à la maison, en liberté, et sont parfaitement sociabilisés avant de rejoindre leur famille pour la vie. Nous attachons une importance capitale à la santé, au caractère et au bien-être de nos Sphynx.</p>
                <p><strong>N° SIRET:</strong> 123 456 789 00012<br>
                   <strong>Affixe LOOF:</strong> Sphynx d'Amour</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Nous Contacter</h2>
        <form onsubmit="event.preventDefault(); alert('Merci ! Nous vous recontacterons très vite.');">
            <div class="form-group">
                <label for="nom">Nom complet</label>
                <input type="text" id="nom" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" required>
            </div>
            <div class="form-group">
                <label for="message">Votre message</label>
                <textarea id="message" rows="5" placeholder="Parlez-nous de votre projet d'adoption..." required></textarea>
            </div>
            <button type="submit" class="btn">Envoyer la demande</button>
        </form>
    </section>

    <footer>
        <p><strong>Sphynx d'Amour</strong> - Élevage de Sphynx LOOF en France</p>
        <p>123 Chemin des Chats, 14000 Caen, Normandie</p>
        <p>Email: contact@sphynxdamour.fr | Tél: 06 12 34 56 78</p>
        <p style="margin-top: 1rem; font-size: 0.8rem;">
            © 2026 Sphynx d'Amour. Tous droits réservés. 
            <a href="#">Mentions légales</a> | <a href="#">Conditions d'adoption</a>
        </p>
    </footer>
</body>
</html>
