# S<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estúdio de Fotografia | Profissionalismo & Criatividade</title>
    <style>
        :root {
            --bg-color: #121212;
            --card-bg: #1e1e1e;
            --text-color: #e0e0e0;
            --accent-color: #d4af37; /* Tom dourado elegante */
            --accent-hover: #f39c12;
            --font-main: 'Helvetica Neue', Arial, sans-serif;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            font-family: var(--font-main);
            line-height: 1.6;
        }

        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1492691527719-9d1e07e534b4?auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }

        header h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            letter-spacing: 2px;
            color: #fff;
        }

        header p {
            font-size: 1.2rem;
            max-width: 600px;
            margin-bottom: 30px;
            color: #ccc;
        }

        .btn {
            background-color: var(--accent-color);
            color: #121212;
            padding: 12px 30px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 4px;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background-color: var(--accent-hover);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 60px 20px;
        }

        section {
            margin-bottom: 60px;
        }

        h2.section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 40px;
            color: #fff;
            position: relative;
        }

        h2.section-title::after {
            content: '';
            display: block;
            width: 60px;
            height: 3px;
            background-color: var(--accent-color);
            margin: 10px auto 0;
        }

        .category-group {
            margin-bottom: 50px;
        }

        .category-group h3 {
            font-size: 1.8rem;
            color: var(--accent-color);
            margin-bottom: 20px;
            border-bottom: 1px solid #333;
            padding-bottom: 10px;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .service-card {
            background-color: var(--card-bg);
            border-radius: 8px;
            padding: 25px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            transition: transform 0.3s ease;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .service-card h4 {
            font-size: 1.3rem;
            margin-bottom: 10px;
            color: #fff;
        }

        .service-card p {
            font-size: 0.95rem;
            color: #aaa;
            margin-bottom: 20px;
        }

        .price {
            font-size: 1.25rem;
            font-weight: bold;
            color: var(--accent-color);
            margin-top: auto;
        }

        footer {
            background-color: #0a0a0a;
            text-align: center;
            padding: 30px;
            color: #777;
            font-size: 0.9rem;
            border-top: 1px solid #222;
        }

        @media (max-width: 768px) {
            header h1 { font-size: 2.5rem; }
            h2.section-title { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Capturamos a Sua Essência</h1>
        <p>Serviços profissionais de fotografia adaptados a cada momento, projeto ou negócio.</p>
        <a href="#precos" class="btn">Ver Preços e Serviços</a>
    </header>

    <div class="container" id="precos">
        <h2 class="section-title">Áreas de Atuação & Tabela de Preços</h2>

        <!-- GRUPO 1 -->
        <div class="category-group">
            <h3>Fotografia Social e Eventos</h3>
            <div class="services-grid">
                <div class="service-card">
                    <h4>Casamentos e Batizados</h4>
                    <p>Registos documentais e retratos autênticos em dias festivos marcantes.</p>
                    <div class="price">Desde 750,00 €</div>
                </div>
                <div class="service-card">
                    <h4>Corporativo e Conferências</h4>
                    <p>Cobertura completa de congressos, feiras empresariais e palestras.</p>
                    <div class="price">Desde 350,00 € / dia</div>
                </div>
                <div class="service-card">
                    <h4>Espetáculos</h4>
                    <p>Fotografia dinâmica de concertos, peças de teatro e eventos desportivos.</p>
                    <div class="price">Desde 200,00 € / evento</div>
                </div>
            </div>
        </div>

        <!-- GRUPO 2 -->
        <div class="category-group">
            <h3>Fotografia Comercial e Publicitária</h3>
            <div class="services-grid">
                <div class="service-card">
                    <h4>Produto (Packshot)</h4>
                    <p>Imagens limpas e detalhadas para lojas online, catálogos e embalagens.</p>
                    <div class="price">Desde 15,00 € / produto</div>
                </div>
                <div class="service-card">
                    <h4>Moda e Editorial</h4>
                    <p>Sessões criativas direcionadas para marcas de roupa, revistas e campanhas publicitárias.</p>
                    <div class="price">Sob Consulta</div>
                </div>
                <div class="service-card">
                    <h4>Culinária (Food)</h4>
                    <p>Fotografia apetitosa de pratos para menus, livros de receitas e redes sociais.</p>
                    <div class="price">Desde 250,00 € / sessão</div>
                </div>
                <div class="service-card">
                    <h4>Imobiliária e Arquitetura</h4>
                    <p>Captação profissional de interiores e exteriores para agências ou arquitetos.</p>
                    <div class="price">Desde 120,00 € / imóvel</div>
                </div>
            </div>
        </div>

        <!-- GRUPO 3 -->
        <div class="category-group">
            <h3>Fotografia de Retrato e Pessoas</h3>
            <div class="services-grid">
                <div class="service-card">
                    <h4>Estúdio / Pessoal</h4>
                    <p>Sessões de família, grávidas, recém-nascidos (newborn) ou retratos individuais.</p>
                    <div class="price">Desde 90,00 €</div>
                </div>
                <div class="service-card">
                    <h4>Retratos Corporativos (Headshots)</h4>
                    <p>Retratos profissionais focados em LinkedIn, sites institucionais e branding pessoal.</p>
                    <div class="price">Desde 60,00 € / pessoa</div>
                </div>
            </div>
        </div>

    </div>

    <footer>
        <p>&copy; 2026 Estúdio de Fotografia. Todos os direitos reservados. (Modo de Rascunho - Não Publicado)</p>
    </footer>

</body>
</html>
ite-fot-grafo-
