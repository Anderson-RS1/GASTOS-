# Gastos do dia a dia — pacote do app (PWA)

Esses arquivos formam um app instalável. Hospedando eles de graça no GitHub
Pages, o app passa a salvar os gastos sozinho (sem precisar de backup manual)
e você instala um ícone no celular igual um app normal.

## Passo 1 — Criar o repositório no GitHub (5 min)

1. Crie uma conta em https://github.com (se ainda não tiver).
2. Clique em **New repository** (botão verde).
3. Dê um nome, por exemplo `gastos-diarios`. Marque como **Public**.
   Não marque "Add a README" (já temos os arquivos prontos).
4. Clique em **Create repository**.

## Passo 2 — Subir os arquivos

1. Na página do repositório recém-criado, clique em **uploading an existing file**
   (ou "Add file" → "Upload files").
2. Arraste todos os arquivos desta pasta: `index.html`, `manifest.json`,
   `service-worker.js`, `icon-192.png`, `icon-192-maskable.png`, `icon-512.png`,
   `icon-512-maskable.png`, `apple-touch-icon.png`.
3. Clique em **Commit changes**.

## Passo 3 — Ativar o GitHub Pages

1. No repositório, vá em **Settings** (aba no topo).
2. No menu lateral, clique em **Pages**.
3. Em "Branch", selecione `main` e a pasta `/ (root)`. Clique em **Save**.
4. Espere 1–2 minutos. A página vai mostrar um link tipo:
   `https://SEU-USUARIO.github.io/gastos-diarios/`
   Esse é o endereço do seu app.

## Passo 4 — Instalar no celular

**Android (Chrome):**
1. Abra o link do passo 3 no Chrome.
2. Toque nos três pontinhos (⋮) no canto superior direito.
3. Toque em **Adicionar à tela inicial** (ou "Instalar app").

**iPhone (Safari):**
1. Abra o link no Safari (tem que ser Safari, não Chrome).
2. Toque no ícone de compartilhar (o quadrado com a seta pra cima).
3. Toque em **Adicionar à Tela de Início**.

Pronto — vai aparecer um ícone no celular igual um app instalado, abre em
tela cheia, e os gastos ficam salvos sozinhos no aparelho, sem precisar de
backup manual.

## Levando os dados de um aparelho pra outro

O app salva os dados só naquele aparelho/navegador. Se quiser levar pra outro
celular, abra "+ exportar / importar backup" dentro do app, copie o texto, e
cole no mesmo campo no outro aparelho.

## Atualizando o app no futuro

Se algum dia quiser mudar algo (mais categorias, ajustes visuais etc.), é só
me pedir o arquivo `index.html` atualizado e subir de novo no GitHub
substituindo o antigo (Add file → Upload files, mesmo nome sobrescreve).
