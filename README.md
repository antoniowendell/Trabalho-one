# Trabalho-one
Comando usado:
Crie uma página pessoal simples e elegante no formato de currículo em HTML/CSS para impressão.
Dados necessários:
- Nome: Antônio Wendell da Costa de Araujo
- Idade: 18 anos
- Curso: Licenciatura em Matemática
Use uma estrutura limpa, com tipografia profissional (Helvetica/Arial), cores sóbrias (cinza escuro e azul petróleo), uma linha de destaque lateral nos títulos e espaçamento adequado para um visual minimalista e direto.


código 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo - Antônio Wendell da Costa de Araujo</title>
    <style>
        /* Configurações Gerais e Reset */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        body {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            color: #333333;
            background-color: #fcfcfc;
            margin: 0;
            padding: 40px 20px;
            line-height: 1.6;
        }

        /* Container Principal (Simula uma folha A4 centralizada) */
        .resume-container {
            max-width: 800px;
            margin: 0 auto;
            background: #ffffff;
            padding: 50px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
            border-radius: 4px;
        }

        /* Cabeçalho */
        .header {
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 20px;
            margin-bottom: 35px;
        }

        h1 {
            font-size: 26pt;
            color: #2c3e50;
            margin: 0 0 8px 0;
            font-weight: 700;
            letter-spacing: -0.5px;
        }

        .info-tag {
            font-size: 12pt;
            color: #7f8c8d;
            margin: 0;
            font-weight: 400;
        }

        /* Seções do Currículo */
        .section {
            margin-bottom: 35px;
        }

        h2 {
            font-size: 14pt;
            color: #2c3e50;
            margin: 0 0 15px 0;
            border-left: 4px solid #34495e;
            padding-left: 10px;
            text-transform: uppercase;
            letter-spacing: 0.8px;
        }

        p {
            margin: 0 0 10px 0;
            color: #555555;
            font-size: 11.5pt;
        }

        .highlight {
            font-weight: 600;
            color: #2c3e50;
        }

        /* Otimização para Impressão */
        @media print {
            body {
                background-color: #ffffff;
                padding: 0;
            }
            .resume-container {
                box-shadow: none;
                padding: 0;
                max-width: 100%;
            }
        }
    </style>
</head>
<body>

    <div class="resume-container">
        <header class="header">
            <h1>Antônio Wendell da Costa de Araujo</h1>
            <p class="info-tag">Brasileiro • 18 anos</p>
        </header>

        <section class="section">
            <h2>Formação Acadêmica</h2>
            <p>Graduando em <span class="highlight">Licenciatura em Matemática</span></p>
        </section>

        <section class="section">
            <h2>Objetivo</h2>
            <p>Desenvolvimento acadêmico e profissional na área de educação matemática, buscando oportunidades para aplicação prática dos conhecimentos adquiridos.</p>
        </section>
    </div>

</body>
</html>
<img width="953" height="1312" alt="1000011932" src="https://github.com/user-attachments/assets/315a38c0-af43-4039-a76d-52a04f1ea182" />

