<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
<title>Convite Especial - [NOME DO ANIVERSARIANTE]</title>

<!-- Compartilhamento WhatsApp / Redes -->
<meta property="og:type" content="website" />
<meta property="og:title" content="Convite Especial - [NOME]" />
<meta property="og:description" content="Clique para abrir o seu convite!" />
<meta property="og:image" content="capa.jpg" />

<style>
html,body{
  margin:0; padding:0;
  width:100%; height:100%;
  background:#000;
  overflow:hidden;
  font-family: system-ui, -apple-system, sans-serif;
}

.phone{
  width:100vw; height:100vh; height:100dvh;
  display:flex; align-items:center; justify-content:center;
  background:#000;
}

.stage{
  position:relative;
  aspect-ratio: 9 / 16;
  width:auto;
  max-width:100%;
  max-height:100dvh;
  background:#000;
  overflow:hidden;
}

.stage img, .stage video{
  position:absolute; inset:0;
  width:100%; height:100%;
  object-fit:cover;
  display:none;
  user-select:none;
}

.fade-transition {
  opacity: 0;
  transition: opacity 0.6s ease;
}
.fade-transition.show {
  opacity: 1;
  display: block !important;
}
.show { display:block !important; }

/* Camada de botões */
.btnLayer{
  position:absolute; inset:0;
  width:100%; height:100%;
  pointer-events:none;
  z-index:100;
}
.btn-inv{
  position:absolute;
  display:block;
  pointer-events:auto;
  background: transparent;
  /* DICA: troque 'transparent' por 'rgba(255,0,0,0.3)' para enxergar os botões ao calibrar */
  -webkit-tap-highlight-color: transparent;
}

.pg3-only, .pg4-only { display:none; }
body.pg3 .pg3-only { display:block; }
body.pg4 .pg4-only { display:block; }

/* Botão de Início (cobre a tela toda) */
#startBtn{
  position:fixed; inset:0;
  border:0; background:transparent;
  z-index:200; cursor:pointer;
}
.started #startBtn { display:none !important; }

/* Botão Pular Vídeo */
#skipIntroBtn{
  position:absolute; right:12px; bottom:24px;
  z-index:150; display:none;
  border:0; border-radius:999px;
  background:rgba(0,0,0,0.7); color:#fff;
  font-size:12px; font-weight:bold;
  padding:8px 14px; cursor:pointer;
}
</style>
</head>
<body>

<div class="phone">
  <div class="stage">
    <!-- Capa Estática -->
    <img id="pdCover" class="show" src="capa.jpg" alt="Capa">
    <button id="startBtn" aria-label="Abrir convite"></button>

    <!-- Vídeo de Abertura -->
    <video id="video" class="fade-transition" src="video.mp4" playsinline preload="auto"></video>
    <button id="skipIntroBtn" type="button">Pular abertura</button>

    <!-- Páginas -->
    <img id="pd3" class="fade-transition" src="pagina3.jpg" alt="Página Principal">
    <img id="pd4" class="fade-transition" src="pagina4.jpg" alt="Página Presentes">

    <!-- BOTÕES INTERATIVOS -->
    <div class="btnLayer">
      
      <!-- BOTÕES DA PÁGINA 3 (PRINCIPAL) -->
      <!-- Como ir para Página 4 (Presentes) -->
      <a class="btn-inv pg3-only" href="#" onclick="mostrarPg4(); return false;" 
         style="left:36%; top:71%; width:27%; height:18%;"></a>

      <!-- Link Localização (Google Maps) -->
      <a class="btn-inv pg3-only" href="LINK_DO_SEU_GOOGLE_MAPS" target="_blank" rel="noopener" 
         style="left:7%; top:70%; width:27%; height:20%;"></a>

      <!-- Link WhatsApp (Confirmar Presença) -->
      <a class="btn-inv pg3-only" href="https://wa.me/55SEUNUMERO?text=Ol%C3%A1!%20Quero%20confirmar%20minha%20presen%C3%A7a!" target="_blank" rel="noopener" 
         style="left:64%; top:70%; width:30%; height:21%;"></a>

      <!-- BOTÕES DA PÁGINA 4 (PRESENTES / PIX) -->
      <!-- Voltar para Página 3 -->
      <a class="btn-inv pg4-only" href="#" onclick="mostrarPg3(); return false;" 
         style="left:30%; top:87%; width:42%; height:11%;"></a>

      <!-- Botão Copiar Chave Pix -->
      <a class="btn-inv pg4-only" href="#" onclick="copiarPix('SUA_CHAVE_PIX_AQUI'); return false;" 
         style="left:21%; top:71%; width:58%; height:9%;"></a>

      <!-- Botão Lista de Presentes Online -->
      <a class="btn-inv pg4-only" href="LINK_DA_LISTA_DE_PRESENTES" target="_blank" rel="noopener" 
         style="left:10%; top:54%; width:36%; height:8%;"></a>

    </div>
  </div>
</div>

<!-- Música de Fundo -->
<audio id="mus" src="musica.mp3" loop preload="auto"></audio>

<script>
const cover = document.getElementById("pdCover");
const startBtn = document.getElementById("startBtn");
const vid = document.getElementById("video");
const skipBtn = document.getElementById("skipIntroBtn");
const mus = document.getElementById("mus");

// Iniciar convite e liberar som
startBtn.addEventListener("click", async () => {
  document.body.classList.add("started");
  
  try {
    mus.volume = 0.6;
    await mus.play();
  } catch(e){}

  cover.classList.remove("show");

  if(vid && vid.getAttribute("src")){
    vid.classList.add("show");
    skipBtn.style.display = "block";
    try {
      await vid.play();
    } catch(e){
      goToPage3();
    }
  } else {
    goToPage3();
  }
});

// Ao terminar o vídeo ou clicar em pular
if(vid){
  vid.addEventListener("ended", goToPage3);
}
skipBtn.addEventListener("click", () => {
  if(vid) vid.pause();
  goToPage3();
});

function goToPage3(){
  if(vid) vid.classList.remove("show");
  skipBtn.style.display = "none";
  mostrarPg3();
}

function mostrarPg3(){
  document.body.classList.remove("pg4");
  document.body.classList.add("pg3");
  document.getElementById("pd4").classList.remove("show");
  const p3 = document.getElementById("pd3");
  p3.classList.add("show");
}

function mostrarPg4(){
  document.body.classList.remove("pg3");
  document.body.classList.add("pg4");
  document.getElementById("pd3").classList.remove("show");
  const p4 = document.getElementById("pd4");
  p4.classList.add("show");
}

// Função de Copiar o Pix
function copiarPix(chave){
  if(!chave) return;
  navigator.clipboard.writeText(chave).then(() => {
    alert("✅ Chave Pix copiada com sucesso!");
  }).catch(() => {
    prompt("Copie a chave Pix abaixo:", chave);
  });
}
</script>
</body>
</html>
