<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio - Joaquin Najt</title>
    <style>
        :root {
            --primary-color: #0ea5e9;
            --secondary-color: #0f172a;
            --bg-light: #f8fafc;
            --text-dark: #334155;
            --text-light: #94a3b8;
            --white: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--bg-light);
            color: var(--text-dark);
            line-height: 1.6;
        }

        header {
            background-color: var(--secondary-color);
            color: var(--white);
            padding: 4rem 2rem;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
            letter-spacing: 1px;
        }

        header h2 {
            font-size: 1.25rem;
            color: var(--primary-color);
            font-weight: 400;
            margin-bottom: 1.5rem;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            flex-wrap: wrap;
            margin-top: 1rem;
        }

        .contact-info a, .contact-info span {
            color: var(--text-light);
            text-decoration: none;
            font-size: 0.95rem;
            display: flex;
            align-items: center;
            gap: 0.5rem;
            transition: color 0.3s ease;
        }

        .contact-info a:hover {
            color: var(--primary-color);
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 3rem 2rem;
        }

        section {
            margin-bottom: 3.5rem;
        }

        h3.section-title {
            font-size: 1.75rem;
            color: var(--secondary-color);
            margin-bottom: 1.5rem;
            position: relative;
            padding-bottom: 0.5rem;
        }

        h3.section-title::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            height: 3px;
            width: 60px;
            background-color: var(--primary-color);
        }

        .card {
            background: var(--white);
            border-radius: 8px;
            padding: 2rem;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
            margin-bottom: 1.5rem;
            transition: transform 0.2s ease;
        }

        .card:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
        }

        .card h4 {
            color: var(--secondary-color);
            font-size: 1.25rem;
            margin-bottom: 0.25rem;
        }

        .card .meta {
            color: var(--primary-color);
            font-size: 0.9rem;
            font-weight: 600;
            margin-bottom: 1rem;
        }

        .profile-text {
            font-size: 1.05rem;
            color: var(--text-dark);
            text-align: justify;
        }

        .crypto-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }

        .crypto-card {
            background: #f1f5f9;
            padding: 1.5rem;
            border-radius: 8px;
            border-left: 4px solid var(--primary-color);
        }

        .crypto-card h5 {
            color: var(--secondary-color);
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
        }

        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .skill-badge {
            background: var(--secondary-color);
            color: var(--white);
            padding: 0.5rem 1.5rem;
            border-radius: 9999px;
            font-weight: 600;
            font-size: 1rem;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
            transition: background 0.3s;
        }
        
        .skill-badge:hover {
            background: var(--primary-color);
        }

        footer {
            text-align: center;
            padding: 2rem;
            background: var(--secondary-color);
            color: var(--text-light);
            font-size: 0.9rem;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2.25rem;
            }
            .contact-info {
                flex-direction: column;
                align-items: center;
                gap: 0.75rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>JOAQUIN NAJT</h1>
        <h2>Economista & Analista Financiero / Crypto</h2>
        <div class="contact-info">
            <span>📍 La Plata, Buenos Aires, Argentina</span>
            <a href="mailto:najtjoaquin6@gmail.com">✉️ najtjoaquin6@gmail.com</a>
            <a href="tel:+542645310311">📞 +54 264 5310311</a>
            <a href="https://linkedin.com" target="_blank">💼 LinkedIn</a>
        </div>
    </header>

    <div class="container">
        
        <section>
            <h3 class="section-title">Perfil Profesional</h3>
            <div class="card">
                <p class="profile-text">
                    Estudiante avanzado de la Licenciatura en Economía (UNLP), con formación en análisis económico y mercados financieros. Participante activo del ecosistema cripto desde 2017. Complemento mi formación académica con trabajo analítico en el Club de Finanzas UNLP, realizando informes de research. Con gran interés en proyectos que combinen finanzas y tecnología.
                </p>
            </div>
        </section>

        <section>
            <h3 class="section-title">Educación</h3>
            <div class="card">
                <h4>Licenciatura en Economía</h4>
                <div class="meta">Universidad Nacional de La Plata (UNLP)</div>
                <p>Estudiante avanzado (3 materias restantes para finalizar).</p>
            </div>
        </section>

        <section>
            <h3 class="section-title">Experiencia Destacada</h3>
            
            <div class="card">
                <h4>Research Renta Variable</h4>
                <div class="meta">Club de Finanzas UNLP | 2024 – 2025</div>
                <p>Análisis de empresas y mercados, elaboración de reportes y seguimiento de drivers macro y micro relevantes para la valuación de activos.</p>
            </div>

            <div class="card">
                <h4>Especialista Crypto y DeFi</h4>
                <div class="meta">2017 – Actualidad</div>
                <p>Participación activa, análisis y operatoria dentro del ecosistema de finanzas descentralizadas. Áreas de enfoque principal:</p>
                
                <div class="crypto-grid">
                    <div class="crypto-card">
                        <h5>💧 Liquidity Pools</h5>
                        <p>Provisión de liquidez, análisis profundo de Impermanent Loss (IL) y optimización de estructuras de fees.</p>
                    </div>
                    <div class="crypto-card">
                        <h5>🏦 Lending & Borrowing</h5>
                        <p>Uso estratégico de mercados de crédito, gestión eficiente de colateral y evaluación rigurosa de riesgos.</p>
                    </div>
                    <div class="crypto-card">
                        <h5>📈 Perpetual Protocols</h5>
                        <p>Operatoria en DEXs de derivados, análisis de funding rates, liquidaciones y dinámica de formación de precios.</p>
                    </div>
                    <div class="crypto-card">
                        <h5>🪙 Tokenomics & Incentivos</h5>
                        <p>Análisis de mecanismos económicos, calendarios de emisiones, staking y modelos de gobernanza descentralizada.</p>
                    </div>
                </div>
            </div>
        </section>

        <section>
            <h3 class="section-title">Hard Skills</h3>
            <div class="skills-container">
                <span class="skill-badge">Power BI</span>
                <span class="skill-badge">SQL</span>
                <span class="skill-badge">Python</span>
                <span class="skill-badge">Excel Avanzado</span>
            </div>
        </section>

    </div>

    <footer>
        <p>&copy; 2026 Joaquin Najt. Portafolio Web.</p>
    </footer>

</body>
</html>
