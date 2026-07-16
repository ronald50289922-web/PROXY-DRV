<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DVR PROXY</title>

<style>
/* ============================================================
   ESTILOS GLOBAIS
   ============================================================ */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    background: #050505;
    color: #fff;
    padding: 20px;
    overflow-x: hidden;
}

/* ── Header ── */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
    position: sticky;
    top: 0;
    background: #050505;
    z-index: 100;
    padding: 5px 0;
}

.menu-trigger {
    font-size: 28px;
    cursor: pointer;
    color: #fff;
}

.logo h1 {
    font-size: 26px;
    color: #fff;
    text-shadow: 0 0 10px #ff073a;
}

.logo p {
    font-size: 13px;
    color: #808080;
}

.status-badge {
    padding: 8px 16px;
    border: 1px solid #fff;
    border-radius: 20px;
    color: #fff;
    box-shadow: 0 0 12px rgba(0, 255, 102, .5);
    font-size: 12px;
}

/* ── Menu Lateral ── */
.menu-lateral {
    position: fixed;
    top: 0;
    left: -300px;
    width: 270px;
    height: 100%;
    background: #111;
    border-right: 2px solid #ff0000;
    padding: 20px;
    transition: .3s;
    z-index: 9999;
}

.menu-lateral h2 {
    margin-bottom: 20px;
    color: #fff;
    text-align: center;
}

.menu-lateral hr {
    margin: 15px 0;
    border: 0;
    border-top: 1px solid #333;
}

.btn-menu {
    width: 100%;
    height: 50px;
    margin: 8px 0;
    background: #1b1b1b;
    color: #fff;
    border: 1px solid #ff0000;
    border-radius: 12px;
    cursor: pointer;
    font-size: 14px;
    font-weight: bold;
    transition: .3s;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
}

.btn-menu:hover {
    background: #ff0000;
    color: #000;
}

.btn-menu.active {
    background: #ff0000;
    color: #000;
}

.overlay {
    display: none;
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0, 0, 0, .7);
    z-index: 9998;
}

/* ── Seções (Pages) ── */
.page-section {
    display: none;
    animation: fadeIn 0.4s ease;
}

.page-section.active {
    display: block;
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(10px); }
    to { opacity: 1; transform: translateY(0); }
}

/* ── Cards e Componentes ── */
.card {
    background: #101010;
    border: 1px solid #1d1d1d;
    border-radius: 18px;
    padding: 18px;
    margin-bottom: 18px;
    box-shadow: 0 0 18px rgba(0, 255, 102, .08);
}

.card h2 {
    font-size: 18px;
    margin-bottom: 15px;
    color: #FF0000;
}

.item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 14px 0;
    border-bottom: 1px solid #222;
}

.item:last-child { border-bottom: none; }

