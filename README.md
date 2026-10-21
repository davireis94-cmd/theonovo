CORRIDA DO THEO — CORRIDA + ESCOLHA DE PERSONAGEM

Você recebeu um ZIP com:
- index.html  (o jogo)
- README.txt  (este guia)

========================
1) TESTAR NO COMPUTADOR
========================
1. Baixe o ZIP e extraia (descompacte).
2. Dê dois cliques no arquivo "index.html".
3. O jogo abre no navegador.

Controles:
- PC: Espaço/↑ = pular | ↓ = abaixar
- Celular: botões PULAR e ABAIXAR

======================================
2) TRANSFORMAR EM LINK (CELULAR) — GH
======================================
Você vai subir o "index.html" no GitHub e ativar o GitHub Pages.

PASSO A PASSO:

A) Criar o repositório
1. Entre em https://github.com (crie conta se precisar)
2. Clique em "New repository"
3. Nome: jogo-theo
4. Marque: Public
5. Create repository

B) Enviar o arquivo
1. Dentro do repositório: "Add file" → "Upload files"
2. Selecione o arquivo "index.html" (APENAS ele)
3. "Commit changes"

C) Ativar o Pages
1. No repositório: Settings
2. Pages
3. Source: Deploy from a branch
4. Branch: main
5. Folder: / (root)
6. Save

D) Abrir o link
1. Espere ~1 minuto.
2. Em Settings → Pages, vai aparecer o link do site.
   Ex: https://SEU-USUARIO.github.io/jogo-theo/

=========================================
3) COLOCAR COMO APP NA TELA DO CELULAR
=========================================
- iPhone (Safari): Compartilhar → "Adicionar à Tela de Início"
- Android (Chrome): Menu ⋮ → "Adicionar à tela inicial"

=========================================
Se der 404
=========================================
Quase sempre é porque:
- o arquivo NÃO se chama index.html
- ou o Pages está apontando para pasta errada (tem que ser /root).


=========================================
CONVITE DA FESTA (pasta "convite")
=========================================
Link do convite (depois de publicado na branch main):
  https://davireis94-cmd.github.io/theonovo/convite/

Arquivos:
- convite/index.html   -> o convite com montagem de fotos e o formulário "Confirmar presença"
- convite/lista.html   -> página da família para ver quem confirmou (pede a senha)
- convite/fotos/       -> fotos recortadas e a imagem de prévia do WhatsApp (og.jpg)

Para mudar local, endereço, horário etc.:
- Abra convite/index.html e edite só o bloco "EDITE AQUI OS DADOS DA FESTA"
  (logo no começo do arquivo). Salve e faça o commit na branch main.

Onde ficam as confirmações:
- No projeto "festa-theo" do Supabase (https://supabase.com/dashboard), tabela "confirmacoes".
- Ou, mais fácil: abra convite/lista.html e digite a senha da família.
  A senha NÃO está neste repositório, porque ele é público.

Como funciona a segurança:
- Quem abre o convite só consegue INSERIR uma confirmação e ver o total
  de crianças confirmadas. Ninguém consegue ler nomes ou telefones sem a senha.
