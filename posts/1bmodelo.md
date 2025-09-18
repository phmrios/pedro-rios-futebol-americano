<!doctype html>
<html lang="pt-br">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- TÍTULO DA ABA/NAVEGADOR -->
  <title>{{CATEGORIA}}: {{TITULO}}</title>

  <!-- CSS global do site (mantenha o caminho relativo que você já usa) -->
  <link rel="stylesheet" href="../../assets/styles.css">

  <!-- SEO: descrição curta do post -->
  <meta name="description" content="{{DESCRICAO_CURTA}}">

  <!-- (Opcional) Metadados simples -->
  <meta name="author" content="Pedro Rios">
  <meta name="robots" content="index,follow">
</head>
<body>
  <!-- Topo do site -->
  <div class="topbar">
    <div class="brand">
      <div class="brand__title"><!-- (opcional) Nome do site --></div>
      <div class="brand__tag"><!-- (opcional) Slogan --></div>
    </div>
  </div>

  <!-- Navegação global -->
  <nav class="global">
    <div class="navwrap">
      <a href="../../index.html">Início</a>
      <a href="../../arquivo.html">Arquivo</a>
      <a href="../../about.html">Sobre</a>
    </div>
  </nav>

  <!-- Conteúdo principal -->
  <div class="container">
    <header class="hero">
      <!-- Título exibido do post -->
      <h2>{{TITULO}}</h2>

      <!-- Data (manual) • Categoria (fixa) -->
      <!-- Escolha UMA das categorias: Tática | Análise | Opinião -->
      <p class="article-meta">
        {{DATA}} • {{CATEGORIA}}
      </p>
    </header>

    <main>
      <!-- INTRODUÇÃO -->
      <p>{{LEAD_INTRODUCAO}}</p>

      <!-- CORPO Usar quantos paragrafos forem necessários -->
      <p>{{PARAGRAFO_1}}</p>
      <p>{{PARAGRAFO_2}}</p>
      <p>{{PARAGRAFO_3}}</p>

      <!-- (Opcional) Lista estruturada -->
      <!-- Remova se não precisar -->
      <ol>
        <li><strong>{{PONTO_CHAVE_1}}</strong>: {{DETALHE_1}}</li>
        <li><strong>{{PONTO_CHAVE_2}}</strong>: {{DETALHE_2}}</li>
        <li><strong>{{PONTO_CHAVE_3}}</strong>: {{DETALHE_3}}</li>
      </ol>

      <!-- Conclusão -->
      <p>{{CONCLUSAO}}</p>
    </main>

  </div>

  <!-- Rodapé -->
  <footer class="site">
    © {{ANO}} Pedro Rios
  </footer>
</body>
</html>
