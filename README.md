<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tellink Telecom</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f4;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #c00000;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      background-color: #a00000;
      padding: 15px 0;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      font-size: 18px;
      text-transform: uppercase;
      padding: 5px 10px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    nav a:hover {
      background-color: #c00000;
    }
    .hero {
      background: #f8f8f8;
      padding: 80px 20px;
      text-align: center;
    }
    .plans, .services, .about, .contact {
      padding: 40px 20px;
      display: none;
    }
    .plans-container, .services-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .plan, .service {
      border: 2px solid #c00000;
      border-radius: 8px;
      padding: 25px;
      width: 300px;
      background-color: white;
      text-align: center;
      transition: transform 0.3s ease;
    }
    .plan:hover, .service:hover {
      transform: scale(1.05);
    }
    .cta-button {
      background-color: #c00000;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      display: inline-block;
      margin-top: 20px;
    }
    .whatsapp-float, .instagram-float {
      position: fixed;
      width: 60px;
      height: 60px;
      bottom: 20px;
      background-color: #25d366;
      color: white;
      border-radius: 50%;
      text-align: center;
      font-size: 30px;
      line-height: 60px;
      z-index: 1000;
    }
    .instagram-float {
      bottom: 100px;
      background-color: #e1306c;
    }
    footer {
      background-color: #c00000;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .plan i, .service i {
      font-size: 40px;
      color: #c00000;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>Tellink Telecom</h1>
  <p>Internet rápida, estável e com o melhor atendimento!</p>
</header>

<nav>
  <a href="javascript:void(0);" onclick="showSection('planos')">Planos Residenciais</a>
  <a href="javascript:void(0);" onclick="showSection('empresarial')">Soluções Empresariais</a>
  <a href="javascript:void(0);" onclick="showSection('quemsomos')">Quem Somos</a>
  <a href="javascript:void(0);" onclick="showSection('contato')">Contato</a>
</nav>

<section id="planos" class="plans">
  <h2 style="text-align:center; color:#c00000;">Planos Residenciais</h2>
  <div class="plans-container">
    <div class="plan">
      <i class="fas fa-wifi"></i>
      <h2>100 Mega</h2>
      <p>R$ 49,90</p>
      <p>Ideal para quem navega e usa redes sociais com moderação.</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Saiba Mais</a>
    </div>
    <div class="plan">
      <i class="fas fa-wifi"></i>
      <h2>150 Mega</h2>
      <p>R$ 59,90</p>
      <p>Mais velocidade para quem usa streaming e chamadas de vídeo.</p>
      <p><strong>Promoção:</strong> R$ 29,95 na primeira parcela</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Saiba Mais</a>
    </div>
    <div class="plan">
      <i class="fas fa-wifi"></i>
      <h2>300 Mega</h2>
      <p>R$ 69,90</p>
      <p>Conexão fluida para assistir filmes, jogar online e trabalhar de casa.</p>
      <p><strong>Promoção:</strong> R$ 34,95 na primeira parcela</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Saiba Mais</a>
    </div>
    <div class="plan">
      <i class="fas fa-wifi"></i>
      <h2>450 Mega</h2>
      <p>R$ 79,90</p>
      <p>Alta performance para famílias conectadas e multitarefas digitais.</p>
      <p><strong>Promoção:</strong> R$ 39,95 na primeira parcela</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Saiba Mais</a>
    </div>
    <div class="plan">
      <i class="fas fa-bolt"></i>
      <h2>600 Mega</h2>
      <p>R$ 99,90</p>
      <p>Desempenho superior com <strong>Wi-Fi 6</strong>, ideal para casas com muitos dispositivos.</p>
      <p><strong>Promoção:</strong> R$ 49,90 nas 4 primeiras parcelas</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Quero esse plano!</a>
    </div>
    <div class="plan">
      <i class="fas fa-network-wired"></i>
      <h2>1 Giga</h2>
      <p>R$ 199,90</p>
      <p>Plano corporativo com <strong>Wi-Fi 6</strong> e estabilidade premium.</p>
      <p>Inclui 2 câmeras com analítico ou alarmes para segurança empresarial.</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Quero esse plano!</a>
    </div>
  </div>
</section>

<section id="empresarial" class="services">
  <h2 style="text-align:center; color:#c00000;">Soluções Empresariais</h2>
  <div class="services-container">
    <div class="service">
      <i class="fas fa-link"></i>
      <h3>Link Dedicado</h3>
      <p>Garantia de banda e estabilidade para sua empresa.</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Saiba Mais</a>
    </div>
    <div class="service">
      <i class="fas fa-exchange-alt"></i>
      <h3>Peering Tellink</h3>
      <p>Conexão direta com pontos de troca de tráfego.</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Saiba Mais</a>
    </div>
    <div class="service">
      <i class="fas fa-tools"></i>
      <h3>Consultoria Técnica</h3>
      <p>Especialistas em cabeamento e redes para seu negócio.</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Saiba Mais</a>
    </div>
    <div class="service">
      <i class="fas fa-video"></i>
      <h3>Vídeo Monitoramento com IA</h3>
      <p>Câmeras inteligentes com reconhecimento de pessoas e veículos.</p>
      <a href="https://wa.me/5583981286950" class="cta-button">Saiba Mais</a>
    </div>
  </div>
</section>

<section id="quemsomos" class="about">
  <h2 style="text-align:center; color:#c00000;">Quem Somos</h2>
  <p style="text-align:center; max-width:800px; margin:auto;">
    Fundada em 2019, a Tellink Telecom nasceu com o propósito de oferecer internet de qualidade, atendimento ágil e qualificado. Além disso, trabalhamos com consultoria para empresas de pequeno e grande porte, oferecendo soluções personalizadas e inovadoras.
  </p>
</section>

<section id="contato" class="contact">
  <p style="text-align:center;">Fale conosco:</p>
  <div style="text-align:center;">
    <a href="https://wa.me/5583981286950" class="cta-button">WhatsApp</a>
    <a href="https://www.instagram.com/tellink_telecom" class="cta-button" style="background-color:#e1306c;">Instagram</a>
  </div>
</section>

<a href="https://wa.me/5583981286950" class="whatsapp-float" target="_blank"><i class="fab fa-whatsapp"></i></a>
<a href="https://www.instagram.com/tellink_telecom" class="instagram-float" target="_blank"><i class="fab fa-instagram"></i></a>

<!-- Chat Flutuante -->
<script>
  window.intercomSettings = { app_id: "your_app_id" };
</script>
<script>(function(){var w=window;var ic=w.Intercom;if(typeof ic==="function"){ic('reattach_activator');ic('update',intercomSettings);}else{var d=document;var i=function(){i.c(arguments)};i.q=[];i.c=function(args){i.q.push(args)};w.Intercom=i;function l(){var s=d.createElement('script');s.type='text/javascript';s.async=true;s.src='https://widget.intercom.io/widget/your_app_id';var x=d.getElementsByTagName('script')[0];x.parentNode.insertBefore(s,x);}l();}})()</script>

<footer>
  <p>&copy; 2019 Tellink Telecom. Todos os direitos reservados.</p>
</footer>

<script>
  function showSection(sectionId) {
    document.querySelectorAll('.plans, .services, .about, .contact').forEach(s => s.style.display = 'none');
    document.getElementById(sectionId).style.display = 'block';
  }

  window.onload = () => showSection('planos');
</script>

</body>
</html>
