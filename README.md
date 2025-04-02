<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="HandheldFriendly" content="true">
    <meta name="MobileOptimized" content="width">
    <meta name="theme-color" content="#ff0000">
    <meta name="format-detection" content="telephone=no">
    <title>ChurrasEmo 2° Edição - Aniversário do Kelvym</title>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Rock+Salt&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset otimizado para mobile */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
            -webkit-text-size-adjust: none;
            text-size-adjust: none;
        }

        html {
            width: 100%;
            overflow-x: hidden;
        }

        body {
            font-family: 'Roboto', sans-serif;
            color: white;
            background: url('https://gabriellemoreira.com.br/wp-content/uploads/2025/04/Captura-de-Tela-2025-04-02-as-15.51.04.png') no-repeat center center fixed;
            background-size: cover;
            position: relative;
            min-height: 100vh;
            width: 100%;
            overflow-x: hidden;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
            line-height: 1.4;
        }

        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            z-index: -1;
        }

        .container {
            max-width: 100%;
            width: 100%;
            margin: 0 auto;
            padding: 10px;
            position: relative;
            z-index: 1;
        }

        header {
            text-align: center;
            padding: 15px 5px;
            border-bottom: 2px solid #ff0000;
            margin-bottom: 15px;
            width: 100%;
        }

        h1 {
            font-family: 'Rock Salt', cursive;
            font-size: 1.8rem;
            color: #ff0000;
            text-shadow: 2px 2px 4px #000;
            margin-bottom: 5px;
            word-break: break-word;
            line-height: 1.2;
        }

        h2 {
            font-family: 'Bebas Neue', cursive;
            font-size: 1.5rem;
            color: white;
            text-shadow: 2px 2px 4px #000;
            margin-bottom: 5px;
            line-height: 1.2;
        }

        h3 {
            font-family: 'Bebas Neue', cursive;
            font-size: 1.3rem;
            color: #ff0000;
            margin: 12px 0 5px;
            text-shadow: 1px 1px 2px #000;
            line-height: 1.2;
        }

        .section {
            background-color: rgba(0, 0, 0, 0.7);
            border: 1px solid #333;
            border-radius: 5px;
            padding: 12px;
            margin-bottom: 15px;
            width: 100%;
        }

        ul {
            list-style-type: none;
            padding-left: 15px;
        }

        li {
            margin-bottom: 8px;
            position: relative;
            padding-left: 20px;
            font-size: 0.95rem;
        }

        li:before {
            content: '🎸';
            position: absolute;
            left: 0;
            font-size: 0.8em;
        }

        .beer-info {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 12px 0;
            background-color: rgba(255, 255, 255, 0.1);
            padding: 10px;
            border-radius: 5px;
            gap: 10px;
            width: 100%;
        }

        .beer-info img {
            width: 100%;
            max-width: 120px;
            border-radius: 4px;
        }

        .beer-info div {
            width: 100%;
        }

        .whatsapp-btn {
            display: block;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            border-radius: 25px;
            font-weight: bold;
            margin: 10px auto;
            transition: all 0.3s;
            border: none;
            cursor: pointer;
            font-size: 1rem;
            width: 100%;
            max-width: 280px;
            text-align: center;
        }

        .map-container {
            margin-top: 15px;
            height: 50vh;
            min-height: 200px;
            max-height: 300px;
            border-radius: 5px;
            overflow: hidden;
            box-shadow: 0 0 10px rgba(255, 0, 0, 0.5);
            width: 100%;
        }

        .map-container iframe {
            width: 100%;
            height: 100%;
            border: none;
        }

        .band-list {
            columns: 1;
            column-gap: 15px;
            font-size: 0.9rem;
        }

        .churrasco-img {
            width: 100%;
            max-height: 200px;
            object-fit: cover;
            border-radius: 5px;
            margin: 10px 0;
            box-shadow: 0 0 6px rgba(255, 0, 0, 0.5);
        }

        footer {
            text-align: center;
            padding: 12px 5px;
            margin-top: 20px;
            border-top: 1px solid #ff0000;
            font-size: 0.95rem;
            width: 100%;
        }

        /* Formulário otimizado para mobile */
        .rsvp-form {
            margin-top: 12px;
            background: rgba(0, 0, 0, 0.6);
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #333;
            width: 100%;
        }

        .form-group {
            margin-bottom: 8px;
            width: 100%;
        }

        .form-group label {
            display: block;
            margin-bottom: 3px;
            font-weight: bold;
            font-size: 0.9rem;
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 8px;
            border-radius: 3px;
            border: none;
            background: rgba(255, 255, 255, 0.9);
            font-size: 0.9rem;
        }

        .form-group textarea {
            min-height: 60px;
            resize: vertical;
        }

        .submit-btn {
            background: #ff0000;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 3px;
            font-weight: bold;
            width: 100%;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 1rem;
            margin-top: 5px;
        }

        .flashing {
            animation: flash 2s infinite;
            font-size: 0.9rem;
        }

        @keyframes flash {
            0% { opacity: 1; }
            50% { opacity: 0.5; }
            100% { opacity: 1; }
        }

        .emoji {
            font-size: 1rem;
            vertical-align: middle;
        }

        /* Media Queries específicas para dispositivos pequenos */
        @media only screen and (max-width: 320px) {
            h1 {
                font-size: 1.5rem;
            }
            h2 {
                font-size: 1.3rem;
            }
            .container {
                padding: 8px;
            }
            .section {
                padding: 10px;
            }
        }

        @media only screen and (min-width: 600px) {
            .container {
                max-width: 600px;
                padding: 15px;
            }
            .band-list {
                columns: 2;
            }
            .beer-info {
                flex-direction: row;
            }
        }

        /* Correção específica para Safari iOS */
        @supports (-webkit-touch-callout: none) {
            body {
                height: -webkit-fill-available;
            }
            .container {
                min-height: -webkit-fill-available;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>🎸 CHURRASEMO 2° EDIÇÃO 🎤</h1>
            <h2>ANIVERSÁRIO DO KELVYM + KARAOKÊ ROCK</h2>
            <p class="flashing">Tema: "No palco da minha vida, você é o vocalista!"</p>
        </header>

        <div class="section">
            <h3>📌 O QUE ROLA:</h3>
            <ul>
                <li><strong>CHURRASCO COMPLETO</strong> (cortesia do chef)</li>
                <img src="https://gabriellemoreira.com.br/wp-content/uploads/2025/04/Captura-de-Tela-2025-04-02-as-16.19.07.png" alt="Churrasco" class="churrasco-img">
                <li><strong>KARAOKÊ TEMÁTICO</strong> (prepare suas cordas vocais!)</li>
                <li><strong>PLAYLIST ÉPICA:</strong></li>
            </ul>
            
            <div class="band-list">
                <p>A Skylit Drive, Black Veil Brides, Linkin Park, Marilyn Manson, Bring Me The Horizon, Falling in Reverse, Asking Alexandria, Glória, Rammstein, Iron Maiden, Pantera, Sepultura, Slipknot, Fresno, John Wayne, Bullet For My Valentine, Angra, Suicide Silence, Chelsea Grin, Alesana, Blessthefall, The Offspring, Sum41, Blink182, Of Mice & Men, AFI, Tokyo Hotel, Hawthorne Heights, My Chemical Romance, A Day To Remember, e muito mais!</p>
            </div>
        </div>

        <div class="section">
            <h3>📅 QUANDO:</h3>
            <p><span class="emoji">🗓️</span> <strong>Sábado, 28 de junho</strong></p>
            <p><span class="emoji">⏰</span> <strong>A partir das 11h até as 23h</strong> (12h de festinha!)</p>
        </div>

        <div class="section">
            <h3>📍 ONDE:</h3>
            <p>Rua Dias Leme 281 - BNH - Mesquita (Rocha Sobrinho no GPS) <br>(mesmo local da 1° edição)</p>
            
            <div class="map-container">
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3679.328389422987!2d-43.4009196!3d-22.7786046!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x99642c1e86d033%3A0xa592318537b3d5c0!2sRua%20Dias%20Leme%20281%20-%20BNH%20-%20Mesquita!5e0!3m2!1spt-BR!2sbr!4v1712080000000!5m2!1spt-BR!2sbr" allowfullscreen="" loading="lazy"></iframe>
            </div>
        </div>

        <div class="section">
            <h3>🎯 DRESS CODE:</h3>
            <ul>
                <li><strong>Rockeiro(a) autêntico!</strong> (camisetas de banda, jaqueta de couro, spikes, ou o que achar foda)</li>
                <li><strong>Opcional:</strong> Venha inspirado na sua banda favorita da lista!</li>
            </ul>
        </div>

        <div class="section">
            <h3>📞 CONFIRMAÇÃO:</h3>
            <p>"Bateu o riff da saudade? Me avisa até 25/06!"</p>
            <a href="https://wa.me/5521981304519?text=Pode%20chamar%20o%20EMO!" class="whatsapp-btn">Pode Chamar o EMO!</a>
            
            <div class="rsvp-form">
                <form id="confirmacaoForm">
                    <div class="form-group">
                        <label for="nome">Seu Nome:</label>
                        <input type="text" id="nome" name="nome" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="telefone">Telefone:</label>
                        <input type="tel" id="telefone" name="telefone" required>
                    </div>
                    
                    <div class="form-group">
                        <label for="mensagem">Mensagem (opcional):</label>
                        <textarea id="mensagem" name="mensagem" placeholder="Ex: Vou levar Stella! Ou: Não posso faltar!"></textarea>
                    </div>
                    
                    <button type="submit" class="submit-btn">ENVIAR CONFIRMAÇÃO</button>
                </form>
            </div>
        </div>

        <div class="section">
            <h3>✨ OBS:</h3>
            <div class="beer-info">
                <img src="https://gabriellemoreira.com.br/wp-content/uploads/2025/04/Captura-de-Tela-2025-04-02-as-16.05.15.png" alt="Cervejas Brahma e Stella">
                <div>
                    <p><strong>Tragam um Pack de latão Brahma ou Stella.</strong> Se você tá naqueles momentos difíceis, não deixe de vir, se está recebendo esse convite, você é especial e será muito bem vindo! Não deixem de vir, mesmo se não puder ajudar com a cerveja 🖤 pois eu mesmo já estarei colocando também alguns Pack's</p>
                </div>
            </div>
            <p>"Crianças? Só se souberem o refrão de 'Numb'!" <span class="emoji">😜</span></p>
        </div>

        <footer>
            <p class="flashing">💀 TOQUE FINAL: 23:00hrs (12h de festinha)</p>
            <br>
            <br>
            <p class="text-center"> Developed for https://www.instagram.com/enceladus_market/ por ANDY</p>
        </footer>
    </div>

    <script>
        // Efeito de digitação para o título
        document.addEventListener('DOMContentLoaded', function() {
            const titles = document.querySelectorAll('h1, h2, h3');
            
            titles.forEach(title => {
                const text = title.textContent;
                title.textContent = '';
                
                let i = 0;
                const typingEffect = setInterval(() => {
                    if (i < text.length) {
                        title.textContent += text.charAt(i);
                        i++;
                    } else {
                        clearInterval(typingEffect);
                    }
                }, 100);
            });
            
            // Máscara para telefone otimizada para mobile
            const phoneInput = document.getElementById('telefone');
            phoneInput.addEventListener('input', function(e) {
                let numbers = this.value.replace(/\D/g, '');
                if (numbers.length > 11) numbers = numbers.substring(0, 11);
                
                // Formatar como (XX) XXXXX-XXXX
                let formatted = '';
                if (numbers.length > 0) {
                    formatted = '(' + numbers.substring(0, 2);
                }
                if (numbers.length > 2) {
                    formatted += ') ' + numbers.substring(2, 7);
                }
                if (numbers.length > 7) {
                    formatted += '-' + numbers.substring(7, 11);
                }
                
                this.value = formatted;
            });

            // Envio do formulário
            document.getElementById('confirmacaoForm').addEventListener('submit', function(e) {
                e.preventDefault();
                
                const nome = document.getElementById('nome').value;
                const telefone = document.getElementById('telefone').value;
                const mensagem = document.getElementById('mensagem').value;
                
                // Formatar a mensagem para o WhatsApp
                let textoWhatsApp = `*Confirmacao para o ChurrasEmo!*%0A%0A`;
                textoWhatsApp += `*Nome:* ${encodeURIComponent(nome)}%0A`;
                textoWhatsApp += `*Telefone:* ${encodeURIComponent(telefone)}%0A`;
                
                if (mensagem) {
                    textoWhatsApp += `*Mensagem:* ${encodeURIComponent(mensagem)}%0A`;
                }
                
                textoWhatsApp += `%0A_Enviado pelo formulário de confirmação_`;
                
                // Abrir WhatsApp com os dados
                window.open(`https://wa.me/5521981304519?text=${textoWhatsApp}`, '_blank');
                
                // Limpar formulário (opcional)
                this.reset();
            });
        });
    </script>
</body>
</html>
