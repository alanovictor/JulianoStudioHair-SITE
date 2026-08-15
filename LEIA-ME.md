# Juliano Studio Hair — site

## O que trocar antes de publicar

1. **Imagem de fundo do topo (hero)**
   - Troque `assets/hero-bg-placeholder.jpg` pela foto real do estúdio
     (a mesma ideia da sua referência: alguém cortando cabelo, ambiente
     aconchegante). Ideal: 1920px de largura, comprimida (JPEG qualidade
     75–85%) para carregar rápido.

2. **Vídeo institucional (opcional)**
   - O botão "Assista ao vídeo" abre um pop-up com um vídeo.
   - Coloque seu vídeo em `assets/promo-video.mp4`. Se não adicionar nada,
     o botão ainda abre o pop-up, só que sem vídeo — então vale colocar
     um arquivo ali (ou eu removo o botão, se preferir).

3. **Feed do Instagram**
   - Acesse https://lightwidget.com, conecte a conta profissional
     `@julianostudiohair` (Business ou Creator) e gere um widget em grade,
     tema escuro.
   - Copie o "Widget ID" e cole em `index.html`, na linha do `<iframe id="igWidget" ...>`,
     substituindo `SEU-WIDGET-ID` na URL.
   - Sem essa troca, aparece uma grade de exemplo no lugar (não quebra o layout).

4. **WhatsApp e telefone**
   - Em `index.html`, troque `5500000000000` (aparece em 3 lugares) pelo
     número real com DDI+DDD, só números. Ex: `551199998888`.

5. **Endereço e horário**
   - Seção "Contato" no final do `index.html` — edite o texto direto.

## Comportamentos já implementados

- **Menu superior**: transparente no topo da página; ao rolar, fica com
  fundo preto suave (com transição), pra continuar legível sobre qualquer
  seção.
- **Cliques no menu** (Início, Sobre, Contato): rolagem suave até a seção,
  já com espaço reservado pra não ficar escondida atrás do menu fixo.
- **Botão "Assista ao vídeo"**: abre um pop-up (modal) com o vídeo, sem
  sair da página.

## Como subir na Hostinger

1. Acesse **hpanel.hostinger.com** → seu site → **Gerenciador de Arquivos**.
2. Entre na pasta **public_html**.
3. Compacte toda esta pasta (`index.html`, `css/`, `js/`, `assets/`) em um `.zip`.
4. Clique em **Upload**, envie o `.zip`.
5. Clique com o botão direito no `.zip` dentro do Gerenciador → **Extract**.
6. Confirme que `index.html` ficou direto dentro de `public_html` (não numa subpasta).
7. Acesse seu domínio no navegador para conferir.

Qualquer ajuste de cor, texto ou seção, é só pedir.
