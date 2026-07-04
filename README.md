# Pura Tita — Site para GitHub Pages

Estrutura multipágina preparada para GitHub Pages:

- `index.html`
- `biofeedback.html`
- `alimentacao.html`
- `familia.html`
- `carolina.html`
- `contactos.html`
- `styles.css`
- `script.js`
- `assets/images/`

## O que esta versão já inclui

- logótipo no cabeçalho e no hero inicial
- favicon para o browser
- páginas separadas para Biofeedback, Alimentação, Família, Carolina e Contactos
- formulário preparado para Formspree
- SEO base: títulos, descrições, Open Graph e Twitter Cards
- imagens da secção Família com perfis humanos e cães em biofeedback (incluindo Xafas, beagle, pastor alemão e terrier)

## GitHub Pages

1. Criar um repositório no GitHub.
2. Carregar todos os ficheiros desta pasta.
3. Em **Settings > Pages**, escolher a branch principal e a pasta `/root`.
4. Guardar.

## Formspree

O formulário já está estruturado. Para o ativar:

1. Criar uma conta em [https://formspree.io](https://formspree.io).
2. Criar um novo formulário.
3. Copiar o endpoint, por exemplo: `https://formspree.io/f/abcde123`.
4. Abrir `contactos.html` e substituir:

```html
<form action="https://formspree.io/f/SEU_FORM_ID" method="POST">
```

pelo endpoint real.

## SEO

Os metadados base estão definidos em cada página. Depois de publicar, recomenda-se substituir o domínio placeholder `https://SEU-UTILIZADOR.github.io/pura-tita-site/` pelo domínio final do GitHub Pages.

## Versão v6

Esta versão acrescenta:

- página `experiencias.html`
- página `marcas-empresas.html`
- botão WhatsApp flutuante
- bloco editorial para Instagram
- mapa Google integrado na página de contactos
- secção Família separada entre perfis humanos e cães em biofeedback
- imagens de cães com a fita/arnês aplicado na barriga
- design mais premium/editorial

### Instagram real

O bloco de Instagram está preparado como grelha editorial. Para um feed real, recomenda-se usar um widget externo como Elfsight, LightWidget ou SnapWidget e substituir a grelha pelo código fornecido pelo serviço.

### Google Maps

O mapa usa a morada por pesquisa. Depois de existir perfil Google Business, pode ser substituído pelo embed oficial do perfil.

### WhatsApp

O botão usa o número `+351 914 849 575`. Para alterar a mensagem ou o número, editar o link `wa.me` nos ficheiros HTML.


### Ajustes v7
- hero inicial com Carolina e Xafas
- integração do Instagram @puratita.familycare
- página de alimentação com fotografias de pratos, sem presença de cães
- página de experiências com showcooking e desporto
- página Marcas & Empresas com imagem única de catering
- página Família focada em tutores e animais em sessão de biofeedback


### Correções v8
- Imagem inicial corrigida para Carolina com o Xafas.
- Separador Alimentação corrigido para usar apenas imagens de comida, sem cão.
- A frase solicitada foi revista sem o termo indicado.
- Separador Experiências corrigido com imagem de showcooking e fotografia de desporto.
- Separador Marcas & Empresas corrigido com imagem única de catering.
- Separador Família mantém a frase "Tutores e animais em sessão de biofeedback".
- Instagram integrado com ligação direta para https://www.instagram.com/puratita.familycare/

Nota Formspree: o formulário está tecnicamente ligado ao padrão Formspree, mas precisa do endpoint real da conta para ficar ativo. Substituir SEU_FORM_ID pelo ID fornecido pelo Formspree.


## Versão v10

Revisão final página a página:
- homepage mantém Xafas apenas como imagem principal/hero
- secção Biofeedback combina tutores e animais
- secção Família combina tutores e animais sem duplicar Xafas na mesma área
- Alimentação mantém apenas imagens de comida
- Experiências usa showcooking e desporto
- Marcas & Empresas usa imagem de catering
- Instagram integrado com @puratita.familycare


## Versão v11

Integração da marcação online:
- todos os botões com texto `Marcar sessão` passam a abrir o link público do Google Calendar
- link usado: `https://calendar.app.google/uFUYTp2zuA6HXyQT7`
- a página `contactos.html` inclui um bloco adicional `Marcação online` com botão `Ver horários disponíveis`
- o link abre numa nova janela/aba com `target="_blank"` e `rel="noopener"`
