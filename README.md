# Doutor do Cabelo

Protótipo front-end de um site institucional para clínica capilar, focado em layout responsivo e usabilidade. Este repositório contém a interface estática (HTML, CSS e JavaScript leves) para apresentação de serviços, agendamento de contato e informações institucionais.

Badges
- ![HTML](https://img.shields.io/badge/language-HTML-orange)
- ![CSS](https://img.shields.io/badge/language-CSS-blue)
- ![JavaScript](https://img.shields.io/badge/language-JS-yellow)

Sumário
- Sobre
- Demonstração
- Tecnologias
- Funcionalidades
- Executando localmente
- Estrutura do projeto
- Acessibilidade e responsividade
- Como contribuir
- Licença
- Contato

Sobre
Este projeto é um protótipo de front-end pensado para clínicas capilares: foco em usabilidade, comunicação clara dos serviços e adaptação a diferentes tamanhos de tela (desktop, tablet e mobile). Ideal para apresentação a clientes ou como base para integração com back-end posteriormente.

Demonstração
- Se o repositório estiver publicado (ex.: GitHub Pages), o link de demonstração aparecerá aqui.
- Para ver localmente, siga as instruções abaixo.

Tecnologias
- HTML5
- CSS3 (flexbox / grid, media queries)
- JavaScript (vanilla — interações leves)
- Imagens e ícones (pastas /assets ou /images)

Funcionalidades principais
- Layout responsivo (mobile-first)
- Seções: home, serviços, equipe, depoimentos, contato/agenda
- Formulário de contato (front-end; sem back-end para envio)
- Navegação fixa / menu adaptável para mobile
- Uso de componentes reutilizáveis (cards, botões, modais)

Executando localmente
Opção 1 — abrir direto no navegador
- Abra o arquivo `index.html` no seu navegador (útil para protótipos simples).
Opção 2 — servidor local simples (recomendado para evitar problemas com fetchs)
- Python 3:
  ```bash
  python -m http.server 8000
  # depois abra http://localhost:8000
