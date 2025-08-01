<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Universe - Catálogo del Futuro</title>
    <link rel="icon" type="image/png" href="images/logo.png">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@300;400;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-glow: #00ffff;
            --secondary-glow: #ff006e;
            --accent-glow: #8338ec;
            --warning-glow: #ff9f00;
            --success-glow: #06ffa5;
            --bg-dark: #0a0a0a;
            --bg-card: rgba(15, 15, 30, 0.9);
            --text-primary: #ffffff;
            --text-secondary: #a0a0a0;
            --footer-bg: #0f1428;
            --footer-text: #ffffff;
        }

        body {
            font-family: 'Rajdhani', sans-serif;
            background: linear-gradient(135deg, #0f1428, #0a0f1c, #000510);
            background-size: cover;
            background-attachment: fixed;
            color: var(--text-primary);
            overflow-x: hidden;
            position: relative;
            min-height: 100vh;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Admin Panel Styles */
        .admin-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.95);
            z-index: 10001;
            display: none;
            align-items: center;
            justify-content: center;
        }

        .admin-login {
            background: linear-gradient(135deg, var(--bg-card), rgba(10, 10, 30, 0.95));
            border: 2px solid var(--primary-glow);
            border-radius: 25px;
            padding: 40px;
            text-align: center;
            backdrop-filter: blur(20px);
            box-shadow: 0 0 50px rgba(0, 255, 255, 0.5);
        }

        .admin-login h2 {
            font-family: 'Orbitron', monospace;
            color: var(--primary-glow);
            margin-bottom: 30px;
            font-size: 2rem;
        }

        .admin-input {
            width: 300px;
            padding: 15px;
            margin: 10px 0;
            border: 2px solid rgba(255, 255, 255, 0.2);
            border-radius: 15px;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            font-size: 16px;
            outline: none;
        }

        .admin-input:focus {
            border-color: var(--primary-glow);
            box-shadow: 0 0 20px rgba(0, 255, 255, 0.3);
        }

        .admin-btn {
            background: linear-gradient(45deg, var(--primary-glow), var(--accent-glow));
            border: none;
            padding: 15px 30px;
            border-radius: 25px;
            color: white;
            font-weight: 700;
            cursor: pointer;
            margin: 10px;
            transition: all 0.3s ease;
        }

        .admin-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(0, 255, 255, 0.4);
        }

        .admin-panel {
            position: fixed;
            top: 10px;
            left: 10px;
            background: var(--bg-card);
            border: 2px solid var(--primary-glow);
            border-radius: 15px;
            padding: 20px;
            backdrop-filter: blur(20px);
            display: none;
            z-index: 10000;
        }

        .admin-controls {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        /* Edit Modal Styles */
        .edit-modal {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.9);
            z-index: 10002;
            display: none;
            align-items: center;
            justify-content: center;
        }

        .edit-modal-content {
            background: var(--bg-card);
            border: 2px solid var(--primary-glow);
            border-radius: 25px;
            padding: 30px;
            width: 90%;
            max-width: 600px;
            max-height: 80vh;
            overflow-y: auto;
            backdrop-filter: blur(20px);
        }

        .edit-form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .form-group {
            display: flex;
            flex-direction: column;
            gap: 5px;
        }

        .form-group label {
            color: var(--primary-glow);
            font-weight: 700;
        }

        .form-group input, .form-group textarea, .form-group select {
            padding: 10px;
            border: 2px solid rgba(255, 255, 255, 0.2);
            border-radius: 10px;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            outline: none;
        }

        .form-group input:focus, .form-group textarea:focus, .form-group select:focus {
            border-color: var(--primary-glow);
        }

        /* Loading Screen - MEJORADA */
        .loading-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, #0a0a0a, #1a0033, #000814);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 10000;
            transition: opacity 0.8s ease, visibility 0.8s ease;
        }

        .loading-screen.hidden {
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
        }

        .loading-logo {
            width: 150px;
            height: 150px;
            border-radius: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            animation: loadingPulse 2s ease-in-out infinite;
            margin-bottom: 30px;
        }

        .loading-logo::before {
            content: "🚀";
            font-size: 80px;
            animation: rotate 2s linear infinite;
        }

        @keyframes loadingPulse {
            0%, 100% { 
                transform: scale(1);
                filter: drop-shadow(0 0 30px rgba(0, 255, 255, 0.5));
            }
            50% { 
                transform: scale(1.1);
                filter: drop-shadow(0 0 50px rgba(255, 0, 110, 0.8));
            }
        }

        @keyframes rotate {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        /* Texto de carga ILUMINADO - CORREGIDO */
        .loading-text {
            font-family: 'Orbitron', monospace;
            font-size: 2.5rem;
            font-weight: 900;
            background: linear-gradient(45deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow));
            background-size: 200% auto;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 20px;
            animation: textShine 2s ease-in-out infinite alternate;
            text-shadow: 0 0 30px rgba(0, 255, 255, 0.8);
            /* Fallback para navegadores que no soportan background-clip */
            color: var(--primary-glow);
        }

        @keyframes textShine {
            0% { 
                background-position: 0% center;
                filter: brightness(1);
                text-shadow: 0 0 30px rgba(0, 255, 255, 0.8);
            }
            100% { 
                background-position: 200% center;
                filter: brightness(1.5);
                text-shadow: 0 0 50px rgba(255, 0, 110, 0.9);
            }
        }

        .loading-bar {
            width: 350px;
            height: 6px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 3px;
            overflow: hidden;
            position: relative;
            border: 1px solid rgba(0, 255, 255, 0.3);
        }

        .loading-progress {
            height: 100%;
            background: linear-gradient(90deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow));
            border-radius: 3px;
            animation: loadingProgress 3.5s ease-in-out forwards;
            box-shadow: 0 0 15px rgba(0, 255, 255, 0.6);
        }

        @keyframes loadingProgress {
            0% { width: 0%; }
            20% { width: 15%; }
            40% { width: 35%; }
            60% { width: 60%; }
            80% { width: 85%; }
            100% { width: 100%; }
        }

        .loading-subtitle {
            font-size: 1.2rem;
            color: var(--primary-glow);
            margin-top: 15px;
            animation: fadeInOut 2s ease-in-out infinite alternate;
            text-shadow: 0 0 20px rgba(0, 255, 255, 0.6);
        }

        @keyframes fadeInOut {
            0% { opacity: 0.6; }
            100% { opacity: 1; }
        }

        /* Main content */
        .main-content {
            opacity: 0;
            transition: opacity 1s ease-in-out;
        }

        .main-content.visible {
            opacity: 1;
        }

        /* Interactive Particles */
        .particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .particle {
            position: absolute;
            width: 3px;
            height: 3px;
            background: var(--primary-glow);
            border-radius: 50%;
            animation: float 20s infinite linear;
            box-shadow: 0 0 15px var(--primary-glow);
        }

        @keyframes float {
            0% {
                transform: translateY(100vh) translateX(0) rotate(0deg);
                opacity: 0;
            }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% {
                transform: translateY(-10vh) translateX(100px) rotate(360deg);
                opacity: 0;
            }
        }

        /* Enhanced Floating Contact Hub - CORREGIDO Y MEJORADO */
        .floating-contact-hub {
            position: fixed;
            top: 20px;
            right: 20px;
            z-index: 1000;
            display: flex;
            flex-direction: column;
            gap: 12px;
            align-items: flex-end;
        }

        .contact-main-btn {
            background: linear-gradient(135deg, var(--secondary-glow), var(--accent-glow), var(--primary-glow));
            background-size: 200% 200%;
            border: none;
            border-radius: 20px;
            padding: 6px 14px;
            color: white;
            font-family: 'Orbitron', monospace;
            font-weight: 700;
            font-size: 11px;
            cursor: pointer;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 6px;
            box-shadow: 0 0 20px rgba(255, 0, 110, 0.4);
            transition: all 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .contact-main-btn:hover {
            transform: scale(1.05) translateY(-2px);
            box-shadow: 0 0 30px rgba(255, 0, 110, 0.6);
        }

        .contact-icon {
            font-size: 12px;
        }

        .contact-text {
            font-weight: 700;
            font-size: 11px;
        }

        /* Quick Action Buttons - Hover MÁS ESPECÍFICO y botones mejorados */
        .quick-actions {
            display: flex;
            flex-direction: column;
            gap: 8px;
            opacity: 0;
            transform: translateX(50px);
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            pointer-events: none;
        }

        .floating-contact-hub:hover .quick-actions {
            opacity: 1;
            transform: translateX(0);
            pointer-events: auto;
        }

        .quick-action-btn {
            width: 35px;
            height: 35px;
            border-radius: 50%;
            border: none;
            color: white;
            font-size: 16px;
            cursor: pointer;
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            position: relative;
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
        }

        /* Botones sociales MEJORADOS con iconos más reconocibles */
        .whatsapp-btn {
            background: linear-gradient(135deg, #25D366, #128C7E);
            box-shadow: 0 0 15px rgba(37, 211, 102, 0.4);
        }

        .whatsapp-btn:before {
            content: "💬";
            font-size: 18px;
        }

        .whatsapp-btn:hover {
            transform: scale(1.2) rotate(15deg);
            box-shadow: 0 0 25px rgba(37, 211, 102, 0.7);
        }

        .instagram-btn {
            background: linear-gradient(135deg, #E4405F, #833AB4, #F77737);
            box-shadow: 0 0 15px rgba(228, 64, 95, 0.4);
        }

        .instagram-btn:before {
            content: "📸";
            font-size: 18px;
        }

        .instagram-btn:hover {
            transform: scale(1.2) rotate(-15deg);
            box-shadow: 0 0 25px rgba(228, 64, 95, 0.7);
        }

        .tiktok-btn {
            background: linear-gradient(135deg, #000000, #ff0050);
            box-shadow: 0 0 15px rgba(255, 0, 80, 0.4);
        }

        .tiktok-btn:before {
            content: "🎬";
            font-size: 18px;
        }

        .tiktok-btn:hover {
            transform: scale(1.2) rotate(15deg);
            box-shadow: 0 0 25px rgba(255, 0, 80, 0.7);
        }

        .email-btn {
            background: linear-gradient(135deg, #1e88e5, #1565c0);
            box-shadow: 0 0 15px rgba(30, 136, 229, 0.4);
        }

        .email-btn:before {
            content: "✉️";
            font-size: 18px;
        }

        .email-btn:hover {
            transform: scale(1.2) rotate(-15deg);
            box-shadow: 0 0 25px rgba(30, 136, 229, 0.7);
        }

        /* Ocultar texto de los botones rápidos */
        .quick-action-btn span {
            display: none;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 15px;
            position: relative;
            z-index: 10;
            padding-bottom: 0;
        }

        /* Header */
        .header {
            text-align: center;
            margin-bottom: 50px;
            padding: 100px 20px 50px;
            min-height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: relative;
            overflow: hidden;
        }

        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: radial-gradient(circle at center, rgba(0, 255, 255, 0.1), transparent 70%);
            animation: headerGlow 8s ease-in-out infinite alternate;
        }

        @keyframes headerGlow {
            0% { opacity: 0.3; transform: scale(1); }
            100% { opacity: 0.6; transform: scale(1.1); }
        }

        .main-title {
            font-family: 'Orbitron', monospace;
            font-size: clamp(2.5rem, 8vw, 7rem);
            font-weight: 900;
            background: linear-gradient(45deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow));
            background-size: 200% auto;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: textShine 3s ease-in-out infinite alternate;
            margin-bottom: 25px;
            text-shadow: 0 0 50px rgba(0, 255, 255, 0.5);
            line-height: 1.1;
            position: relative;
            z-index: 2;
        }

        .subtitle {
            font-size: clamp(1.4rem, 4vw, 2rem);
            font-weight: 600;
            background: linear-gradient(45deg, #00ffff, #ff006e, #8338ec);
            background-size: 200% auto;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: fadeInUp 1s ease 0.5s forwards, subtitleGlow 4s ease-in-out 1.5s infinite alternate;
            text-shadow: 0 0 20px rgba(0, 255, 255, 0.3);
            opacity: 0;
            position: relative;
            z-index: 2;
        }

        @keyframes subtitleGlow {
            0% { 
                background-position: 0% center;
                filter: brightness(1);
            }
            100% { 
                background-position: 200% center;
                filter: brightness(1.3);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Enhanced Search */
        .search-container {
            position: relative;
            margin-bottom: 50px;
            padding: 0 15px;
        }

        .search-wrapper {
            position: relative;
            max-width: 700px;
            margin: 0 auto;
        }

        .search-input {
            width: 100%;
            padding: 18px 60px 18px 25px;
            font-size: 18px;
            border: 2px solid transparent;
            border-radius: 60px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(15px);
            color: white;
            outline: none;
            transition: all 0.4s ease;
            font-family: 'Rajdhani', sans-serif;
            font-weight: 600;
        }

        .search-input::placeholder {
            color: rgba(255, 255, 255, 0.6);
        }

        .search-input:focus {
            border-color: var(--primary-glow);
            box-shadow: 0 0 40px rgba(0, 255, 255, 0.6);
            transform: scale(1.02);
        }

        .search-icon {
            position: absolute;
            right: 25px;
            top: 50%;
            transform: translateY(-50%);
            color: var(--primary-glow);
            font-size: 20px;
            animation: searchPulse 2s infinite;
        }

        @keyframes searchPulse {
            0%, 100% { opacity: 0.7; }
            50% { opacity: 1; }
        }

        /* Enhanced Filter Tags */
        .filter-tags {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 50px;
            flex-wrap: wrap;
            padding: 0 15px;
        }

        .filter-tag {
            padding: 12px 20px;
            background: linear-gradient(135deg, rgba(0, 255, 255, 0.2), rgba(131, 56, 236, 0.2));
            border: 2px solid transparent;
            border-radius: 25px;
            color: white;
            cursor: pointer;
            transition: all 0.4s ease;
            font-weight: 700;
            backdrop-filter: blur(15px);
            font-size: 16px;
            text-align: center;
            min-width: fit-content;
            position: relative;
            overflow: hidden;
            background-clip: padding-box;
        }

        .filter-tag::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(135deg, var(--primary-glow), var(--accent-glow));
            opacity: 0;
            transition: opacity 0.3s ease;
            border-radius: 25px;
            z-index: -1;
        }

        .filter-tag:hover::before, .filter-tag.active::before {
            opacity: 1;
        }

        .filter-tag:hover, .filter-tag.active {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0, 255, 255, 0.3);
            border-color: var(--primary-glow);
        }

        /* Testimonials - Better mobile layout */
        .testimonials-section {
            background: linear-gradient(135deg, rgba(0, 255, 255, 0.1), rgba(255, 0, 110, 0.1));
            border-radius: 30px;
            padding: 40px 20px;
            margin: 60px 0;
            backdrop-filter: blur(20px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            position: relative;
            overflow: hidden;
        }

        .testimonials-section::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: conic-gradient(from 0deg, transparent, rgba(0, 255, 255, 0.1), transparent);
            animation: rotate 20s linear infinite;
            z-index: -1;
        }

        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        .testimonials-header {
            text-align: center;
            margin-bottom: 40px;
        }

        .testimonials-title {
            font-family: 'Orbitron', monospace;
            font-size: clamp(1.8rem, 5vw, 2.5rem);
            font-weight: 700;
            color: var(--primary-glow);
            text-shadow: 0 0 20px var(--primary-glow);
            margin-bottom: 20px;
        }

        .testimonials-subtitle {
            font-size: clamp(1rem, 3vw, 1.4rem);
            font-weight: 600;
            background: linear-gradient(45deg, #00ffff, #ff006e, #8338ec);
            background-size: 200% auto;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: subtitleGlow 4s ease-in-out infinite alternate;
        }

        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-bottom: 30px;
        }

        .testimonial-card {
            background: rgba(0, 0, 0, 0.4);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 25px;
            backdrop-filter: blur(15px);
            transition: all 0.4s ease;
            position: relative;
        }

        .testimonial-card:hover {
            transform: translateY(-10px);
            border-color: var(--primary-glow);
            box-shadow: 0 20px 40px rgba(0, 255, 255, 0.2);
        }

        .testimonial-text {
            font-style: italic;
            font-size: 1rem;
            margin-bottom: 20px;
            color: #fff;
            line-height: 1.6;
        }

        .testimonial-author {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .author-avatar {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            background: linear-gradient(45deg, var(--primary-glow), var(--secondary-glow));
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.3rem;
            font-weight: bold;
            flex-shrink: 0;
        }

        .author-info h4 {
            color: var(--primary-glow);
            margin-bottom: 5px;
            font-size: 1rem;
        }

        .author-info .stars {
            color: #ffd700;
            font-size: 1.1rem;
        }

        /* Add Comment Section */
        .add-comment-section {
            margin-top: 40px;
            text-align: center;
        }

        .add-comment-btn {
            background: linear-gradient(45deg, var(--success-glow), var(--primary-glow));
            border: none;
            padding: 15px 30px;
            border-radius: 25px;
            color: white;
            font-weight: 700;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s ease;
        }

        .add-comment-btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 25px rgba(6, 255, 165, 0.4);
        }

        .comment-form {
            display: none;
            background: var(--bg-card);
            border: 2px solid var(--primary-glow);
            border-radius: 25px;
            padding: 30px;
            margin-top: 20px;
            backdrop-filter: blur(20px);
            text-align: left;
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            color: var(--primary-glow);
            margin-bottom: 8px;
            font-weight: 700;
        }

        .form-group input, .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 2px solid rgba(255, 255, 255, 0.2);
            border-radius: 15px;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            outline: none;
            font-family: 'Rajdhani', sans-serif;
        }

        .form-group input:focus, .form-group textarea:focus {
            border-color: var(--primary-glow);
        }

        .star-rating {
            display: flex;
            gap: 5px;
        }

        .star {
            font-size: 1.5rem;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .star:hover, .star.selected {
            color: #ffd700;
            transform: scale(1.2);
        }

        .form-actions {
            display: flex;
            gap: 15px;
            margin-top: 25px;
        }

        .btn {
            padding: 12px 25px;
            border: none;
            border-radius: 25px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .btn-primary {
            background: linear-gradient(45deg, var(--primary-glow), var(--accent-glow));
            color: white;
        }

        .btn-secondary {
            background: transparent;
            color: var(--text-secondary);
            border: 2px solid var(--text-secondary);
        }

        .btn:hover {
            transform: translateY(-3px);
        }

        /* Enhanced Mobile Responsiveness */
        @media (max-width: 768px) {
            .floating-contact {
                top: 10px;
                right: 10px;
                padding: 10px 16px;
                font-size: 12px;
                gap: 6px;
            }

            .header {
                padding: 60px 15px 30px;
                min-height: 40vh;
            }

            .main-title {
                font-size: clamp(1.8rem, 6vw, 3rem);
                margin-bottom: 15px;
            }

            .subtitle {
                font-size: clamp(1rem, 3vw, 1.4rem);
            }

            .services-grid {
                grid-template-columns: 1fr;
                gap: 15px;
            }

            .service-card {
                padding: 15px;
            }

            .service-header {
                flex-direction: column;
                align-items: flex-start;
                gap: 8px;
            }

            .service-name {
                font-size: 1.2rem;
                min-width: auto;
            }

            .service-price {
                font-size: 1.4rem;
            }

            .service-actions {
                flex-direction: column;
                gap: 8px;
            }

            .service-btn {
                min-width: auto;
                padding: 12px 20px;
                font-size: 15px;
            }

            .filter-tags {
                gap: 8px;
                padding: 0 15px;
            }

            .filter-tag {
                padding: 6px 12px;
                font-size: 12px;
            }

            .category-header {
                gap: 10px;
            }

            .category-title {
                font-size: clamp(1.5rem, 4vw, 2rem);
            }

            .features-grid {
                grid-template-columns: 1fr;
                gap: 15px;
            }

            .feature-card {
                padding: 25px 15px;
            }

            .testimonials-grid {
                grid-template-columns: 1fr;
                gap: 15px;
            }

            .testimonial-card {
                padding: 20px;
            }

            .search-input {
                padding: 12px 45px 12px 15px;
                font-size: 15px;
            }

            .search-icon {
                right: 15px;
                font-size: 16px;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 10px;
            }

            .header {
                padding: 50px 10px 25px;
                min-height: 35vh;
            }

            .search-container,
            .category-section {
                padding: 0 5px;
            }

            .service-tags {
                gap: 6px;
            }

            .service-tag {
                padding: 3px 8px;
                font-size: 10px;
            }
        }

        /* Features Showcase */
        .features-showcase {
            margin: 80px 0;
            text-align: center;
            padding: 0 15px;
        }

        .features-title {
            font-family: 'Orbitron', monospace;
            font-size: clamp(2rem, 5vw, 3rem);
            font-weight: 700;
            color: var(--accent-glow);
            margin-bottom: 50px;
            text-shadow: 0 0 30px var(--accent-glow);
        }

        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .feature-card {
            background: rgba(0, 0, 0, 0.6);
            border: 2px solid rgba(255, 255, 255, 0.1);
            border-radius: 25px;
            padding: 40px 25px;
            transition: all 0.5s ease;
            backdrop-filter: blur(20px);
            position: relative;
            overflow: hidden;
        }

        .feature-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(131, 56, 236, 0.1), transparent);
            transition: left 0.8s ease;
        }

        .feature-card:hover::before {
            left: 100%;
        }

        .feature-card:hover {
            transform: translateY(-20px);
            border-color: var(--accent-glow);
            box-shadow: 0 30px 60px rgba(131, 56, 236, 0.4);
        }

        .feature-icon {
            font-size: 4rem;
            margin-bottom: 25px;
            display: block;
            animation: iconFloat 4s ease-in-out infinite;
        }

        @keyframes iconFloat {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
        }

        .feature-title {
            font-size: 1.5rem;
            font-weight: 700;
            color: var(--primary-glow);
            margin-bottom: 20px;
            font-family: 'Orbitron', monospace;
        }

        .feature-description {
            color: var(--text-secondary);
            line-height: 1.7;
            font-size: 1rem;
        }

        /* Service Categories */
        .category-section {
            margin-bottom: 60px;
            opacity: 0;
            animation: slideInUp 0.8s ease forwards;
            padding: 0 15px;
        }

        .category-section:nth-child(even) {
            animation-delay: 0.2s;
        }

        .category-section:nth-child(odd) {
            animation-delay: 0.4s;
        }

        @keyframes slideInUp {
            from {
                opacity: 0;
                transform: translateY(50px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Category Header */
        .category-header {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 20px;
            margin-bottom: 40px;
            cursor: pointer;
            transition: all 0.4s ease;
            flex-wrap: wrap;
            text-align: center;
            position: relative;
        }

        .category-header::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 0;
            height: 0;
            background: radial-gradient(circle, rgba(0, 255, 255, 0.15), transparent);
            transition: all 0.5s ease;
            border-radius: 50%;
        }

        .category-header:hover::before {
            width: 150px;
            height: 150px;
        }

        .category-header:hover {
            transform: scale(1.02);
        }

        .category-title {
            font-family: 'Orbitron', monospace;
            font-size: clamp(2rem, 5vw, 3rem);
            font-weight: 700;
            color: var(--primary-glow);
            text-shadow: 0 0 30px var(--primary-glow);
            position: relative;
            z-index: 2;
        }

        .category-icon {
            font-size: clamp(2.5rem, 5vw, 3.5rem);
            animation: iconFloat 4s ease-in-out infinite;
            position: relative;
            z-index: 2;
        }

        /* Service Grid */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 25px;
            margin-bottom: 50px;
        }

        .service-card {
            background: var(--bg-card);
            border: 2px solid rgba(255, 255, 255, 0.1);
            border-radius: 25px;
            padding: 25px;
            cursor: pointer;
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            backdrop-filter: blur(25px);
            position: relative;
            overflow: hidden;
        }

        .service-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.1), transparent);
            transition: left 0.8s ease;
        }

        .service-card:hover::before {
            left: 100%;
        }

        .service-card:hover {
            transform: translateY(-15px) scale(1.02);
            border-color: var(--primary-glow);
            box-shadow: 0 25px 50px rgba(0, 255, 255, 0.3);
        }

        /* Enhanced service tags */
        .service-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 20px;
        }

        .service-tag {
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            animation: tagFloat 3s ease-in-out infinite;
        }

        .tag-popular {
            background: linear-gradient(45deg, #ff9f00, #ff6b35);
            color: white;
            animation: tagGlow 2s ease-in-out infinite alternate;
        }

        .tag-recommended {
            background: linear-gradient(45deg, #06ffa5, #00d4aa);
            color: white;
        }

        .tag-premium {
            background: linear-gradient(45deg, #8338ec, #3d52a0);
            color: white;
        }

        .tag-bestseller {
            background: linear-gradient(45deg, #ff006e, #c77dff);
            color: white;
        }

        .tag-exclusive {
            background: linear-gradient(45deg, #00ffff, #0066cc);
            color: white;
        }

        .tag-value {
            background: linear-gradient(45deg, #32cd32, #228b22);
            color: white;
        }

        @keyframes tagGlow {
            0% { box-shadow: 0 0 10px rgba(255, 159, 0, 0.6); }
            100% { box-shadow: 0 0 25px rgba(255, 159, 0, 0.9); }
        }

        @keyframes tagFloat {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-3px); }
        }

        .service-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 20px;
            flex-wrap: wrap;
            gap: 15px;
        }

        .service-name {
            font-size: 1.4rem;
            font-weight: 700;
            color: white;
            flex: 1;
            min-width: 200px;
            font-family: 'Orbitron', monospace;
        }

        .service-price {
            font-family: 'Orbitron', monospace;
            font-size: 1.8rem;
            font-weight: 900;
            color: var(--success-glow);
            text-shadow: 0 0 15px var(--success-glow);
            white-space: nowrap;
        }

        .service-features {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.6s ease, padding 0.4s ease;
            opacity: 0;
        }

        .service-card.expanded .service-features {
            max-height: 500px;
            padding: 25px 0;
            opacity: 1;
        }

        .feature-list {
            list-style: none;
            margin-bottom: 25px;
        }

        .feature-item {
            padding: 8px 0;
            color: var(--text-secondary);
            position: relative;
            padding-left: 30px;
            font-size: 1rem;
            line-height: 1.5;
            transition: all 0.3s ease;
        }

        .feature-item::before {
            content: '✓';
            position: absolute;
            left: 0;
            color: var(--success-glow);
            font-weight: bold;
            font-size: 1.2rem;
        }

        .feature-item:hover {
            color: var(--text-primary);
            padding-left: 35px;
        }

        .service-actions {
            display: flex;
            gap: 12px;
            margin-top: 25px;
            flex-wrap: wrap;
        }

        .service-btn {
            padding: 12px 25px;
            border: none;
            border-radius: 30px;
            font-family: 'Rajdhani', sans-serif;
            font-weight: 700;
            font-size: 15px;
            cursor: pointer;
            transition: all 0.4s ease;
            text-decoration: none;
            display: flex;
            align-items: center;
            gap: 8px;
            flex: 1;
            justify-content: center;
            min-width: 140px;
        }

        .service-btn-primary {
            background: linear-gradient(45deg, var(--primary-glow), var(--accent-glow));
            color: white;
        }

        .service-btn-secondary {
            background: transparent;
            color: var(--primary-glow);
            border: 2px solid var(--primary-glow);
        }

        .service-btn:hover:not(.service-btn-coming-soon) {
            transform: translateY(-3px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
        }

        .service-btn-primary:hover {
            box-shadow: 0 15px 40px rgba(0, 255, 255, 0.5);
        }

        /* Enhanced Footer */
        .footer {
            background: linear-gradient(135deg, var(--footer-bg) 0%, #0a0f1c 50%, #000510 100%);
            color: var(--footer-text);
            padding: 80px 0 40px;
            margin-top: 100px;
            position: relative;
            overflow: hidden;
        }

        .footer::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 6px;
            background: linear-gradient(90deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow), var(--primary-glow));
            background-size: 300% 100%;
            animation: gradientFlow 4s ease infinite;
        }

        @keyframes gradientFlow {
            0%, 100% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
        }

        .footer-content {
            max-width: 1400px;
            margin: 0 auto;
            padding: 0 30px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: start;
        }

        .footer-brand {
            display: flex;
            align-items: flex-start;
            gap: 30px;
        }

        .footer-logo {
            width: 120px;
            height: 120px;
            border-radius: 30px;
            background: transparent;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
            position: relative;
        }

        .footer-logo img {
            width: 120px;
            height: 120px;
            filter: drop-shadow(0 0 25px rgba(0, 255, 255, 0.5));
            z-index: 1;
            position: relative;
        }

        .footer-info h3 {
            font-family: 'Orbitron', monospace;
            font-size: 2.5rem;
            font-weight: 900;
            background: linear-gradient(45deg, var(--primary-glow), var(--secondary-glow));
            background-size: 200% auto;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: textShine 3s ease-in-out infinite alternate;
            margin-bottom: 20px;
            text-shadow: 0 0 40px rgba(0, 255, 255, 0.5);
        }

        .footer-description {
            font-size: 1.2rem;
            color: #c8d5f2;
            line-height: 1.8;
            margin-bottom: 30px;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
        }

        .footer-social {
            display: flex;
            gap: 25px;
            margin-bottom: 25px;
        }

        .social-link {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-decoration: none;
            font-size: 1.5rem;
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            backdrop-filter: blur(15px);
            border: 2px solid rgba(255, 255, 255, 0.1);
            position: relative;
            overflow: hidden;
        }

        .social-link::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: inherit;
            border-radius: inherit;
            filter: blur(15px);
            z-index: -1;
            opacity: 0.8;
        }

        /* Footer social buttons MEJORADOS */
        .social-instagram {
            background: linear-gradient(135deg, #E4405F, #833AB4, #F77737);
            box-shadow: 0 0 40px rgba(228, 64, 95, 0.5);
        }

        .social-instagram:before {
            content: "📸";
            font-size: 1.8rem;
        }

        .social-instagram:hover {
            transform: translateY(-8px) scale(1.15);
            box-shadow: 0 20px 50px rgba(228, 64, 95, 0.7);
        }

        .social-tiktok {
            background: linear-gradient(135deg, #000000, #ff0050);
            box-shadow: 0 0 40px rgba(255, 0, 80, 0.5);
        }

        .social-tiktok:before {
            content: "🎬";
            font-size: 1.8rem;
        }

        .social-tiktok:hover {
            transform: translateY(-8px) scale(1.15);
            box-shadow: 0 20px 50px rgba(255, 0, 80, 0.7);
        }

        .social-whatsapp {
            background: linear-gradient(135deg, #25D366, #128C7E);
            box-shadow: 0 0 40px rgba(37, 211, 102, 0.5);
        }

        .social-whatsapp:before {
            content: "💬";
            font-size: 1.8rem;
        }

        .social-whatsapp:hover {
            transform: translateY(-8px) scale(1.15);
            box-shadow: 0 20px 50px rgba(37, 211, 102, 0.7);
        }

        /* Ocultar texto de botones sociales del footer */
        .social-link span {
            display: none;
        }

        .footer-contact {
            text-align: left;
        }

        .footer-contact h4 {
            font-family: 'Orbitron', monospace;
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(45deg, var(--accent-glow), var(--secondary-glow));
            background-size: 200% auto;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: textShine 4s ease-in-out infinite alternate;
            margin-bottom: 35px;
            text-shadow: 0 0 25px rgba(131, 56, 236, 0.5);
        }

        .contact-methods {
            display: flex;
            flex-direction: column;
            gap: 30px;
        }

        .contact-item {
            background: rgba(255, 255, 255, 0.05);
            border: 2px solid rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 25px;
            transition: all 0.5s ease;
            backdrop-filter: blur(20px);
            position: relative;
            overflow: hidden;
        }

        .contact-item::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.1), transparent);
            transition: left 0.8s ease;
        }

        .contact-item:hover::before {
            left: 100%;
        }

        .contact-item:hover {
            transform: translateY(-5px);
            border-color: var(--primary-glow);
            box-shadow: 0 20px 40px rgba(0, 255, 255, 0.3);
            background: rgba(255, 255, 255, 0.08);
        }

        .contact-header {
            display: flex;
            align-items: center;
            gap: 20px;
            margin-bottom: 12px;
        }

        .contact-icon {
            width: 45px;
            height: 45px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.3rem;
            flex-shrink: 0;
        }

        .contact-icon.email {
            background: linear-gradient(135deg, #1e88e5, #1565c0);
            box-shadow: 0 0 25px rgba(30, 136, 229, 0.4);
        }

        .contact-icon.whatsapp {
            background: linear-gradient(135deg, #25D366, #128C7E);
            box-shadow: 0 0 25px rgba(37, 211, 102, 0.4);
        }

        .contact-title {
            font-size: 1.3rem;
            font-weight: 700;
            color: var(--primary-glow);
            margin: 0;
        }

        .contact-info {
            margin-left: 65px;
        }

        .contact-link {
            color: #c8d5f2;
            text-decoration: none;
            font-size: 1.1rem;
            transition: all 0.4s ease;
            display: inline-block;
        }

        .contact-link:hover {
            color: var(--primary-glow);
            text-shadow: 0 0 15px var(--primary-glow);
            transform: translateX(8px);
        }

        .contact-description {
            color: #9aacce;
            font-size: 1rem;
            margin-top: 10px;
            line-height: 1.5;
        }

        .footer-bottom {
            margin-top: 60px;
            padding-top: 40px;
            border-top: 2px solid rgba(255, 255, 255, 0.1);
            text-align: center;
            background: linear-gradient(135deg, rgba(0, 0, 0, 0.4), rgba(15, 20, 40, 0.4));
            border-radius: 25px;
            padding: 30px;
            backdrop-filter: blur(15px);
        }

        .footer-bottom-text {
            color: #8aa4d3;
            font-size: 1rem;
            font-weight: 500;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
        }

        .footer-brand-highlight {
            color: var(--primary-glow);
            font-weight: 700;
            text-shadow: 0 0 15px var(--primary-glow);
        }

        /* Enhanced Mobile Responsiveness */
        @media (max-width: 768px) {
            .floating-contact-hub {
                top: 15px;
                right: 15px;
                gap: 10px;
            }

            .contact-main-btn {
                padding: 6px 12px;
                font-size: 10px;
                gap: 5px;
            }

            .contact-icon {
                font-size: 11px;
            }

            .quick-action-btn {
                width: 30px;
                height: 30px;
                font-size: 12px;
            }

            .header {
                padding: 80px 15px 40px;
                min-height: 50vh;
            }

            .main-title {
                font-size: clamp(2rem, 6vw, 4rem);
                margin-bottom: 20px;
            }

            .subtitle {
                font-size: clamp(1.2rem, 3vw, 1.6rem);
            }

            .search-input {
                padding: 15px 50px 15px 20px;
                font-size: 16px;
            }

            .filter-tag {
                padding: 10px 16px;
                font-size: 14px;
            }

            .services-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .service-card {
                padding: 20px;
            }

            .service-header {
                flex-direction: column;
                align-items: flex-start;
                gap: 10px;
            }

            .service-name {
                font-size: 1.2rem;
                min-width: auto;
            }

            .service-price {
                font-size: 1.6rem;
            }

            .service-actions {
                flex-direction: column;
                gap: 10px;
            }

            .service-btn {
                min-width: auto;
                padding: 12px 20px;
                font-size: 14px;
            }

            .category-header {
                gap: 15px;
            }

            .category-title {
                font-size: clamp(1.6rem, 4vw, 2.5rem);
            }

            .features-grid {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .feature-card {
                padding: 30px 20px;
            }

            .footer-content {
                grid-template-columns: 1fr;
                gap: 50px;
                text-align: center;
            }

            .footer-brand {
                justify-content: center;
                flex-direction: column;
                align-items: center;
                text-align: center;
            }

            .footer-contact {
                text-align: center;
            }

            .contact-item {
                text-align: left;
            }

            .footer-logo {
                width: 100px;
                height: 100px;
            }

            .footer-logo img {
                width: 100px;
                height: 100px;
            }

            .footer-info h3 {
                font-size: 2rem;
            }

            .footer-social {
                justify-content: center;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 10px;
            }

            .header {
                padding: 60px 10px 30px;
                min-height: 40vh;
            }

            .search-container,
            .category-section {
                padding: 0 5px;
            }

            .service-tags {
                gap: 8px;
            }

            .service-tag {
                padding: 4px 10px;
                font-size: 11px;
            }

            .footer-content {
                padding: 0 15px;
            }

            .footer-logo {
                width: 80px;
                height: 80px;
            }

            .footer-logo img {
                width: 80px;
                height: 80px;
            }

            .contact-methods {
                gap: 20px;
            }

            .contact-item {
                padding: 20px;
            }

            .floating-contact-hub {
                top: 10px;
                right: 10px;
            }

            .contact-main-btn {
                padding: 5px 10px;
                font-size: 9px;
            }

            .quick-action-btn {
                width: 28px;
                height: 28px;
                font-size: 11px;
            }
        }
    </style>
</head>
<body>
    <!-- Admin Access Button -->
    <div style="position: fixed; bottom: 10px; left: 10px; z-index: 9999;">
        <button onclick="showAdminLogin()" style="background: rgba(0,0,0,0.7); color: white; border: none; padding: 5px 10px; border-radius: 5px; font-size: 12px; cursor: pointer;">Admin</button>
    </div>

    <!-- Admin Login Overlay -->
    <div class="admin-overlay" id="adminOverlay">
        <div class="admin-login">
            <h2>🔐 Acceso Administrativo</h2>
            <input type="password" class="admin-input" id="adminPassword" placeholder="Contraseña de administrador">
            <br>
            <button class="admin-btn" onclick="checkAdminPassword()">Ingresar</button>
            <button class="admin-btn" onclick="hideAdminLogin()">Cancelar</button>
        </div>
    </div>

    <!-- Admin Panel -->
    <div class="admin-panel" id="adminPanel">
        <h3 style="color: var(--primary-glow); margin-bottom: 15px;">Panel Admin</h3>
        <div class="admin-controls">
            <button class="admin-btn" onclick="addService()">➕ Agregar Servicio</button>
            <button class="admin-btn" onclick="editServices()">✏️ Editar Servicios</button>
            <button class="admin-btn" onclick="manageComments()">💬 Gestionar Comentarios</button>
            <button class="admin-btn" onclick="logoutAdmin()">🚪 Cerrar Sesión</button>
        </div>
    </div>

    <!-- Edit Service Modal -->
    <div class="edit-modal" id="editModal">
        <div class="edit-modal-content">
            <h3 style="color: var(--primary-glow); margin-bottom: 20px;">Editar Servicio</h3>
            <form class="edit-form" id="editForm">
                <div class="form-group">
                    <label for="editServiceName">Nombre del Servicio:</label>
                    <input type="text" id="editServiceName" required>
                </div>
                <div class="form-group">
                    <label for="editServicePrice">Precio:</label>
                    <input type="text" id="editServicePrice" required>
                </div>
                <div class="form-group">
                    <label for="editServiceCategory">Categoría:</label>
                    <select id="editServiceCategory" required>
                        <option value="streaming">Streaming</option>
                        <option value="musica">Música</option>
                        <option value="ia">Inteligencia Artificial</option>
                        <option value="otros">Otros Servicios</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="editServiceFeatures">Características (una por línea):</label>
                    <textarea id="editServiceFeatures" rows="8" required></textarea>
                </div>
                <div class="form-group">
                    <label for="editServiceTags">Tags (separados por comas):</label>
                    <input type="text" id="editServiceTags" placeholder="popular, recommended, premium">
                </div>
                <div class="form-actions">
                    <button type="button" class="btn btn-primary" onclick="saveServiceEdit()">💾 Guardar Cambios</button>
                    <button type="button" class="btn btn-secondary" onclick="closeEditModal()">❌ Cancelar</button>
                </div>
            </form>
        </div>
    </div>

    <!-- Add Service Modal -->
    <div class="edit-modal" id="addModal">
        <div class="edit-modal-content">
            <h3 style="color: var(--primary-glow); margin-bottom: 20px;">Agregar Nuevo Servicio</h3>
            <form class="edit-form" id="addForm">
                <div class="form-group">
                    <label for="addServiceName">Nombre del Servicio:</label>
                    <input type="text" id="addServiceName" required>
                </div>
                <div class="form-group">
                    <label for="addServicePrice">Precio:</label>
                    <input type="text" id="addServicePrice" required>
                </div>
                <div class="form-group">
                    <label for="addServiceCategory">Categoría:</label>
                    <select id="addServiceCategory" required>
                        <option value="streaming">Streaming</option>
                        <option value="musica">Música</option>
                        <option value="ia">Inteligencia Artificial</option>
                        <option value="otros">Otros Servicios</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="addServiceFeatures">Características (una por línea):</label>
                    <textarea id="addServiceFeatures" rows="8" required></textarea>
                </div>
                <div class="form-group">
                    <label for="addServiceTags">Tags (separados por comas):</label>
                    <input type="text" id="addServiceTags" placeholder="popular, recommended, premium">
                </div>
                <div class="form-actions">
                    <button type="button" class="btn btn-primary" onclick="saveNewService()">✨ Crear Servicio</button>
                    <button type="button" class="btn btn-secondary" onclick="closeAddModal()">❌ Cancelar</button>
                </div>
            </form>
        </div>
    </div>

    <!-- Comments Management Modal -->
    <div class="edit-modal" id="commentsModal">
        <div class="edit-modal-content">
            <h3 style="color: var(--primary-glow); margin-bottom: 20px;">Gestión de Comentarios</h3>
            <div id="commentsList">
                <!-- Comments will be populated here -->
            </div>
            <div class="form-actions">
                <button type="button" class="btn btn-secondary" onclick="closeCommentsModal()">❌ Cerrar</button>
            </div>
        </div>
    </div>

    <!-- Loading Screen -->
    <div class="loading-screen" id="loadingScreen">
        <div class="loading-logo"></div>
        <div class="loading-text">DIGITAL UNIVERSE</div>
        <div class="loading-bar">
            <div class="loading-progress"></div>
        </div>
        <div class="loading-subtitle">Cargando el futuro digital...</div>
    </div>

    <!-- Main Content -->
    <div class="main-content" id="mainContent">
        <!-- Interactive Particles Background -->
        <div class="particles" id="particles"></div>

        <div class="container">
            <!-- Header with Parallax Effect -->
            <div class="header">
                <h1 class="main-title">DIGITAL UNIVERSE</h1>
                <p class="subtitle">🚀 Tus plataformas favoritas están aquí 🌟</p>
            </div>

            <!-- Enhanced Search -->
            <div class="search-container">
                <div class="search-wrapper">
                    <input type="text" class="search-input" id="searchInput" placeholder="Busca tu servicio digital ideal...">
                    <span class="search-icon">🔍</span>
                </div>
            </div>

            <!-- Enhanced Filter Tags -->
            <div class="filter-tags">
                <div class="filter-tag active" data-category="all">Todos</div>
                <div class="filter-tag" data-category="streaming">Streaming</div>
                <div class="filter-tag" data-category="musica">Música</div>
                <div class="filter-tag" data-category="ia">IA</div>
                <div class="filter-tag" data-category="otros">Otros Servicios</div>
            </div>

            <!-- Features Showcase -->
            <div class="features-showcase">
                <h2 class="features-title">✨ Experiencia Premium ✨</h2>
                <div class="features-grid">
                    <div class="feature-card">
                        <span class="feature-icon">💰</span>
                        <h3 class="feature-title">Mejores Precios</h3>
                        <p class="feature-description">Precios increíbles que no encontrarás en otro lugar. Ahorra hasta 80% vs precios oficiales.</p>
                    </div>
                    <div class="feature-card">
                        <span class="feature-icon">🎯</span>
                        <h3 class="feature-title">Soporte 24/7</h3>
                        <p class="feature-description">Equipo de soporte disponible siempre. Respuesta inmediata a todas tus consultas.</p>
                    </div>
                    <div class="feature-card">
                        <span class="feature-icon">🎁</span>
                        <h3 class="feature-title">Combos Especiales</h3>
                        <p class="feature-description">Descuentos exclusivos al combinar servicios. Más servicios, más ahorro.</p>
                    </div>
                </div>
            </div>

            <!-- Testimonials Section -->
            <div class="testimonials-section">
                <div class="testimonials-header">
                    <h2 class="testimonials-title">💬 Lo Que Dicen Nuestros Clientes 💬</h2>
                    <p class="testimonials-subtitle">Testimonios auténticos de usuarios reales</p>
                </div>
                <div class="testimonials-grid" id="testimonialsGrid">
                    <div class="testimonial-card">
                        <p class="testimonial-text">"Increíble servicio! Netflix funcionando perfecto por meses. Precio súper accesible y entrega inmediata. 100% recomendado!"</p>
                        <div class="testimonial-author">
                            <div class="author-avatar">M</div>
                            <div class="author-info">
                                <h4>María González</h4>
                                <div class="stars">⭐⭐⭐⭐⭐</div>
                            </div>
                        </div>
                    </div>
                    <div class="testimonial-card">
                        <p class="testimonial-text">"Spotify Premium funcionando de maravilla. El soporte es excelente, responden súper rápido. Ya llevo 6 meses sin problemas."</p>
                        <div class="testimonial-author">
                            <div class="author-avatar">C</div>
                            <div class="author-info">
                                <h4>Carlos Ruiz</h4>
                                <div class="stars">⭐⭐⭐⭐⭐</div>
                            </div>
                        </div>
                    </div>
                    <div class="testimonial-card">
                        <p class="testimonial-text">"ChatGPT Plus a precio increíble! La IA funciona perfecta, todas las funciones disponibles. Mejor que comprarlo oficial."</p>
                        <div class="testimonial-author">
                            <div class="author-avatar">A</div>
                            <div class="author-info">
                                <h4>Ana Morales</h4>
                                <div class="stars">⭐⭐⭐⭐⭐</div>
                            </div>
                        </div>
                    </div>
                    <div class="testimonial-card">
                        <p class="testimonial-text">"Office 365 completo por una fracción del precio oficial. Todas las aplicaciones funcionando al 100%. Excelente inversión!"</p>
                        <div class="testimonial-author">
                            <div class="author-avatar">J</div>
                            <div class="author-info">
                                <h4>Juan Pérez</h4>
                                <div class="stars">⭐⭐⭐⭐⭐</div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Add Comment Section -->
                <div class="add-comment-section" style="display: none;">
                    <button class="add-comment-btn" onclick="toggleCommentForm()">
                        ✨ Agregar Tu Testimonio ✨
                    </button>
                    
                    <div class="comment-form" id="commentForm">
                        <div class="form-group">
                            <label for="userName">Tu Nombre:</label>
                            <input type="text" id="userName" placeholder="Escribe tu nombre...">
                        </div>
                        
                        <div class="form-group">
                            <label for="userComment">Tu Experiencia:</label>
                            <textarea id="userComment" rows="4" placeholder="Cuéntanos sobre tu experiencia con nuestros servicios..."></textarea>
                        </div>
                        
                        <div class="form-group">
                            <label>Tu Calificación:</label>
                            <div class="star-rating" id="starRating">
                                <span class="star" data-rating="1">⭐</span>
                                <span class="star" data-rating="2">⭐</span>
                                <span class="star" data-rating="3">⭐</span>
                                <span class="star" data-rating="4">⭐</span>
                                <span class="star" data-rating="5">⭐</span>
                            </div>
                        </div>
                        
                        <div class="form-actions">
                            <button class="btn btn-primary" onclick="submitComment()">
                                🚀 Publicar Testimonio
                            </button>
                            <button class="btn btn-secondary" onclick="toggleCommentForm()">
                                ❌ Cancelar
                            </button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Service Categories -->
            <div id="servicesContainer">
                <!-- Services will be populated by JavaScript -->
            </div>
        </div>

        <style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
  font-family: 'Rajdhani', sans-serif;
  background: linear-gradient(135deg, #0f1428, #0a0f1c, #000510);
  background-size: cover;
  background-attachment: fixed;
  color: var(--text-primary);
  overflow-x: hidden;
  position: relative;
  min-height: 100vh;
}

    .footer {
        width: 100%;
        background: linear-gradient(135deg, 
            rgba(10, 10, 26, 0.98) 0%, 
            rgba(26, 26, 46, 0.99) 25%,
            rgba(22, 33, 62, 0.98) 50%,
            rgba(15, 32, 39, 0.99) 75%,
            rgba(10, 10, 26, 0.98) 100%);
        backdrop-filter: blur(30px);
        border-top: 3px solid transparent;
        border-image: linear-gradient(90deg, 
            transparent 0%, 
            #00ffff 20%, 
            #ff0080 40%, 
            #8000ff 60%, 
            #00ff80 80%,
            transparent 100%) 1;
        position: relative;
        overflow: hidden;
        padding: 100px 0 50px 0;
    }

    .footer::before,
.footer::after {
  display: none !important;
}

    @keyframes cosmicPulse {
        0%, 100% { 
            opacity: 0.4; 
            transform: scale(1);
        }
        25% { 
            opacity: 0.8; 
            transform: scale(1.02);
        }
        50% { 
            opacity: 0.6; 
            transform: scale(1.01);
        }
        75% { 
            opacity: 0.9; 
            transform: scale(1.03);
        }
    }

    @keyframes dataStream {
        0% { transform: translateX(-100%); }
        100% { transform: translateX(100vw); }
    }

    .footer-content {
        max-width: 1500px;
        margin: 0 auto;
        padding: 0 30px;
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 100px;
        align-items: center;
        position: relative;
        z-index: 2;
    }

    /* BRAND SECTION ULTRA FUTURISTA */
    .footer-brand {
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        position: relative;
    }

    .footer-brand::before {
        content: '';
        position: absolute;
        top: -50px;
        left: 50%;
        transform: translateX(-50%);
        width: 200px;
        height: 200px;
        background: radial-gradient(circle, rgba(0, 255, 255, 0.2) 0%, transparent 70%);
        border-radius: 50%;
        animation: haloExpand 4s ease-in-out infinite;
        z-index: -1;
    }

    @keyframes haloExpand {
        0%, 100% { 
            transform: translateX(-50%) scale(0.8);
            opacity: 0.3;
        }
        50% { 
            transform: translateX(-50%) scale(1.2);
            opacity: 0.8;
        }
    }

    .footer-logo {
        display: flex;
        align-items: center;
        justify-content: center;
        position: relative;
        font-size: 140px;
        margin-bottom: 40px;
        animation: logoLevitate 5s ease-in-out infinite;
        filter: drop-shadow(0 0 50px rgba(0, 255, 255, 0.8));
    }

    .footer-logo::after {
        content: "🚀";
        display: block;
        animation: rocketOrbit 4s linear infinite;
        filter: 
            drop-shadow(0 0 60px rgba(0, 255, 255, 1)) 
            drop-shadow(0 0 100px rgba(255, 0, 128, 0.8)) 
            drop-shadow(0 0 140px rgba(128, 0, 255, 0.6))
            drop-shadow(0 0 180px rgba(0, 255, 128, 0.4));
    }

    @keyframes logoLevitate {
        0%, 100% { 
            transform: translateY(0px) scale(1) rotate(0deg);
        }
        25% { 
            transform: translateY(-20px) scale(1.08) rotate(2deg);
        }
        50% { 
            transform: translateY(-10px) scale(1.05) rotate(0deg);
        }
        75% { 
            transform: translateY(-25px) scale(1.1) rotate(-2deg);
        }
    }

    @keyframes rocketOrbit {
        0% { transform: rotate(0deg) translateX(20px) rotate(0deg); }
        25% { transform: rotate(90deg) translateX(25px) rotate(-90deg); }
        50% { transform: rotate(180deg) translateX(30px) rotate(-180deg); }
        75% { transform: rotate(270deg) translateX(25px) rotate(-270deg); }
        100% { transform: rotate(360deg) translateX(20px) rotate(-360deg); }
    }

    .footer-info h3 {
        font-family: 'Orbitron', monospace;
        font-size: 3.2rem;
        font-weight: 900;
        background: linear-gradient(135deg, 
            #00ffff 0%, 
            #ff0080 25%, 
            #8000ff 50%, 
            #00ff80 75%, 
            #ff8000 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
        background-size: 200% 200%;
        animation: rainbowShift 3s ease-in-out infinite, titleMegaGlow 4s ease-in-out infinite;
        margin-bottom: 30px;
        letter-spacing: 4px;
        text-transform: uppercase;
        position: relative;
    }

    .footer-info h3::after {
        content: '';
        position: absolute;
        bottom: -10px;
        left: 50%;
        transform: translateX(-50%);
        width: 80%;
        height: 3px;
        background: linear-gradient(90deg, transparent, #00ffff, #ff0080, #8000ff, transparent);
        animation: underlineGlow 2s ease-in-out infinite;
    }

    @keyframes rainbowShift {
        0%, 100% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
    }

    @keyframes titleMegaGlow {
        0%, 100% { 
            filter: drop-shadow(0 0 20px rgba(0, 255, 255, 0.8));
            transform: scale(1);
        }
        50% { 
            filter: drop-shadow(0 0 40px rgba(255, 0, 128, 1));
            transform: scale(1.05);
        }
    }

    @keyframes underlineGlow {
        0%, 100% { opacity: 0.6; transform: translateX(-50%) scaleX(0.8); }
        50% { opacity: 1; transform: translateX(-50%) scaleX(1.2); }
    }

    .footer-description {
        color: rgba(255, 255, 255, 0.9);
        font-size: 1.4rem;
        line-height: 1.9;
        margin-bottom: 50px;
        max-width: 600px;
        font-weight: 400;
        text-shadow: 0 0 15px rgba(0, 255, 255, 0.4);
        animation: textGlow 6s ease-in-out infinite;
    }

    @keyframes textGlow {
        0%, 100% { text-shadow: 0 0 15px rgba(0, 255, 255, 0.4); }
        50% { text-shadow: 0 0 25px rgba(255, 0, 128, 0.6); }
    }

    /* CONTACT & SOCIAL SECTION ULTRA AVANZADA */
    .footer-contact {
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        position: relative;
    }

    .footer-contact::before {
        content: '';
        position: absolute;
        top: -40px;
        right: -40px;
        width: 150px;
        height: 150px;
        background: conic-gradient(from 0deg, #00ffff, #ff0080, #8000ff, #00ff80, #00ffff);
        border-radius: 50%;
        opacity: 0.1;
        animation: conicSpin 8s linear infinite;
        z-index: -1;
    }

    @keyframes conicSpin {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
    }

    .section-title {
        font-family: 'Orbitron', monospace;
        font-size: 2.6rem;
        font-weight: 700;
        background: linear-gradient(135deg, 
            #00ffff 0%, 
            #ff0080 50%, 
            #8000ff 100%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        background-clip: text;
        margin-bottom: 60px;
        letter-spacing: 3px;
        animation: sectionTitlePulse 5s ease-in-out infinite;
        position: relative;
    }

    .section-title::before {
        content: '🌟';
        position: absolute;
        left: -60px;
        top: 50%;
        transform: translateY(-50%);
        animation: starSpin 3s linear infinite;
        font-size: 2rem;
    }

    .section-title::after {
        content: '🌟';
        position: absolute;
        right: -60px;
        top: 50%;
        transform: translateY(-50%);
        animation: starSpin 3s linear infinite reverse;
        font-size: 2rem;
    }

    @keyframes sectionTitlePulse {
        0%, 100% { 
            filter: drop-shadow(0 0 20px rgba(0, 255, 255, 0.7));
        }
        50% { 
            filter: drop-shadow(0 0 35px rgba(255, 0, 128, 0.9));
        }
    }

    @keyframes starSpin {
        0% { transform: translateY(-50%) rotate(0deg); }
        100% { transform: translateY(-50%) rotate(360deg); }
    }

    .contact-methods {
        display: flex;
        flex-direction: column;
        gap: 40px;
        width: 100%;
        max-width: 600px;
        margin-bottom: 60px;
    }

    .contact-item, .social-item {
        background: linear-gradient(135deg, 
            rgba(0, 255, 255, 0.12) 0%, 
            rgba(255, 0, 128, 0.16) 30%, 
            rgba(128, 0, 255, 0.12) 60%,
            rgba(0, 255, 128, 0.08) 100%);
        border: 2px solid transparent;
        border-radius: 30px;
        padding: 40px;
        backdrop-filter: blur(20px);
        transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        position: relative;
        overflow: hidden;
        box-shadow: 
            0 15px 40px rgba(0, 0, 0, 0.4),
            inset 0 1px 0 rgba(255, 255, 255, 0.15);
    }

    .contact-item::before, .social-item::before {
        content: '';
        position: absolute;
        inset: 0;
        border-radius: 30px;
        background: linear-gradient(135deg, 
            rgba(0, 255, 255, 0.2) 0%, 
            transparent 30%, 
            rgba(255, 0, 128, 0.15) 70%, 
            transparent 100%);
        opacity: 0;
        transition: all 0.4s ease;
    }

    .contact-item::after, .social-item::after {
        content: '';
        position: absolute;
        top: 0;
        left: -100%;
        width: 100%;
        height: 100%;
        background: linear-gradient(90deg, 
            transparent 0%, 
            rgba(0, 255, 255, 0.3) 30%,
            rgba(255, 0, 128, 0.4) 50%,
            rgba(128, 0, 255, 0.3) 70%, 
            transparent 100%);
        transition: left 0.8s ease;
        z-index: 1;
    }

    .contact-item:hover, .social-item:hover {
        transform: translateY(-12px) scale(1.03);
        border: 2px solid rgba(0, 255, 255, 0.8);
        box-shadow: 
            0 30px 60px rgba(0, 0, 0, 0.5),
            0 0 50px rgba(0, 255, 255, 0.4),
            inset 0 1px 0 rgba(255, 255, 255, 0.25);
        background: linear-gradient(135deg, 
            rgba(0, 255, 255, 0.18) 0%, 
            rgba(255, 0, 128, 0.22) 30%, 
            rgba(128, 0, 255, 0.18) 60%,
            rgba(0, 255, 128, 0.14) 100%);
    }

    .contact-item:hover::before, .social-item:hover::before {
        opacity: 1;
        animation: energyPulse 0.8s ease-out;
    }

    .contact-item:hover::after, .social-item:hover::after {
        left: 100%;
    }

    @keyframes energyPulse {
        0% { transform: scale(0.8) rotate(0deg); opacity: 0; }
        50% { transform: scale(1.1) rotate(180deg); opacity: 1; }
        100% { transform: scale(1) rotate(360deg); opacity: 0.7; }
    }

    .contact-header, .social-header {
        display: flex;
        align-items: center;
        gap: 20px;
        margin-bottom: 20px;
        justify-content: center;
        position: relative;
        z-index: 2;
    }

    .contact-icon, .social-icon {
        width: 65px;
        height: 65px;
        border-radius: 50%;
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 30px;
        animation: iconLevitate 4s ease-in-out infinite;
        box-shadow: 0 0 30px rgba(0, 0, 0, 0.3);
        position: relative;
        overflow: hidden;
    }

    .contact-icon::before, .social-icon::before {
        content: '';
        position: absolute;
        inset: -2px;
        border-radius: 50%;
        background: conic-gradient(from 0deg, transparent, var(--icon-color), transparent);
        animation: iconBorder 3s linear infinite;
        z-index: -1;
    }

    @keyframes iconBorder {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
    }

    .contact-icon.email {
        background: linear-gradient(135deg, #FF6B6B, #4ECDC4, #45B7D1);
        --icon-color: #FF6B6B;
        animation-delay: 0s;
    }

    .contact-icon.whatsapp {
        background: linear-gradient(135deg, #25D366, #128C7E, #075E54);
        --icon-color: #25D366;
        animation-delay: 2s;
    }

    .social-icon.instagram {
        background: linear-gradient(135deg, #E4405F, #833AB4, #C13584);
        --icon-color: #E4405F;
        animation-delay: 1s;
    }

    .social-icon.tiktok {
        background: linear-gradient(135deg, #000000, #ff0050, #00f2ea);
        --icon-color: #ff0050;
        animation-delay: 3s;
    }

    @keyframes iconLevitate {
        0%, 100% { 
            transform: translateY(0px) rotate(0deg) scale(1);
        }
        25% { 
            transform: translateY(-8px) rotate(5deg) scale(1.05);
        }
        50% { 
            transform: translateY(-4px) rotate(0deg) scale(1.02);
        }
        75% { 
            transform: translateY(-10px) rotate(-5deg) scale(1.08);
        }
    }

    /* Para logos personalizados */
    .social-icon img {
        width: 35px;
        height: 35px;
        object-fit: contain;
        filter: drop-shadow(0 0 10px rgba(255, 255, 255, 0.8));
    }

    .contact-title, .social-title {
        font-family: 'Orbitron', monospace;
        font-size: 1.6rem;
        font-weight: 600;
        color: #ffffff;
        letter-spacing: 2px;
        text-shadow: 0 0 10px rgba(0, 255, 255, 0.6);
        position: relative;
        z-index: 2;
    }

    .contact-info, .social-info {
        text-align: center;
        position: relative;
        z-index: 2;
    }

    .contact-link, .social-link {
        display: inline-block;
        color: #00ffff;
        text-decoration: none;
        font-size: 1.4rem;
        font-weight: 600;
        margin-bottom: 10px;
        transition: all 0.4s ease;
        position: relative;
    }

    .contact-link::after, .social-link::after {
        content: '';
        position: absolute;
        bottom: -3px;
        left: 50%;
        width: 0;
        height: 3px;
        background: linear-gradient(90deg, #00ffff, #ff0080, #8000ff);
        transition: all 0.4s ease;
        transform: translateX(-50%);
        border-radius: 2px;
    }

    .contact-link:hover, .social-link:hover {
        color: #ff0080;
        transform: translateY(-3px) scale(1.05);
        text-shadow: 0 0 20px rgba(255, 0, 128, 0.8);
    }

    .contact-link:hover::after, .social-link:hover::after {
        width: 100%;
        box-shadow: 0 0 15px rgba(0, 255, 255, 0.8);
    }

    .contact-description, .social-description {
        color: rgba(255, 255, 255, 0.8);
        font-size: 1.1rem;
        font-weight: 300;
        margin: 0;
        line-height: 1.6;
    }

    /* SOCIAL SECTION */
    .social-methods {
        display: flex;
        flex-direction: column;
        gap: 40px;
        width: 100%;
        max-width: 600px;
    }

    /* RESPONSIVE DESIGN MEJORADO */
    @media (max-width: 1400px) {
        .footer-content {
            gap: 80px;
        }
        
        .footer-info h3 {
            font-size: 2.8rem;
        }
    }

    @media (max-width: 1200px) {
        .footer-content {
            gap: 60px;
            padding: 0 20px;
        }
        
        .footer-info h3 {
            font-size: 2.4rem;
        }
        
        .section-title {
            font-size: 2.2rem;
        }
    }

    @media (max-width: 768px) {
        .footer {
            padding: 80px 0 40px 0;
        }
        
        .footer-content {
            grid-template-columns: 1fr;
            gap: 60px;
            padding: 0 20px;
        }
        
        .footer-logo {
            font-size: 110px;
        }
        
        .footer-info h3 {
            font-size: 2rem;
            letter-spacing: 3px;
        }
        
        .footer-description {
            font-size: 1.2rem;
            margin-bottom: 40px;
        }
        
        .section-title {
            font-size: 1.8rem;
            margin-bottom: 40px;
        }
        
        .section-title::before,
        .section-title::after {
            display: none;
        }
        
        .contact-methods,
        .social-methods {
            max-width: 100%;
        }
        
        .contact-item,
        .social-item {
            padding: 30px 25px;
        }
        
        .contact-icon,
        .social-icon {
            width: 55px;
            height: 55px;
            font-size: 26px;
        }
        
        .social-icon img {
            width: 30px;
            height: 30px;
        }
    }

    @media (max-width: 480px) {
        .footer {
            padding: 60px 0 30px 0;
        }
        
        .footer-content {
            gap: 50px;
            padding: 0 15px;
        }
        
        .footer-logo {
            font-size: 90px;
        }
        
        .footer-info h3 {
            font-size: 1.8rem;
            letter-spacing: 2px;
        }
        
        .footer-description {
            font-size: 1.1rem;
        }
        
        .section-title {
            font-size: 1.6rem;
            margin-bottom: 35px;
        }
        
        .contact-item,
        .social-item {
            padding: 25px 20px;
        }
        
        .contact-header,
        .social-header {
            flex-direction: column;
            gap: 15px;
        }
        
        .contact-link,
        .social-link {
            font-size: 1.2rem;
        }
        
        .contact-icon,
        .social-icon {
            width: 50px;
            height: 50px;
            font-size: 24px;
        }
        
        .social-icon img {
            width: 28px;
            height: 28px;
        }
        
        .contact-title,
        .social-title {
            font-size: 1.4rem;
        }
    }

    /* ANIMACIONES ADICIONALES PARA ULTRA FUTURISMO */
    @keyframes dataStream {
        0% { transform: translateX(-100%); }
        100% { transform: translateX(100vw); }
    }
</style>

<style>
        @import url('https://fonts.googleapis.com/css2?family=Rajdhani:wght@300;400;500;600;700&family=Orbitron:wght@400;700;900&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-glow: #00ffff;
            --secondary-glow: #ff006e;
            --accent-glow: #8338ec;
            --warning-glow: #ff9f00;
            --success-glow: #06ffa5;
            --bg-dark: #0a0a0a;
            --bg-card: rgba(15, 15, 30, 0.9);
            --text-primary: #ffffff;
            --text-secondary: #a0a0a0;
            --footer-bg: #0f1428;
            --footer-text: #ffffff;
        }

        body {
            font-family: 'Rajdhani', sans-serif;
            background: linear-gradient(135deg, #0f1428, #0a0f1c, #000510);
            background-size: cover;
            background-attachment: fixed;
            color: var(--text-primary);
            overflow-x: hidden;
            position: relative;
            min-height: 100vh;
        }

        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }



        .contact-section {
            padding: 100px 20px;
            min-height: 100vh;
            display: flex;
            align-items: center;
            position: relative;
            z-index: 2;
        }

        .contact-container {
            max-width: 1400px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 80px;
            align-items: center;
        }

        /* LADO IZQUIERDO - LOGO Y TEXTO */
        .left-section {
            text-align: center;
            position: relative;
        }

        .rocket-container {
            width: 180px;
            height: 180px;
            margin: 0 auto 40px;
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .rocket-glow {
            position: absolute;
            width: 160px;
            height: 160px;
            border-radius: 50%;
            background: conic-gradient(from 0deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow), var(--primary-glow));
            animation: rocketSpin 8s linear infinite;
            opacity: 0.7;
        }

        .rocket-inner {
            position: absolute;
            width: 140px;
            height: 140px;
            border-radius: 50%;
            background: var(--bg-card);
            border: 2px solid var(--primary-glow);
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 
                0 0 30px var(--primary-glow),
                inset 0 0 30px rgba(0, 255, 255, 0.1);
            animation: rocketPulse 3s ease-in-out infinite;
        }

        @keyframes rocketSpin {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }

        @keyframes rocketPulse {
            0%, 100% { 
                transform: scale(1);
                box-shadow: 
                    0 0 30px var(--primary-glow),
                    inset 0 0 30px rgba(0, 255, 255, 0.1);
            }
            50% { 
                transform: scale(1.05);
                box-shadow: 
                    0 0 50px var(--primary-glow),
                    inset 0 0 50px rgba(0, 255, 255, 0.2);
            }
        }

        .rocket-emoji {
            font-size: 4rem;
            filter: drop-shadow(0 0 20px var(--primary-glow));
            animation: rocketFloat 2s ease-in-out infinite alternate;
        }

        @keyframes rocketFloat {
            from { transform: translateY(-5px) rotate(-2deg); }
            to { transform: translateY(5px) rotate(2deg); }
        }

        .brand-title {
            font-family: 'Orbitron', monospace;
            font-size: 4rem;
            font-weight: 900;
            margin-bottom: 30px;
            background: linear-gradient(45deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow));
            background-size: 300% 300%;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            animation: gradientShift 4s ease-in-out infinite;
            text-shadow: 0 0 40px var(--primary-glow);
            filter: drop-shadow(0 0 20px rgba(0, 255, 255, 0.5));
        }

        .subtitle {
            font-family: 'Rajdhani', sans-serif;
            font-size: 1.8rem;
            font-weight: 600;
            color: var(--text-primary);
            line-height: 1.6;
            position: relative;
            text-shadow: 0 0 20px var(--secondary-glow);
        }



        .decorative-line {
            width: 150px;
            height: 3px;
            margin: 25px auto;
            background: linear-gradient(90deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow));
            background-size: 200% 200%;
            border-radius: 2px;
            animation: gradientShift 3s ease-in-out infinite;
            box-shadow: 0 0 15px var(--primary-glow);
        }

        /* LADO DERECHO - PLATAFORMAS */
        .right-section {
            position: relative;
        }

        .platforms-container {
            background: rgba(5, 5, 15, 0.95);
            border: 2px solid;
            border-image: linear-gradient(45deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow), var(--success-glow)) 1;
            border-radius: 25px;
            padding: 50px 40px;
            backdrop-filter: blur(20px);
            position: relative;
            overflow: hidden;
            box-shadow: 
                0 0 60px rgba(0, 255, 255, 0.15),
                0 0 120px rgba(255, 0, 110, 0.1),
                inset 0 0 80px rgba(0, 0, 0, 0.3);
            animation: containerColorShift 4s ease-in-out infinite;
        }

        @keyframes containerColorShift {
            0% { 
                border-image: linear-gradient(45deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow), var(--success-glow)) 1;
                box-shadow: 
                    0 0 60px rgba(0, 255, 255, 0.3),
                    0 0 120px rgba(255, 0, 110, 0.1),
                    inset 0 0 80px rgba(0, 0, 0, 0.3);
            }
            25% { 
                border-image: linear-gradient(45deg, var(--secondary-glow), var(--accent-glow), var(--success-glow), var(--primary-glow)) 1;
                box-shadow: 
                    0 0 60px rgba(255, 0, 110, 0.3),
                    0 0 120px rgba(131, 56, 236, 0.1),
                    inset 0 0 80px rgba(0, 0, 0, 0.3);
            }
            50% { 
                border-image: linear-gradient(45deg, var(--accent-glow), var(--success-glow), var(--primary-glow), var(--secondary-glow)) 1;
                box-shadow: 
                    0 0 60px rgba(131, 56, 236, 0.3),
                    0 0 120px rgba(6, 255, 165, 0.1),
                    inset 0 0 80px rgba(0, 0, 0, 0.3);
            }
            75% { 
                border-image: linear-gradient(45deg, var(--success-glow), var(--primary-glow), var(--secondary-glow), var(--accent-glow)) 1;
                box-shadow: 
                    0 0 60px rgba(6, 255, 165, 0.3),
                    0 0 120px rgba(0, 255, 255, 0.1),
                    inset 0 0 80px rgba(0, 0, 0, 0.3);
            }
            100% { 
                border-image: linear-gradient(45deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow), var(--success-glow)) 1;
                box-shadow: 
                    0 0 60px rgba(0, 255, 255, 0.3),
                    0 0 120px rgba(255, 0, 110, 0.1),
                    inset 0 0 80px rgba(0, 0, 0, 0.3);
            }
        }

        .platforms-container::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(135deg, 
                rgba(0, 255, 255, 0.1) 0%,
                rgba(255, 0, 110, 0.05) 25%,
                rgba(131, 56, 236, 0.1) 50%,
                rgba(6, 255, 165, 0.05) 75%,
                rgba(255, 159, 0, 0.1) 100%);
            border-radius: 25px;
            z-index: -1;
            animation: backgroundPulse 8s ease-in-out infinite;
        }

        @keyframes backgroundPulse {
            0%, 100% { opacity: 0.3; transform: scale(1); }
            50% { opacity: 0.7; transform: scale(1.02); }
        }

        /* Efectos de líneas digitales */
        .platforms-container::after {
            content: '';
            position: absolute;
            top: 10px;
            left: 10px;
            right: 10px;
            bottom: 10px;
            border: 1px solid;
            border-image: linear-gradient(45deg, 
                rgba(0, 255, 255, 0.3), 
                rgba(255, 0, 110, 0.3), 
                rgba(131, 56, 236, 0.3)) 1;
            border-radius: 20px;
            pointer-events: none;
            animation: borderGlow 6s ease-in-out infinite;
        }

        @keyframes borderGlow {
            0%, 100% { border-image: linear-gradient(45deg, rgba(0, 255, 255, 0.3), rgba(255, 0, 110, 0.3), rgba(131, 56, 236, 0.3)) 1; }
            33% { border-image: linear-gradient(45deg, rgba(255, 0, 110, 0.4), rgba(131, 56, 236, 0.3), rgba(0, 255, 255, 0.3)) 1; }
            66% { border-image: linear-gradient(45deg, rgba(131, 56, 236, 0.4), rgba(0, 255, 255, 0.3), rgba(255, 0, 110, 0.3)) 1; }
        }

        .platforms-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 25px;
            position: relative;
            z-index: 1;
        }

        .platform-card {
            background: rgba(0, 0, 0, 0.7);
            border: 1px solid rgba(0, 255, 255, 0.2);
            border-radius: 18px;
            padding: 20px 15px;
            text-align: center;
            transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94);
            position: relative;
            overflow: hidden;
            cursor: pointer;
        }

        .platform-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, 
                transparent, 
                rgba(0, 255, 255, 0.1), 
                rgba(255, 0, 110, 0.1), 
                transparent);
            transition: left 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94);
        }

        .platform-card:hover::before {
            left: 100%;
        }

        .platform-card:hover {
            transform: translateY(-12px) scale(1.05);
            border-color: var(--platform-color);
            background: var(--platform-bg);
            box-shadow: 
                0 20px 50px rgba(0, 0, 0, 0.4),
                0 0 40px var(--platform-glow),
                inset 0 0 30px rgba(0, 0, 0, 0.2);
        }

        .platform-icon {
            width: 70px;
            height: 70px;
            margin: 0 auto 15px;
            border-radius: 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            background: var(--platform-bg);
            border: 2px solid var(--platform-color);
            transition: all 0.4s ease;
            position: relative;
        }

        .platform-card:hover .platform-icon {
            transform: scale(1.1) rotate(5deg);
            box-shadow: 0 0 25px var(--platform-glow);
        }

        .platform-icon img {
            width: 45px;
            height: 45px;
            object-fit: contain;
            filter: brightness(1.2);
            transition: all 0.3s ease;
        }

        .platform-card:hover .platform-icon img {
            filter: brightness(1.5) saturate(1.3);
        }

        .platform-name {
            font-family: 'Orbitron', monospace;
            font-size: 1.3rem;
            font-weight: 700;
            color: var(--platform-color);
            margin-bottom: 10px;
            transition: all 0.3s ease;
        }

        .platform-card:hover .platform-name {
            text-shadow: 0 0 15px var(--platform-glow);
            transform: scale(1.05);
        }

        .platform-handle {
            color: var(--text-primary);
            font-size: 1rem;
            font-weight: 500;
            margin-bottom: 8px;
            transition: all 0.3s ease;
        }

        .platform-card:hover .platform-handle {
            color: #ffffff;
            text-shadow: 0 0 10px var(--platform-glow);
        }



        /* Colores específicos para cada plataforma */
        .instagram {
            --platform-color: #E4405F;
            --platform-bg: rgba(228, 64, 95, 0.1);
            --platform-glow: rgba(228, 64, 95, 0.5);
        }

        .tiktok {
            --platform-color: #FF0050;
            --platform-bg: rgba(255, 0, 80, 0.1);
            --platform-glow: rgba(255, 0, 80, 0.5);
        }

        .whatsapp {
            --platform-color: var(--success-glow);
            --platform-bg: rgba(6, 255, 165, 0.1);
            --platform-glow: rgba(6, 255, 165, 0.5);
        }

        .gmail {
            --platform-color: var(--warning-glow);
            --platform-bg: rgba(255, 159, 0, 0.1);
            --platform-glow: rgba(255, 159, 0, 0.5);
        }

        /* Enlaces sin decoración */
        .platform-card a {
            text-decoration: none;
            color: inherit;
            display: block;
        }

        /* Responsive */
        @media (max-width: 1024px) {
            .contact-container {
                gap: 60px;
            }
            
            .brand-title {
                font-size: 3.2rem;
            }
        }

        @media (max-width: 768px) {
            .contact-container {
                grid-template-columns: 1fr;
                gap: 50px;
                text-align: center;
            }
            
            .brand-title {
                font-size: 2.8rem;
            }
            
            .subtitle {
                font-size: 1.5rem;
            }
            
            .platforms-grid {
                grid-template-columns: 1fr 1fr;
                gap: 20px;
            }
        }

        @media (max-width: 480px) {
            .contact-section {
                padding: 60px 15px;
            }
            
            .platforms-grid {
                grid-template-columns: 1fr;
                gap: 15px;
            }
            
            .platform-card {
                padding: 20px 15px;
            }
            
            .brand-title {
                font-size: 2.2rem;
            }
        }

        /* Animaciones de entrada */
        .left-section {
            animation: slideInLeft 1s ease-out;
        }

        .right-section {
            animation: slideInRight 1s ease-out 0.3s both;
        }

        @keyframes slideInLeft {
            from {
                opacity: 0;
                transform: translateX(-50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes slideInRight {
            from {
                opacity: 0;
                transform: translateX(50px);
            }
            to {
                opacity: 1;
                transform: translateX(0);
            }
        }
    </style>
        <script>
        // Siempre ir al inicio al cargar/refrescar
        window.addEventListener('beforeunload', function() {
            window.scrollTo(0, 0);
        });
        
        window.addEventListener('load', function() {
            window.scrollTo(0, 0);
        });
        
        // Alternativa más directa
        if (history.scrollRestoration) {
            history.scrollRestoration = 'manual';
        }
        window.scrollTo(0, 0);
    </script>
    <style>
.decorative-line-full {
    width: 100%;
    height: 3px;
    background: linear-gradient(90deg, var(--primary-glow), var(--secondary-glow), var(--accent-glow));
    background-size: 200% 200%;
    border-radius: 2px;
    animation: gradientShift 3s ease-in-out infinite;
    box-shadow: 0 0 15px var(--primary-glow);
    margin: 60px 0 40px;
}

@media (max-width: 768px) {
    .loading-text {
        font-size: 1.8rem;
        text-align: center;
        padding: 0 15px;
    }

    .loading-logo::before {
        font-size: 60px;
    }

    .loading-bar {
        width: 80%;
    }

    .loading-subtitle {
        font-size: 1rem;
        text-align: center;
        padding: 0 15px;
    }
}

@media (max-width: 480px) {
    .loading-logo::before {
        font-size: 50px;
    }

    .loading-text {
        font-size: 1.4rem;
    }

    .loading-bar {
        height: 5px;
    }

    .loading-subtitle {
        font-size: 0.95rem;
    }
}
</style>
    <!-- Efectos de fondo quitados para usar el tuyo -->
<div class="decorative-line-full"></div>
    <div class="contact-section">
        <div class="contact-container">
            <!-- LADO IZQUIERDO - LOGO Y TEXTO -->
            <div class="left-section">
                <div class="rocket-container">
                    <div class="rocket-glow"></div>
                    <div class="rocket-inner">
                        <div class="rocket-emoji">🚀</div>
                    </div>
                </div>

                <h1 class="brand-title">DIGITAL UNIVERSE</h1>
                <div class="decorative-line"></div>
                <p class="subtitle">Tus plataformas favoritas están aquí</p>
            </div>

            <!-- LADO DERECHO - PLATAFORMAS -->
            <div class="right-section">
                <div class="platforms-container">
                    <div class="platforms-grid">
                        <a href="https://www.instagram.com/digitaluniverse284/" target="_blank" class="platform-card instagram">
                            <div class="platform-icon">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
                            </div>
                            <div class="platform-name">Instagram</div>
                            <div class="platform-handle">@digitaluniverse284</div>
                        </a>

                        <a href="https://www.tiktok.com/@digital.universe284?is_from_webapp=1&sender_device=pc" target="_blank" class="platform-card tiktok">
                            <div class="platform-icon">
                                <img src="images/Tik tok.png" alt="TikTok">
                            </div>
                            <div class="platform-name">TikTok</div>
                            <div class="platform-handle">@digital.universe284</div>
                        </a>

                        <a href="https://wa.me/573214634560" target="_blank" class="platform-card whatsapp">
                            <div class="platform-icon">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
                            </div>
                            <div class="platform-name">WhatsApp</div>
                            <div class="platform-handle">+57 321 463 4560</div>
                        </a>

                        <a href="mailto:digitaluniverse284@gmail.com" class="platform-card gmail">
                            <div class="platform-icon">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Gmail_Icon.png" alt="Gmail">
                            </div>
                            <div class="platform-name">Gmail</div>
                            <div class="platform-handle">digitaluniverse284@gmail.com</div>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</footer>

    <script>
        // Enhanced service data with unique tags and detailed features
        let services = {
            streaming: [
                {
                    name: "Netflix (pantalla)",
                    price: "$10.000",
                    features: [
                        "🎥 Catálogo completo mundial con contenido original",
                        "📺 4K Ultra HD con HDR y Dolby Vision",
                        "📱 Descarga offline en dispositivos móviles",
                        "🚫 Sin anuncios ni interrupciones",
                        "👥 Pantalla compartida con perfiles personalizados",
                        "🌍 Acceso desde cualquier país",
                        "🎬 Estrenos exclusivos y series originales",
                        "📊 Recomendaciones personalizadas con IA"
                    ],
                    tags: ["popular", "recommended"],
                    category: "streaming"
                },
                {
                    name: "Disney Plus Estándar",
                    price: "$4.000",
                    features: [
                        "🏰 Contenido familiar completo de Disney",
                        "🦸‍♂️ Marvel Cinematic Universe completo",
                        "⭐ Star Wars - todas las películas y series",
                        "🎨 Pixar - películas animadas en HD",
                        "🐅 National Geographic documentales",
                        "📱 Descarga móvil para ver offline",
                        "👶 Modo infantil con controles parentales",
                        "🎵 Contenido musical de Disney"
                    ],
                    tags: ["value", "exclusive"],
                    category: "streaming"
                },
                {
                    name: "Disney Plus Premium",
                    price: "$7.500",
                    features: [
                        "🌟 Todo el contenido de Disney Plus Estándar",
                        "📺 4K Ultra HD con Dolby Atmos",
                        "👥 Ppantallas simultáneas",
                        "💾 Descarga ilimitada en todos los dispositivos",
                        "🎬 Acceso temprano a estrenos exclusivos",
                        "🎮 Contenido interactivo y juegos",
                        "🏆 Documentales premium de National Geographic",
                    ],
                    tags: ["premium", "bestseller"],
                    category: "streaming"
                },
                {
                    name: "MAX (antes HBO)",
                    price: "$6.000",
                    features: [
                        "🏆 Contenido HBO original premiado",
                        "🎬 Warner Bros - películas recién estrenadas",
                        "🦸‍♀️ DC Comics - series y películas de superhéroes",
                        "📺 CNN - noticias en vivo 24/7",
                        "🔬 Discovery Channel - documentales científicos",
                        "👥 Streaming simultáneo en múltiples dispositivos",
                        "🌎 Contenido internacional exclusivo",
                        "🎭 Series dramáticas galardonadas"
                    ],
                    tags: ["exclusive", "premium"],
                    category: "streaming"
                },
                {
                    name: "Prime Video",
                    price: "$6.000",
                    features: [
                        "🎬 Amazon Originals exclusivos",
                        "🎪 Películas exclusivas de estreno",
                        "⚽ Deportes en vivo - fútbol y más",
                        "📦 Envíos gratis en Amazon incluidos",
                        "🎵 Amazon Music incluido",
                        "📚 Prime Reading - libros gratis",
                        "☁️ Amazon Photos con almacenamiento ilimitado",
                        "🛒 Ofertas exclusivas en Amazon"
                    ],
                    tags: ["value", "recommended"],
                    category: "streaming"
                },
                {
                    name: "Crunchyroll",
                    price: "$6.000",
                    features: [
                        "🏮 Anime sin anuncios - catálogo completo",
                        "🇯🇵 Simulcast directo desde Japón",
                        "📚 Manga digital incluido",
                        "🎌 Contenido exclusivo y doblajes",
                        "📺 Calidad HD y subtítulos en español",
                        "📱 Apps para todos los dispositivos",
                        "🎪 Eventos especiales y premieres",
                        "👥 Comunidad otaku activa"
                    ],
                    tags: ["exclusive", "popular"],
                    category: "streaming"
                },
                {
                    name: "Paramount Plus",
                    price: "$4.000",
                    features: [
                        "📺 Shows exclusivos de CBS y Paramount",
                        "🎬 Películas exclusivas de Paramount Pictures",
                        "⚽ Deportes en vivo - Champions League",
                        "👶 Nickelodeon - contenido infantil",
                        "😂 Comedy Central - humor y stand-up",
                        "🌟 Star Trek - todas las series",
                        "🕵️ NCIS y series policiales",
                        "📡 Transmisión en vivo de eventos"
                    ],
                    tags: ["value", "exclusive"],
                    category: "streaming"
                },
                {
                    name: "Apple TV Plus - 1 mes",
                    price: "$6.500",
                    features: [
                        "🍎 Originales Apple exclusivos",
                        "📺 4K HDR con Dolby Vision y Atmos",
                        "📱 Descarga offline en todos los dispositivos Apple",
                        "👥 Hasta 6 dispositivos simultáneos",
                        "🚫 Completamente sin anuncios",
                        "🎬 Películas premiadas y aclamadas",
                        "👨‍👩‍👧‍👦 Compartir familiar incluido",
                        "🔒 Privacidad garantizada por Apple"
                    ],
                    tags: ["premium", "exclusive"],
                    category: "streaming"
                },
                {
                    name: "Apple TV Plus - 3 meses",
                    price: "$11.000",
                    features: [
                        "💰 3 meses completos - ahorro del 43%",
                        "🍎 Todas las funciones Premium incluidas",
                        "👨‍👩‍👧‍👦 Perfecto para toda la familia",
                        "📺 Acceso completo al catálogo Apple",
                        "🎬 Estrenos exclusivos durante 3 meses",
                        "📱 Sincronización entre todos los dispositivos",
                        "🏆 Contenido galardonado internacionalmente",
                        "🎵 Integración con Apple Music"
                    ],
                    tags: ["bestseller", "value"],
                    category: "streaming"
                },
                {
                    name: "Viki",
                    price: "$3.200",
                    features: [
                        "🇰🇷 K-Dramas sin anuncios - catálogo completo",
                        "🌏 Subtítulos en múltiples idiomas",
                        "⚡ Acceso temprano a nuevos episodios",
                        "🎭 Contenido asiático exclusivo",
                        "📺 Calidad HD con subtítulos precisos",
                        "📱 Apps móviles optimizadas",
                        "❤️ Series románticas y de comedia",
                        "🎪 Especiales y documentales asiáticos"
                    ],
                    tags: ["exclusive", "popular"],
                    category: "streaming"
                },
                {
                    name: "DirecTV",
                    price: "$14.000",
                    features: [
                        "📺 Canales en vivo - más de 200 opciones",
                        "⚽ Deportes premium - fútbol internacional",
                        "🎬 Películas recientes y estrenos",
                        "☁️ DVR en la nube - graba sin límites",
                        "📱 Múltiples dispositivos simultáneos",
                        "🌎 Canales internacionales incluidos",
                        "📻 Canales de música y radio",
                        "🎯 Guía TV inteligente personalizada"
                    ],
                    tags: ["premium", "recommended"],
                    category: "streaming"
                },
                {
                    name: "Mubi",
                    price: "$5.500",
                    features: [
                        "🎭 Cine independiente y de autor",
                        "🏆 Película nueva cada día - curada por expertos",
                        "🚫 Sin anuncios ni interrupciones",
                        "🌟 Contenido exclusivo no disponible en otros lados",
                        "📺 Calidad HD premium",
                        "🎪 Festivales de cine internacionales",
                        "📝 Reseñas y análisis de expertos",
                        "🌍 Cinema mundial contemporáneo"
                    ],
                    tags: ["exclusive", "premium"],
                    category: "streaming"
                },
                {
                    name: "Universal",
                    price: "$5.000",
                    features: [
                        "🎬 Shows exclusivos de Universal Studios",
                        "🦖 Jurassic Park - saga completa",
                        "😂 Comedias clásicas y modernas",
                        "🎭 Contenido original de Universal",
                        "🚫 Experiencia sin anuncios",
                        "📱 Compatible con todos los dispositivos",
                        "🎪 Detrás de cámaras y contenido extra",
                        "🌟 Clásicos remasterizados en HD"
                    ],
                    tags: ["exclusive", "value"],
                    category: "streaming"
                },
                {
                    name: "Win Sports",
                    price: "$20.000",
                    features: [
                        "⚽ Fútbol colombiano completo - todos los partidos",
                        "🏆 Liga BetPlay - transmisión exclusiva",
                        "📺 Deportes en vivo sin interrupciones",
                        "🔄 Repeticiones ilimitadas de jugadas",
                        "🎥 Multi-cámara para análisis detallado",
                        "📊 Estadísticas en tiempo real",
                        "🎙️ Comentarios de expertos deportivos",
                        "📱 App móvil para ver en cualquier lugar"
                    ],
                    tags: ["exclusive", "popular"],
                    category: "streaming"
                }
            ],
            musica: [
                {
                    name: "Spotify Premium - 1 mes",
                    price: "$8.500",
                    features: [
                        "🚫 Sin anuncios ni interrupciones",
                        "📱 Descarga offline - hasta 10,000 canciones",
                        "🎵 Calidad extrema - 320 kbps",
                        "⏭️ Saltar canciones ilimitado",
                        "🔗 Spotify Connect - controla desde cualquier dispositivo",
                        "🎧 Audio espacial y podcasts exclusivos",
                        "🤖 Recomendaciones con IA personalizada",
                        "📊 Wrapped anual personalizado"
                    ],
                    tags: ["popular", "recommended"],
                    category: "musica"
                },
                {
                    name: "Spotify Premium - 2 meses",
                    price: "$16.000",
                    features: [
                        "💰 2 meses completos - ahorro del 6%",
                        "🎵 Todas las funciones Premium incluidas",
                        "📈 Mejor valor para usuarios regulares",
                        "🎧 Acceso completo a podcasts premium",
                        "🌟 Listas personalizadas avanzadas",
                        "📱 Sincronización entre dispositivos",
                        "🎪 Acceso prioritario a nuevos lanzamientos",
                        "🔊 Control de ecualizador avanzado"
                    ],
                    tags: ["value", "recommended"],
                    category: "musica"
                },
                {
                    name: "Spotify Premium - 3 meses",
                    price: "$22.500",
                    features: [
                        "🔥 3 meses completos - ahorro del 12%",
                        "💎 Máximo ahorro disponible",
                        "🎵 Experiencia completa sin límites",
                        "🎧 Bibliotecas musicales ilimitadas",
                        "📊 Estadísticas detalladas de escucha",
                        "🌟 Acceso VIP a eventos exclusivos",
                        "🤖 IA que aprende tus gustos musicales",
                        "🔗 Integración con redes sociales"
                    ],
                    tags: ["bestseller", "value"],
                    category: "musica"
                },
                {
                    name: "YouTube Premium",
                    price: "$8.500",
                    features: [
                        "🚫 Sin anuncios en YouTube - experiencia limpia",
                        "🎵 YouTube Music Premium incluido",
                        "📱 Descarga offline de videos y música",
                        "📺 Reproducción en segundo plano",
                        "🎬 YouTube Originals exclusivos",
                        "🎧 Audio de alta calidad",
                        "👥 Hasta 6 cuentas familiares",
                        "📊 Estadísticas avanzadas de visualización"
                    ],
                    tags: ["premium", "popular"],
                    category: "musica"
                },
                {
                    name: "Deezer Premium",
                    price: "$5.000",
                    features: [
                        "🎵 Audio Hi-Fi FLAC - calidad de CD",
                        "🚫 Sin anuncios - experiencia pura",
                        "📱 Descarga offline ilimitada",
                        "🌊 Flow personalizado con IA",
                        "📝 Letras sincronizadas en tiempo real",
                        "🎧 Ecualizador personalizable",
                        "🌍 Música de más de 180 países",
                        "📊 Descubrimiento musical inteligente"
                    ],
                    tags: ["premium", "value"],
                    category: "musica"
                }
            ],
            ia: [
                {
                    name: "Blackbox AI",
                    price: "$20.900",
                    features: [
                        "💻 Generación de código inteligente",
                        "🐛 Debugging automático avanzado",
                        "🌐 Soporte para +20 lenguajes de programación",
                        "🔧 Integración con IDEs populares",
                        "📚 Explicaciones detalladas del código",
                        "⚡ Autocompletado con IA",
                        "🔍 Análisis de código en tiempo real",
                        "🎯 Optimización automática de rendimiento"
                    ],
                    tags: ["premium", "exclusive"],
                    category: "ia"
                },
                {
                    name: "ChatGPT Plus",
                    price: "$22.900",
                    features: [
                        "🧠 GPT-4 Turbo - modelo más avanzado",
                        "⚡ Respuestas más rápidas y precisas",
                        "🎯 Acceso prioritario al servidor",
                        "🔌 Plugins avanzados y herramientas",
                        "📄 Análisis de documentos complejos",
                        "🖼️ Generación y análisis de imágenes",
                        "💬 Conversaciones más largas y detalladas",
                        "🌟 Acceso a funciones beta exclusivas"
                    ],
                    tags: ["popular", "bestseller"],
                    category: "ia"
                },
                {
                    name: "Gemini (Dispositivo)",
                    price: "$10.900",
                    features: [
                        "📱 Un dispositivo único autorizado",
                        "🤖 Funciones básicas de IA",
                        "🔧 Soporte técnico estándar",
                        "🔗 Integración básica con Google",
                        "📊 Consultas limitadas por día",
                        "🌐 Acceso web estándar",
                        "📝 Generación de texto básico",
                        "🎯 Perfecto para uso personal"
                    ],
                    tags: ["value", "recommended"],
                    category: "ia"
                },
                {
                    name: "Gemini (Completa)",
                    price: "$30.000",
                    features: [
                        "🔬 Análisis avanzado multimodal",
                        "🌟 Funciones completas desbloqueadas",
                        "💼 Integración Google Workspace completa",
                        "⚡ Procesamiento masivo de datos",
                        "🔌 Acceso completo a API",
                        "📊 Analytics avanzados con IA",
                        "🎯 Consultas ilimitadas",
                        "🛡️ Soporte prioritario 24/7"
                    ],
                    tags: ["premium", "exclusive"],
                    category: "ia"
                }
            ],
            otros: [
                {
                    name: "Duolingo Plus",
                    price: "$4.500",
                    features: [
                        "🚫 Sin anuncios - aprendizaje continuo",
                        "❤️ Vidas ilimitadas - nunca te detengas",
                        "📱 Lecciones offline disponibles",
                        "📊 Progreso personalizado y detallado",
                        "🏆 Certificados oficiales reconocidos",
                        "🎯 Práctica de errores personalizada",
                        "👥 Competencias con amigos",
                        "🌟 Acceso a cursos premium exclusivos"
                    ],
                    tags: ["popular", "value"],
                    category: "otros"
                },
                {
                    name: "Game Pass Ultimate",
                    price: "$22.000",
                    features: [
                        "🎮 Juegos Xbox y PC - catálogo completo",
                        "🎯 EA Play incluido - juegos de Electronic Arts",
                        "☁️ Cloud Gaming - juega en cualquier dispositivo",
                        "🚀 Nuevos lanzamientos disponibles día 1",
                        "👥 Xbox Live Gold incluido",
                        "📱 Gaming móvil con xCloud",
                        "🎪 Descuentos exclusivos en la tienda",
                        "🔗 Cross-play entre plataformas"
                    ],
                    tags: ["popular", "bestseller"],
                    category: "otros"
                },
                {
                    name: "Adobe Photoshop (Dispositivo)",
                    price: "$16.500",
                    features: [
                        "🎨 Edición profesional completa",
                        "🤖 IA integrada Adobe Firefly",
                        "☁️ 20GB de almacenamiento en la nube",
                        "🔄 Actualizaciones automáticas incluidas",
                        "📱 Sincronización con apps móviles",
                        "🖼️ Herramientas avanzadas de retoque",
                        "🎭 Efectos y filtros profesionales",
                        "📐 Herramientas de diseño vectorial"
                    ],
                    tags: ["premium", "popular"],
                    category: "otros"
                },
                {
                    name: "Canva Pro - 1 mes",
                    price: "$9.800",
                    features: [
                        "🎨 Plantillas premium ilimitadas",
                        "🖼️ Elementos y fotos premium",
                        "🏢 Brand kit personalizado",
                        "✂️ Remover fondo automático con IA",
                        "📏 Resize mágico para redes sociales",
                        "👥 Colaboración en equipo",
                        "📊 Plantillas de presentaciones avanzadas",
                        "💾 Almacenamiento en la nube expandido"
                    ],
                    tags: ["popular", "recommended"],
                    category: "otros"
                },
                {
                    name: "Canva Pro - 12 meses",
                    price: "$30.900",
                    features: [
                        "💰 12 meses completos - ahorro del 74%",
                        "🎨 Todas las funciones Pro desbloqueadas",
                        "👥 Colaboración en equipo avanzada",
                        "💾 1TB de almacenamiento en la nube",
                        "📈 Analytics de diseño y rendimiento",
                        "🎯 Plantillas exclusivas actualizadas",
                        "🤖 IA de diseño más avanzada",
                        "🌟 Soporte prioritario incluido"
                    ],
                    tags: ["bestseller", "value"],
                    category: "otros"
                },
                {
                    name: "Office 365 - 1 dispositivo",
                    price: "$15.000",
                    features: [
                        "📄 Word, Excel, PowerPoint completos",
                        "☁️ 1TB de almacenamiento OneDrive",
                        "🔄 Actualizaciones automáticas siempre",
                        "🛠️ Soporte técnico de Microsoft",
                        "📱 Aplicaciones móviles incluidas",
                        "🔗 Sincronización entre dispositivos",
                        "📊 Funciones avanzadas de Excel",
                        "🎯 Templates profesionales premium"
                    ],
                    tags: ["popular", "recommended"],
                    category: "otros"
                },
                {
                    name: "Office 365 - 5 dispositivos",
                    price: "$35.000",
                    features: [
                        "👨‍👩‍👧‍👦 Hasta 5 dispositivos simultáneos",
                        "☁️ 5TB de OneDrive total (1TB por usuario)",
                        "👥 Compartir familiar con gestión",
                        "📱 Todas las apps Office en móvil y PC",
                        "💼 Microsoft Teams Premium incluido",
                        "🔒 Seguridad avanzada y privacidad",
                        "📞 Skype con minutos internacionales",
                        "🎯 Perfecto para familias y equipos"
                    ],
                    tags: ["bestseller", "value"],
                    category: "otros"
                }
            ]
        };

        // User comments storage
        let userComments = [];
        let selectedRating = 0;
        let currentEditingService = null;

        // Admin functionality
        const ADMIN_PASSWORD = "digitaluniverse2024";
        let isAdminLoggedIn = false;

        function showAdminLogin() {
            document.getElementById('adminOverlay').style.display = 'flex';
        }

        function hideAdminLogin() {
            document.getElementById('adminOverlay').style.display = 'none';
            document.getElementById('adminPassword').value = '';
        }

        function checkAdminPassword() {
            const password = document.getElementById('adminPassword').value;
            if (password === ADMIN_PASSWORD) {
                isAdminLoggedIn = true;
                hideAdminLogin();
                document.getElementById('adminPanel').style.display = 'block';
                alert('¡Bienvenido Administrador!');
            } else {
                alert('Contraseña incorrecta');
            }
        }

        function logoutAdmin() {
            isAdminLoggedIn = false;
            document.getElementById('adminPanel').style.display = 'none';
            alert('Sesión cerrada');
        }

        // Add Service Function
        function addService() {
            if (!isAdminLoggedIn) return;
            document.getElementById('addModal').style.display = 'flex';
        }

        function closeAddModal() {
            document.getElementById('addModal').style.display = 'none';
            document.getElementById('addForm').reset();
        }

        function saveNewService() {
            const name = document.getElementById('addServiceName').value;
            const price = document.getElementById('addServicePrice').value;
            const category = document.getElementById('addServiceCategory').value;
            const features = document.getElementById('addServiceFeatures').value.split('\n').filter(f => f.trim());
            const tags = document.getElementById('addServiceTags').value.split(',').map(t => t.trim()).filter(t => t);

            if (!name || !price || !features.length) {
                alert('Por favor complete todos los campos obligatorios');
                return;
            }

            const newService = {
                name,
                price,
                features,
                tags,
                category
            };

            if (!services[category]) {
                services[category] = [];
            }

            services[category].push(newService);
            renderServices();
            closeAddModal();
            alert('Servicio agregado exitosamente!');
        }

        // Edit Services Function
        function editServices() {
            if (!isAdminLoggedIn) return;
            // Add edit buttons to all service cards
            const serviceCards = document.querySelectorAll('.service-card');
            serviceCards.forEach((card, index) => {
                if (!card.querySelector('.admin-edit-btn')) {
                    const editBtn = document.createElement('button');
                    editBtn.className = 'admin-btn admin-edit-btn';
                    editBtn.textContent = '✏️ Editar';
                    editBtn.style.cssText = 'position: absolute; top: 10px; right: 10px; padding: 5px 10px; font-size: 12px;';
                    editBtn.onclick = (e) => {
                        e.stopPropagation();
                        openEditModal(card);
                    };
                    card.style.position = 'relative';
                    card.appendChild(editBtn);
                }
            });
            alert('Modo de edición activado. Haz clic en "Editar" en cualquier servicio.');
        }

        function openEditModal(card) {
            const serviceName = card.querySelector('.service-name').textContent;
            const servicePrice = card.querySelector('.service-price').textContent;
            const features = Array.from(card.querySelectorAll('.feature-item')).map(item => item.textContent);
            
            document.getElementById('editServiceName').value = serviceName;
            document.getElementById('editServicePrice').value = servicePrice;
            document.getElementById('editServiceFeatures').value = features.join('\n');
            
            currentEditingService = card;
            document.getElementById('editModal').style.display = 'flex';
        }

        function closeEditModal() {
            document.getElementById('editModal').style.display = 'none';
            document.getElementById('editForm').reset();
            currentEditingService = null;
        }

        function saveServiceEdit() {
            if (!currentEditingService) return;

            const name = document.getElementById('editServiceName').value;
            const price = document.getElementById('editServicePrice').value;
            const category = document.getElementById('editServiceCategory').value;
            const features = document.getElementById('editServiceFeatures').value.split('\n').filter(f => f.trim());
            const tags = document.getElementById('editServiceTags').value.split(',').map(t => t.trim()).filter(t => t);

            if (!name || !price || !features.length) {
                alert('Por favor complete todos los campos obligatorios');
                return;
            }

            // Update the service in the data
            const oldServiceName = currentEditingService.querySelector('.service-name').textContent;
            
            // Find and update the service in the services object
            for (let cat in services) {
                const serviceIndex = services[cat].findIndex(service => service.name === oldServiceName);
                if (serviceIndex !== -1) {
                    services[cat][serviceIndex] = {
                        name,
                        price,
                        features,
                        tags,
                        category
                    };
                    break;
                }
            }

            renderServices();
            closeEditModal();
            alert('Servicio actualizado exitosamente!');
        }

        // Comments Management
        function manageComments() {
            if (!isAdminLoggedIn) return;
            const commentsList = document.getElementById('commentsList');
            commentsList.innerHTML = '';

            if (userComments.length === 0) {
                commentsList.innerHTML = '<p style="color: var(--text-secondary);">No hay comentarios para gestionar.</p>';
            } else {
                userComments.forEach((comment, index) => {
                    const commentDiv = document.createElement('div');
                    commentDiv.style.cssText = 'background: rgba(255,255,255,0.1); padding: 15px; margin: 10px 0; border-radius: 15px; border: 1px solid rgba(255,255,255,0.2);';
                    commentDiv.innerHTML = `
                        <h5 style="color: var(--primary-glow);">${comment.name}</h5>
                        <p style="color: white; margin: 10px 0;">"${comment.comment}"</p>
                        <p style="color: var(--warning-glow);">⭐ ${comment.rating}/5</p>
                        <button onclick="deleteComment(${index})" style="background: var(--secondary-glow); color: white; border: none; padding: 5px 10px; border-radius: 10px; cursor: pointer; margin-top: 10px;">🗑️ Eliminar</button>
                    `;
                    commentsList.appendChild(commentDiv);
                });
            }

            document.getElementById('commentsModal').style.display = 'flex';
        }

        function closeCommentsModal() {
            document.getElementById('commentsModal').style.display = 'none';
        }

        function deleteComment(index) {
            if (confirm('¿Estás seguro de que quieres eliminar este comentario?')) {
                userComments.splice(index, 1);
                renderTestimonials();
                manageComments(); // Refresh the modal
                alert('Comentario eliminado exitosamente!');
            }
        }

        // Loading Screen Management
        window.addEventListener('load', function() {
            const loadingScreen = document.getElementById('loadingScreen');
            const mainContent = document.getElementById('mainContent');
            
            setTimeout(() => {
                loadingScreen.classList.add('hidden');
                setTimeout(() => {
                    mainContent.classList.add('visible');
                    initializeParticles();
                    initializeSearch();
                    initializeFilters();
                    renderServices();
                }, 500);
            }, 4000);
        });

        // Initialize Particles
        function initializeParticles() {
            const particlesContainer = document.getElementById('particles');
            const particleCount = 50;

            for (let i = 0; i < particleCount; i++) {
                createParticle();
            }

            function createParticle() {
                const particle = document.createElement('div');
                particle.classList.add('particle');
                
                particle.style.left = Math.random() * 100 + '%';
                particle.style.animationDelay = Math.random() * 20 + 's';
                particle.style.animationDuration = (15 + Math.random() * 10) + 's';
                
                const colors = ['#00ffff', '#ff006e', '#8338ec', '#06ffa5'];
                const randomColor = colors[Math.floor(Math.random() * colors.length)];
                particle.style.background = randomColor;
                particle.style.boxShadow = `0 0 15px ${randomColor}`;
                
                particlesContainer.appendChild(particle);
                
                setTimeout(() => {
                    if (particle.parentNode) {
                        particle.remove();
                        createParticle();
                    }
                }, (15 + Math.random() * 10) * 1000);
            }
        }

        // Service Features Toggle
        function toggleFeatures(card) {
            const isExpanded = card.classList.contains('expanded');
            
            document.querySelectorAll('.service-card.expanded').forEach(otherCard => {
                if (otherCard !== card) {
                    otherCard.classList.remove('expanded');
                }
            });
            
            if (isExpanded) {
                card.classList.remove('expanded');
            } else {
                card.classList.add('expanded');
            }
        }

        // Search Functionality
        function initializeSearch() {
            const searchInput = document.getElementById('searchInput');
            
            searchInput.addEventListener('input', function(e) {
                const searchTerm = e.target.value.toLowerCase();
                const serviceCards = document.querySelectorAll('.service-card');
                
                serviceCards.forEach(card => {
                    const serviceName = card.querySelector('.service-name').textContent.toLowerCase();
                    const features = Array.from(card.querySelectorAll('.feature-item')).map(item => item.textContent.toLowerCase()).join(' ');
                    
                    if (serviceName.includes(searchTerm) || features.includes(searchTerm)) {
                        card.style.display = 'block';
                    } else {
                        card.style.display = 'none';
                    }
                });
            });
        }

        // Filter Functionality
        function initializeFilters() {
            const filterTags = document.querySelectorAll('.filter-tag');
            
            filterTags.forEach(tag => {
                tag.addEventListener('click', function() {
                    filterTags.forEach(t => t.classList.remove('active'));
                    this.classList.add('active');
                    
                    const category = this.getAttribute('data-category');
                    const categorySections = document.querySelectorAll('.category-section');
                    
                    if (category === 'all') {
                        categorySections.forEach(section => {
                            section.style.display = 'block';
                        });
                    } else {
                        categorySections.forEach(section => {
                            const categoryTitle = section.querySelector('.category-title').textContent.toLowerCase();
                            if (category === 'streaming' && categoryTitle.includes('streaming')) {
                                section.style.display = 'block';
                            } else if (category === 'musica' && categoryTitle.includes('música')) {
                                section.style.display = 'block';
                            } else if (category === 'ia' && categoryTitle.includes('inteligencia')) {
                                section.style.display = 'block';
                            } else if (category === 'otros' && categoryTitle.includes('otros')) {
                                section.style.display = 'block';
                            } else {
                                section.style.display = 'none';
                            }
                        });
                    }
                });
            });
        }

        // Render Services Function
        function renderServices() {
            const servicesContainer = document.getElementById('servicesContainer');
            servicesContainer.innerHTML = '';

            const categoryNames = {
                streaming: { title: 'STREAMING', icon: '🎬' },
                musica: { title: 'MÚSICA', icon: '🎵' },
                ia: { title: 'INTELIGENCIA ARTIFICIAL', icon: '🤖' },
                otros: { title: 'OTROS SERVICIOS', icon: '⚡' }
            };

            Object.keys(services).forEach(category => {
                if (services[category].length === 0) return;

                const categorySection = document.createElement('div');
                categorySection.className = 'category-section';
                categorySection.innerHTML = `
                    <div class="category-header">
                        <span class="category-icon">${categoryNames[category].icon}</span>
                        <h2 class="category-title">${categoryNames[category].title}</h2>
                        <span class="category-icon">${categoryNames[category].icon}</span>
                    </div>
                    <div class="services-grid">
                        ${services[category].map(service => createServiceCard(service)).join('')}
                    </div>
                `;

                servicesContainer.appendChild(categorySection);
            });

            // Re-attach event listeners
            attachServiceEvents();
        }

        // Etiquetas de servicios con íconos mejorados
        const tagClasses = {
            'popular': 'tag-popular',
            'recommended': 'tag-recommended', 
            'premium': 'tag-premium',
            'bestseller': 'tag-bestseller',
            'exclusive': 'tag-exclusive',
            'value': 'tag-value'
        };

        const tagLabels = {
            'popular': '🔥 Más Popular',
            'recommended': '⭐ Recomendado',
            'premium': '💎 Premium',
            'bestseller': '🏆 Más Vendido',
            'exclusive': '🌟 Exclusivo',
            'value': '💰 Mejor Valor'
        };

        function createServiceCard(service) {
            const tagsHtml = service.tags.map(tag => 
                `<span class="service-tag ${tagClasses[tag] || 'tag-popular'}">${tagLabels[tag] || tag}</span>`
            ).join('');

            const featuresHtml = service.features.map(feature => 
                `<li class="feature-item">${feature}</li>`
            ).join('');

            return `
                <div class="service-card" onclick="toggleFeatures(this)" data-service="${service.name.toLowerCase()}">
                    <div class="service-tags">
                        ${tagsHtml}
                    </div>
                    <div class="service-header">
                        <h3 class="service-name">${service.name}</h3>
                        <div class="service-price">${service.price}</div>
                    </div>
                    <div class="service-features">
                        <ul class="feature-list">
                            ${featuresHtml}
                        </ul>
                        <div class="service-actions">
                            <a href="https://wa.me/573214634560?text=Hola!%20Me%20interesa%20${encodeURIComponent(service.name)}%20por%20${encodeURIComponent(service.price)}" class="service-btn service-btn-primary" target="_blank">
                                🛒 Comprar Ahora
                            </a>
                            <button class="service-btn service-btn-secondary" onclick="shareService('${service.name}', '${service.price}')">
                                <span>📤</span>
                                <span>Compartir</span>
                            </button>
                        </div>
                    </div>
                </div>
            `;
        }

        // Testimonials functionality
        function toggleCommentForm() {
            const commentForm = document.getElementById('commentForm');
            if (commentForm.style.display === 'none' || commentForm.style.display === '') {
                commentForm.style.display = 'block';
            } else {
                commentForm.style.display = 'none';
                resetCommentForm();
            }
        }

        function resetCommentForm() {
            document.getElementById('userName').value = '';
            document.getElementById('userComment').value = '';
            selectedRating = 0;
            updateStarDisplay();
        }

        // Star rating functionality
        document.addEventListener('DOMContentLoaded', function() {
            const stars = document.querySelectorAll('.star');
            stars.forEach(star => {
                star.addEventListener('click', function() {
                    selectedRating = parseInt(this.getAttribute('data-rating'));
                    updateStarDisplay();
                });

                star.addEventListener('mouseenter', function() {
                    const rating = parseInt(this.getAttribute('data-rating'));
                    highlightStars(rating);
                });
            });

            document.getElementById('starRating').addEventListener('mouseleave', function() {
                updateStarDisplay();
            });
        });

        function highlightStars(rating) {
            const stars = document.querySelectorAll('.star');
            stars.forEach((star, index) => {
                if (index < rating) {
                    star.classList.add('selected');
                } else {
                    star.classList.remove('selected');
                }
            });
        }

        function updateStarDisplay() {
            highlightStars(selectedRating);
        }

        function submitComment() {
            const userName = document.getElementById('userName').value.trim();
            const userComment = document.getElementById('userComment').value.trim();

            if (!userName || !userComment || selectedRating === 0) {
                alert('Por favor completa todos los campos y selecciona una calificación.');
                return;
            }

            const newComment = {
                name: userName,
                comment: userComment,
                rating: selectedRating,
                date: new Date().toLocaleDateString()
            };

            userComments.push(newComment);
            renderTestimonials();
            toggleCommentForm();
            alert('¡Gracias por tu testimonio! Ha sido agregado exitosamente.');
        }

        function renderTestimonials() {
            const testimonialsGrid = document.getElementById('testimonialsGrid');
            
            // Keep original testimonials and add user comments
            const originalTestimonials = `
                <div class="testimonial-card">
                    <p class="testimonial-text">"Increíble servicio! Netflix funcionando perfecto por meses. Precio súper accesible y entrega inmediata. 100% recomendado!"</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">M</div>
                        <div class="author-info">
                            <h4>María González</h4>
                            <div class="stars">⭐⭐⭐⭐⭐</div>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <p class="testimonial-text">"Spotify Premium funcionando de maravilla. El soporte es excelente, responden súper rápido. Ya llevo 6 meses sin problemas."</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">C</div>
                        <div class="author-info">
                            <h4>Carlos Ruiz</h4>
                            <div class="stars">⭐⭐⭐⭐⭐</div>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <p class="testimonial-text">"ChatGPT Plus a precio increíble! La IA funciona perfecta, todas las funciones disponibles. Mejor que comprarlo oficial."</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">A</div>
                        <div class="author-info">
                            <h4>Ana Morales</h4>
                            <div class="stars">⭐⭐⭐⭐⭐</div>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <p class="testimonial-text">"Office 365 completo por una fracción del precio oficial. Todas las aplicaciones funcionando al 100%. Excelente inversión!"</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">J</div>
                        <div class="author-info">
                            <h4>Juan Pérez</h4>
                            <div class="stars">⭐⭐⭐⭐⭐</div>
                        </div>
                    </div>
                </div>
            `;

            const userTestimonials = userComments.map(comment => `
                <div class="testimonial-card">
                    <p class="testimonial-text">"${comment.comment}"</p>
                    <div class="testimonial-author">
                        <div class="author-avatar">${comment.name.charAt(0).toUpperCase()}</div>
                        <div class="author-info">
                            <h4>${comment.name}</h4>
                            <div class="stars">${'⭐'.repeat(comment.rating)}</div>
                        </div>
                    </div>
                </div>
            `).join('');

            testimonialsGrid.innerHTML = originalTestimonials + userTestimonials;
        }
        // Share service function
        function shareService(serviceName, price) {
            const text = `🌟 ¡Mira este increíble servicio! ${serviceName} por solo ${price}! 🚀\n\n¡Consigue tu plataforma favorita al mejor precio! 💰\n\n¡Contacta ahora! 👇`;
            const whatsappUrl = `https://wa.me/573214634560?text=${encodeURIComponent(text)}`;
            
            if (navigator.share) {
                navigator.share({
                    title: `${serviceName} - ${price}`,
                    text: text,
                    url: window.location.href
                });
            } else {
                window.open(whatsappUrl, '_blank');
            }
        }
        // Smooth scrolling for category headers
        document.addEventListener('DOMContentLoaded', function() {
            setTimeout(() => {
                document.querySelectorAll('.category-header').forEach(header => {
                    header.addEventListener('click', function() {
                        this.scrollIntoView({ behavior: 'smooth', block: 'center' });
                    });
                });
            }, 5000);
        });
    </script>
</body>
</html>
