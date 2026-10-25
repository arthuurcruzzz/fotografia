# Arthur Cruz — piloto do portfólio

Site estático responsivo. Página inicial e galerias independentes em `/eventos/`, `/ensaio-corporativo/` e `/fotografia-esportiva/`.

WhatsApp: +55 71 99280-9439. Todos os links usam `wa.me/5571992809439`, com mensagens específicas nas galerias.

Os arquivos da identidade visual são originais fornecidos pelo cliente. A galeria corporativa usa as nove fotos fornecidas por Arthur Cruz (IMG_7580, IMG_7574, IMG_7575, IMG_7586, IMG_7589, IMG_7587, IMG_7588, IMG_7590 e IMG_7591). Elas foram dimensionadas para web, com proporção e cores preservadas. A galeria Eventos usa as fotos IMG_2187, IMG_2302 e IMG_2068 fornecidas por Arthur. A abertura usa o retrato FINC (1144) de Arthur. A galeria Fotografia esportiva está preparada para receber fotos e sinalizada como em breve. O antigo endereço `/retrato/` redireciona para a nova categoria. Não há fotografias ilustrativas em exibição.

## Alterar o portfólio

- Substitua as imagens em `dist/assets/` e atualize os textos alternativos nos HTMLs.
- Para adicionar fotos, duplique um botão `.gallery-photo` dentro de `.gallery-grid`, atualize `data-photo`, a imagem e os rótulos acessíveis. Atualize também o total de imagens visível.
- A ampliação das fotos detecta automaticamente os botões de cada galeria.
- Cores e layout estão em `dist/style.css` e `dist/brand.css`; navegação e ampliação em `dist/app.js`.
- Para visualizar, sirva `dist/` com um servidor HTTP. Os links começam na raiz do domínio.

A versão hospedada pelo Sites é privada por padrão.

## Revisão da identidade visual

Fundo #F1F1F1, preto #000000 e vermelho #DC141C, conferidos nos arquivos originais. A seção Sobre mim usa o retrato FINC (1149) de Arthur, com a coluna gráfica ao lado. A logo no cabeçalho e rodapé usa o SVG original LOGO HORIZONTAL 1.

A seção de contato usa o retrato FINC (1147) de Arthur (`.contact-portrait`). O texto Sobre mim informa os três anos de experiência e a proposta de posicionamento estratégico.

## Animações de rolagem

Os elementos entram com opacidade e deslocamento para cima, repetindo a animação ao descer e subir. Dois observadores controlam entrada e reinício fora da tela, evitando oscilações na borda. A preferência do dispositivo por movimento reduzido desativa o efeito; sem JavaScript, o conteúdo permanece visível.

A abertura usa uma moldura com detalhes gráficos da marca e sem frases sobre o retrato. Ícone de WhatsApp: Bootstrap Icons (MIT; licença incluída).
