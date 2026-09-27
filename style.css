@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');

:root {
    /* Qorong'u rejim (Dark Mode) */
    --bg-color: #000000;
    --text-main: #ffffff;
    --text-inverse: #000000;
    --text-muted: #a7a7a7;
    --accent: #1db954; 
    --glass-bg: rgba(18, 18, 18, 0.6);
    --glass-border: rgba(255, 255, 255, 0.08);
    --input-bg: rgba(255, 255, 255, 0.1);
    --bg-image: url('https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?q=80&w=2564&auto=format&fit=crop'); 
}

body.light-mode {
    /* Yorug' rejim (Light Mode) */
    --bg-color: #f5f5f7;
    --text-main: #1d1d1f;
    --text-inverse: #ffffff;
    --text-muted: #86868b;
    --accent: #0066cc; 
    --glass-bg: rgba(255, 255, 255, 0.6);
    --glass-border: rgba(0, 0, 0, 0.1);
    --input-bg: rgba(0, 0, 0, 0.05);
    --bg-image: url('https://images.unsplash.com/photo-1579546929518-9e396f3cc809?q=80&w=2670&auto=format&fit=crop'); 
}

body.evening-mode {
    /* Oqshom rejimi (Evening) */
    --bg-color: #0f0c29;
    --text-main: #ffffff;
    --text-inverse: #000000;
    --text-muted: #c8b6ff;
    --accent: #d946ef; 
    --glass-bg: rgba(20, 15, 45, 0.5);
    --glass-border: rgba(255, 255, 255, 0.15);
    --input-bg: rgba(255, 255, 255, 0.15);
    --bg-image: url('https://images.unsplash.com/photo-1614850523459-c2f4c699c52e?q=80&w=2670&auto=format&fit=crop'); 
}

body {
    font-family: 'Inter', sans-serif;
    background-color: var(--bg-color);
    background-image: var(--bg-image);
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
}

/* Цвета текста и фонов */
.text-main { color: var(--text-main); }
.text-muted { color: var(--text-muted); }
.text-inverse { color: var(--text-inverse); }
.bg-main { background-color: var(--text-main); }
.bg-accent { background-color: var(--accent); }
.text-accent { color: var(--accent); }
.accent-accent { accent-color: var(--accent); }

/* Эффект стекла */
.glass-panel {
    background: var(--glass-bg);
    backdrop-filter: blur(28px) saturate(200%);
    -webkit-backdrop-filter: blur(28px) saturate(200%);
}
.glass-input {
    background: var(--input-bg);
    backdrop-filter: blur(16px);
    border: 1px solid var(--glass-border);
}
.glass-input:focus {
    border-color: var(--accent);
    background: var(--glass-bg);
}
.glass-btn {
    background: var(--input-bg);
    border: 1px solid var(--glass-border);
    color: var(--text-main);
}
.glass-btn:hover { background: var(--glass-border); }

/* Меню */
.nav-item.active {
    background: var(--input-bg);
    border: 1px solid var(--glass-border);
}

/* Карточки песен */
.song-card {
    background: var(--glass-bg);
    border: 1px solid var(--glass-border);
    backdrop-filter: blur(12px);
    transition: all 0.3s;
}
.song-card:hover {
    transform: translateY(-5px);
    border-color: var(--accent);
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}

/* Лоадер */
.loader {
    border: 4px solid var(--glass-border);
    border-top: 4px solid var(--accent);
    border-radius: 50%;
    width: 40px; height: 40px;
    animation: spin 1s linear infinite;
    margin: 40px auto;
    display: none;
}
@keyframes spin { 100% { transform: rotate(360deg); } }

/* Полный фикс скрытых элементов в Tailwind */
.hidden { display: none !important; }

/* Жидкий фон */
#liquid-blob {
    position: fixed;
    width: 600px;
    height: 600px;
    background: radial-gradient(circle, var(--accent) 0%, transparent 60%);
    filter: blur(80px);
    pointer-events: none; /* Важно: чтобы не мешал кликать */
    z-index: 0;
    opacity: 0.3;
    top: 50%;
    left: 50%;
    animation: liquid-shape 8s infinite alternate ease-in-out;
    transform: translate(-50%, -50%);
}
@keyframes liquid-shape {
    0% { border-radius: 40% 60% 70% 30% / 40% 50% 60% 50%; }
    100% { border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%; }
}