.info h3 { font-size: 16px; }
.info p { font-size: 12px; color: #999; margin-top: 4px; }

/* ── Toggle Switch ── */
.switch {
    position: relative;
    width: 58px;
    height: 30px;
}
.switch input { display: none; }
.slider {
    position: absolute;
    cursor: pointer;
    top: 0; left: 0; right: 0; bottom: 0;
    background: #333;
    border-radius: 30px;
    transition: .3s;
}
.slider:before {
    content: "";
    position: absolute;
    width: 24px; height: 24px;
    left: 3px; top: 3px;
    background: white;
    border-radius: 50%;
    transition: .3s;
}
input:checked + .slider {
    background: #00ff66;
    box-shadow: 0 0 12px #00ff66;
}
input:checked + .slider:before { transform: translateX(28px); }

/* ── Botões ── */
.btn-primary {
    width: 100%;
    height: 60px;
    border: none;
    border-radius: 15px;
    background: #FF0000;
    color: #000;
    font-size: 14px;
    font-weight: bold;
    cursor: pointer;
    margin-top: 15px;
    box-shadow: 0 0 18px #FF0000;
    transition: .3s;
}
.btn-primary:hover {
    transform: scale(1.02);
    box-shadow: 0 0 30px #FF0000;
}

/* ============================================================
   ESTILOS ESPECÍFICOS: ADB WI-FI
   ============================================================ */
.adb-status {
    background: #151922;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    font-weight: bold;
    color: #ff4040;
    margin-bottom: 20px;
}

.adb-box {
    background: #131720;
    padding: 18px;
    border-radius: 18px;
    margin-top: 15px;
}

.adb-box h3 { color: #00bfff; font-size: 18px; margin-bottom: 10px; }
.adb-box p { color: #ddd; line-height: 1.6; font-size: 14px; }

.adb-tabs {
    display: flex;
    margin-top: 20px;
    border-radius: 12px;
    overflow: hidden;
}

.adb-tab {
    width: 50%;
    padding: 14px;
    text-align: center;
    background: #151922;
    cursor: pointer;
    font-size: 13px;
    font-weight: bold;
}

.adb-tab.active { background: #008cff; }

.adb-page { display: none; }
.adb-page.active { display: block; }

.adb-input {
    width: 100%;
    padding: 14px;
    margin-top: 10px;
    background: #080a0f;
    color: white;
    border: 1px solid #333;
    border-radius: 12px;
    text-align: center;
    font-size: 18px;
}

.adb-btn {
    width: 100%;
    padding: 14px;
    margin-top: 15px;
    border: none;
    border-radius: 12px;
    background: #008cff;
    color: white;
    font-weight: bold;
    cursor: pointer;
}

/* ============================================================
   ESTILOS ESPECÍFICOS: BYPASS SS
   ============================================================ */
.bypass-container {
    text-align: center;
    padding: 40px 20px;
}

.loading-spinner {
    width: 50px;
    height: 50px;
    border: 5px solid #333;
    border-top: 5px solid #ff0000;
    border-radius: 50%;
    margin: 0 auto 20px;
    animation: spin 1s linear infinite;
}

@keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}

.status-text {
    font-size: 20px;
    font-weight: bold;
    color: #ff0000;
    text-transform: uppercase;
    letter-spacing: 2px;
}

/* Toast */
#toast {
    display: none;
    position: fixed;
    bottom: 25px;
    left: 50%;
    transform: translateX(-50%);
    background: #202632;
    color: #fff;
    padding: 15px 25px;
    border-radius: 30px;
    font-size: 14px;
    z-index: 10001;
}
</style>
</head>

<body>

<!-- Overlay -->
<div class="overlay" id="overlay" onclick="toggleMenu()"></div>

<!-- Menu Lateral Unificado -->
<div class="menu-lateral" id="menuLateral">
    <h2>DVR PROXY</h2>
    <hr>
    <button class="btn-menu active" id="nav-menu" onclick="navegar('menu')">⊕ Menu Principal</button>
    <button class="btn-menu" id="nav-adb" onclick="navegar('adb')">⇄ ADB Wi-Fi</button>
    <button class="btn-menu" id="nav-bypass" onclick="navegar('bypass')">✯ Bypass SS</button>
    <hr>
    <button class="btn-menu" onclick="toggleMenu()" style="border-color: #555; background: #222;">✕ Fechar Menu</button>
</div>

<!-- Header -->
<header>
    <div class="menu-trigger" onclick="toggleMenu()">☰</div>
    <div class="logo">
        <h1>DVR PROXY</h1>
        <p>Versão 2.0</p>
    </div>
    <div class="status-badge">🟢 Online</div>
</header>

<!-- SEÇÃO: MENU PRINCIPAL (FUNÇÕES) -->
<div id="page-menu" class="page-section active">
    
    <!-- Seção: Funções (Seleção Única) -->
    <div class="card">
        <h2>Funções</h2>
        <p style="font-size: 11px; color: #666; margin-bottom: 10px;">(Selecione apenas uma opção)</p>
        
        <div class="item">
            <div class="info"><h3>Hs alto</h3><p>Hs acima da cabeça</p></div>
            <label class="switch">
                <input type="checkbox" class="funcao-unica" onchange="selecaoUnica(this)">
                <span class="slider"></span>
            </label>
        </div>
        <div class="item">
            <div class="info"><h3>Hs alto + Neck</h3><p>Hs acima da cabeça + Hs pescoço</p></div>
            <label class="switch">
                <input type="checkbox" class="funcao-unica" onchange="selecaoUnica(this)">
                <span class="slider"></span>
            </label>
        </div>
        <div class="item">
            <div class="info"><h3>Hs caveira</h3><p>Hs abaixo do pescoço</p></div>
            <label class="switch">
                <input type="checkbox" class="funcao-unica" onchange="selecaoUnica(this)">
                <span class="slider"></span>
            </label>
        </div>
        <div class="item">
            <div class="info"><h3>Hs Neck</h3><p>Hs no pescoço</p></div>
            <label class="switch">
                <input type="checkbox" class="funcao-unica" onchange="selecaoUnica(this)">
                <span class="slider"></span>
            </label>
        </div>
    </div>

    <!-- Seção: Opções Adicionais (Seleção Múltipla) -->
    <div class="card">
        <h2>Opções adicionais</h2>
        <p style="font-size: 11px; color: #666; margin-bottom: 10px;">(Pode selecionar várias opções)</p>
        
        <div class="item">
            <div class="info"><h3>Speed</h3><p>Seu personagem fica mais rápido</p></div>
            <label class="switch">
                <input type="checkbox" class="opcao-multipla">
                <span class="slider"></span>
            </label>
        </div>
        <div class="item">
            <div class="info"><h3>Antena</h3><p>A mão do personagem vira uma antena</p></div>
            <label class="switch">
                <input type="checkbox" class="opcao-multipla">
                <span class="slider"></span>
            </label>
        </div>
        <div class="item">
            <div class="info"><h3>Back Jump</h3><p>Pulo pra trás sem olhar pra trás</p></div>
            <label class="switch">
                <input type="checkbox" class="opcao-multipla">
                <span class="slider"></span>
            </label>
        </div>
    </div>

    <button class="btn-primary" id="btnInjetar">⚡ INJETAR</button>
</div>

<!-- SEÇÃO: ADB WI-FI -->
<div id="page-adb" class="page-section">
    <div class="card">
        <h2>CONEXÃO ADB WI-FI</h2>
        
        <div id="adb-status" class="adb-status">🔴 DESCONECTADO</div>

        <div class="adb-box">
            <h3>COMO ATIVAR</h3>
            <p>
                1. Abra Configurações > Opções do Desenvolvedor<br>
                2. Ative "Depuração sem fio" ou "Depuração Wi-Fi"<br>
                3. Toque em "Parear com código"<br>
                4. Digite o código de 6 dígitos abaixo
            </p>
        </div>

        <div class="adb-tabs">
            <div class="adb-tab active" id="tab-dividir" onclick="trocarAbaAdb('dividir')">DIVIDIR TELA</div>
            <div class="adb-tab" id="tab-notificacao" onclick="trocarAbaAdb('notificacao')">NOTIFICAÇÃO</div>
        </div>

        <div id="adb-dividir" class="adb-page active">
            <div class="adb-box">
                <p>Divida a tela para ver o código e digite-o abaixo.</p>
                <input id="adb-codigo" class="adb-input" type="number" placeholder="000000" maxlength="6">
                <button class="adb-btn" onclick="parearAdb()">CONECTAR</button>
            </div>
        </div>

        <div id="adb-notificacao" class="adb-page">
            <div class="adb-box">
                <p>Enviaremos uma notificação para você inserir o código.</p>
                <button class="adb-btn" onclick="mostrarToast('🔔 Notificação enviada!')">ENVIAR NOTIFICAÇÃO</button>
            </div>
        </div>
    </div>
</div>

<!-- SEÇÃO: BYPASS SS -->
<div id="page-bypass" class="page-section">
    <div class="card">
        <h2>BYPASS SS</h2>
        <div class="bypass-container">
            <div class="loading-spinner"></div>
            <div class="status-text">EM ANDAMENTO...</div>
            <p style="margin-top: 20px; color: #888;">Esta funcionalidade está sendo desenvolvida e estará disponível em breve.</p>
        </div>
    </div>
</div>

<!-- Toast -->
<div id="toast"></div>

<script>
/* ── Navegação e Menu ── */
function toggleMenu() {
    const menu = document.getElementById("menuLateral");
    const overlay = document.getElementById("overlay");
    if (menu.style.left === "0px") {
        menu.style.left = "-300px";
        overlay.style.display = "none";
    } else {
        menu.style.left = "0px";
        overlay.style.display = "block";
    }
}

function navegar(id) {
    document.querySelectorAll(".page-section").forEach(p => p.classList.remove("active"));
    document.getElementById("page-" + id).classList.add("active");
    
    document.querySelectorAll(".btn-menu").forEach(b => b.classList.remove("active"));
    document.getElementById("nav-" + id).classList.add("active");
    
    toggleMenu();
    window.scrollTo(0,0);
}

/* ── Regras de Seleção (NOVO) ── */
function selecaoUnica(elemento) {
    if (elemento.checked) {
        // Busca todos os checkboxes da classe 'funcao-unica'
        const funcoes = document.querySelectorAll('.funcao-unica');
        funcoes.forEach(f => {
            // Desmarca todos, exceto o que acabou de ser clicado
            if (f !== elemento) {
                f.checked = false;
            }
        });
    }
}

/* ── Lógica ADB ── */
function trocarAbaAdb(aba) {
    document.querySelectorAll(".adb-page").forEach(p => p.classList.remove("active"));
    document.querySelectorAll(".adb-tab").forEach(t => t.classList.remove("active"));
    
    document.getElementById("adb-" + aba).classList.add("active");
    document.getElementById("tab-" + aba).classList.add("active");
}

function parearAdb() {
    const cod = document.getElementById("adb-codigo").value;
    const status = document.getElementById("adb-status");
    if(cod.length === 6) {
        status.innerHTML = "🟢 CONECTADO";
        status.style.color = "#00ff88";
        mostrarToast("✅ Pareamento realizado!");
    } else {
        mostrarToast("⚠️ Digite os 6 dígitos!");
    }
}

/* ── Toast ── */
function mostrarToast(txt) {
    const t = document.getElementById("toast");
    t.innerHTML = txt;
    t.style.display = "block";
    setTimeout(() => { t.style.display = "none"; }, 2500);
}

/* ── Botão Injetar ── */
const btn = document.getElementById("btnInjetar");
btn.onclick = function() {
    const checks = document.querySelectorAll('input[type="checkbox"]');
    let ok = false;
    checks.forEach(c => { if(c.checked) ok = true; });

    if(!ok) {
        btn.innerHTML = "❌ ERRO: Selecione uma opção";
        btn.style.background = "#ff2b2b";
        setTimeout(() => { 
            btn.innerHTML = "⚡ INJETAR"; 
            btn.style.background = "#FF0000";
        }, 2000);
        return;
    }

    btn.innerHTML = "✅ INJETADO COM SUCESSO";
    btn.style.background = "#00cc55";
    setTimeout(() => { 
        btn.innerHTML = "⚡ INJETAR"; 
        btn.style.background = "#FF0000";
    }, 2000);
}
</script>

</body>
</html>
