<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Angela Bernardete Batista | Advocacia</title>
  <meta name="description" content="Escritório de advocacia de Angela Bernardete Batista. Atendimento ético, personalizado e comprometido com a defesa dos seus direitos.">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <header class="header" id="topo">
    <div class="container header__inner">
      <a href="#topo" class="logo" aria-label="Angela Bernardete Batista - Advocacia">
        <span class="logo__mark">ABB</span>
        <span class="logo__text">Angela Bernardete Batista<small>Advocacia</small></span>
      </a>
      <button class="menu-toggle" id="menuToggle" aria-label="Abrir menu" aria-expanded="false">
        <span></span><span></span><span></span>
      </button>
      <nav class="nav" id="nav">
        <a href="#sobre">Sobre</a>
        <a href="#areas">Áreas de atuação</a>
        <a href="#equipe">Equipe</a>
        <a href="#contato" class="btn btn--small">Fale conosco</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero__inner">
        <p class="eyebrow">Advocacia</p>
        <h1>Defesa dos seus direitos com ética, clareza e dedicação.</h1>
        <p class="hero__lead">Atendimento personalizado, acompanhamento próximo de cada caso e compromisso com resultados justos.</p>
        <div class="hero__actions">
          <a href="#contato" class="btn">Agendar atendimento</a>
          <a href="#areas" class="btn btn--ghost">Conhecer as áreas</a>
        </div>
      </div>
    </section>

    <section class="section" id="sobre">
      <div class="container grid grid--2">
        <div class="reveal">
          <p class="eyebrow">Sobre o escritório</p>
          <h2>Compromisso com cada cliente</h2>
        </div>
        <div class="reveal">
          <p>O escritório Angela Bernardete Batista Advocacia atua com foco na escuta atenta, na transparência e na busca da melhor solução jurídica para cada situação.</p>
          <p>Cada caso é tratado de forma individual, com linguagem acessível e informações claras em todas as etapas, do primeiro contato até a conclusão do processo.</p>
          <ul class="values">
            <li><strong>Ética</strong> e sigilo profissional</li>
            <li><strong>Transparência</strong> no acompanhamento</li>
            <li><strong>Dedicação</strong> a cada detalhe</li>
          </ul>
        </div>
      </div>
    </section>

    <section class="section section--alt" id="areas">
      <div class="container">
        <div class="section__head reveal">
          <p class="eyebrow">Áreas de atuação</p>
          <h2>Como podemos ajudar</h2>
        </div>
        <div class="cards">
          <article class="card reveal">
            <h3>Direito Civil</h3>
            <p>Atuação em Direito Civil, com ênfase em sucessões e divórcio.</p>
          </article>
          <article class="card reveal">
            <h3>Sucessões</h3>
            <p>Inventário, partilha de bens, testamento e planejamento sucessório.</p>
          </article>
          <article class="card reveal">
            <h3>Divórcio</h3>
            <p>Divórcio consensual e litigioso, partilha de bens, guarda e pensão alimentícia.</p>
          </article>
        </div>
      </div>
    </section>

    <section class="section" id="equipe">
      <div class="container">
        <div class="section__head reveal">
          <p class="eyebrow">Nossa equipe</p>
          <h2>Quem atende você</h2>
        </div>
        <div class="team">
          <article class="person reveal">
            <div class="person__avatar" aria-hidden="true">AB</div>
            <h3>Angela Bernardete Batista</h3>
            <p class="person__role">Advogada</p>
            <p class="person__oab">OAB/SP nº 265.224</p>
          </article>
          <article class="person reveal">
            <div class="person__avatar" aria-hidden="true">MG</div>
            <h3>Matheus Henrique Castelli Garcia</h3>
            <p class="person__role">Assistente Jurídico</p>
            <p class="person__oab"><a href="https://wa.me/5518996151075" target="_blank" rel="noopener">(18) 99615-1075</a></p>
          </article>
        </div>
      </div>
    </section>

    <section class="section section--dark" id="contato">
      <div class="container grid grid--2">
        <div class="reveal">
          <p class="eyebrow eyebrow--light">Contato</p>
          <h2>Vamos conversar sobre o seu caso</h2>
          <p>Envie uma mensagem e retornaremos o mais breve possível. As informações enviadas são tratadas com sigilo.</p>
          <ul class="contact-list">
            <li><span>Telefone / WhatsApp</span> <a href="https://wa.me/5518981937959" target="_blank" rel="noopener">(18) 98193-7959</a></li>
            <li><span>E-mail</span> contato@seudominio.com.br</li>
            <li><span>Endereço</span> Rua Exemplo, 000 - Cidade/UF</li>
            <li><span>Horário</span> Segunda a sexta, 9h às 18h</li>
          </ul>
        </div>
        <form class="form reveal" id="contactForm" novalidate>
          <label>Nome
            <input type="text" name="nome" required autocomplete="name">
          </label>
          <label>E-mail
            <input type="email" name="email" required autocomplete="email">
          </label>
          <label>Telefone
            <input type="tel" name="telefone" id="telefone" placeholder="(00) 00000-0000" autocomplete="tel">
          </label>
          <label>Mensagem
            <textarea name="mensagem" rows="4" required></textarea>
          </label>
          <button type="submit" class="btn">Enviar mensagem</button>
          <p class="form__status" id="formStatus" role="status" aria-live="polite"></p>
        </form>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container footer__inner">
      <p>&copy; <span id="ano"></span> Angela Bernardete Batista Advocacia. Todos os direitos reservados.</p>
      <p class="footer__note">Este site tem caráter exclusivamente informativo e não constitui aconselhamento jurídico.</p>
    </div>
  </footer>

  <script src="script.js"></script>
  (function () {
  "use strict";

  // Ano atual no rodapé
  var ano = document.getElementById("ano");
  if (ano) ano.textContent = new Date().getFullYear();

  // Menu mobile
  var toggle = document.getElementById("menuToggle");
  var nav = document.getElementById("nav");

  function closeMenu() {
    toggle.classList.remove("is-open");
    nav.classList.remove("is-open");
    toggle.setAttribute("aria-expanded", "false");
  }

  toggle.addEventListener("click", function () {
    var open = nav.classList.toggle("is-open");
    toggle.classList.toggle("is-open", open);
    toggle.setAttribute("aria-expanded", String(open));
  });

  nav.querySelectorAll("a").forEach(function (link) {
    link.addEventListener("click", closeMenu);
  });

  // Sombra no cabeçalho ao rolar
  var header = document.querySelector(".header");
  function onScroll() {
    header.classList.toggle("is-scrolled", window.scrollY > 10);
  }
  window.addEventListener("scroll", onScroll, { passive: true });
  onScroll();

  // Animação de entrada dos elementos
  var items = document.querySelectorAll(".reveal");
  if ("IntersectionObserver" in window) {
    var observer = new IntersectionObserver(function (entries) {
      entries.forEach(function (entry) {
        if (entry.isIntersecting) {
          entry.target.classList.add("is-visible");
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.12 });
    items.forEach(function (el) { observer.observe(el); });
  } else {
    items.forEach(function (el) { el.classList.add("is-visible"); });
  }

  // Máscara de telefone brasileiro
  var tel = document.getElementById("telefone");
  tel.addEventListener("input", function () {
    var d = tel.value.replace(/\D/g, "").slice(0, 11);
    var out = d;
    if (d.length > 10) {
      out = "(" + d.slice(0, 2) + ") " + d.slice(2, 7) + "-" + d.slice(7);
    } else if (d.length > 6) {
      out = "(" + d.slice(0, 2) + ") " + d.slice(2, 6) + "-" + d.slice(6);
    } else if (d.length > 2) {
      out = "(" + d.slice(0, 2) + ") " + d.slice(2);
    } else if (d.length > 0) {
      out = "(" + d;
    }
    tel.value = out;
  });

  // Formulário de contato (validação e envio por e-mail)
  var form = document.getElementById("contactForm");
  var status = document.getElementById("formStatus");
  var EMAIL_DESTINO = "contato@seudominio.com.br"; // troque pelo e-mail real

  form.addEventListener("submit", function (e) {
    e.preventDefault();
    status.classList.remove("is-error");

    var nome = form.nome;
    var email = form.email;
    var mensagem = form.mensagem;
    var valido = true;

    [nome, email, mensagem].forEach(function (campo) {
      var ok = campo.value.trim() !== "";
      if (campo === email) ok = ok && /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(campo.value);
      campo.classList.toggle("is-invalid", !ok);
      if (!ok) valido = false;
    });

    if (!valido) {
      status.textContent = "Preencha nome, e-mail válido e mensagem.";
      status.classList.add("is-error");
      return;
    }

    var corpo =
      "Nome: " + nome.value.trim() +
      "\nE-mail: " + email.value.trim() +
      "\nTelefone: " + form.telefone.value.trim() +
      "\n\n" + mensagem.value.trim();

    window.location.href =
      "mailto:" + EMAIL_DESTINO +
      "?subject=" + encodeURIComponent("Contato pelo site - " + nome.value.trim()) +
      "&body=" + encodeURIComponent(corpo);

    status.textContent = "Abrindo seu aplicativo de e-mail para enviar a mensagem...";
    form.reset();
  });
})();
</body>
</html>
