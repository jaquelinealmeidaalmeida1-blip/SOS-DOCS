# Como publicar este HTML online

Arquivos criados:

- painel-sos-docs.html — página estática pronta.

Opções rápidas para publicar:

1) Visualizar localmente (rápido)

Execute:

$ python3 -m http.server 8000

Depois abra: http://localhost:8000/painel-sos-docs.html

2) GitHub Pages (recomendado se usar GitHub)

Comandos básicos:

$ git init
$ git add painel-sos-docs.html
$ git commit -m "Add painel SOS DOCS"
# Crie um repositório no GitHub e adicione o remote, por exemplo:
$ git remote add origin git@github.com:SEU_USUARIO/SEU_REPO.git
$ git branch -M main
$ git push -u origin main

Em seguida ative GitHub Pages em Settings → Pages apontando para a branch `main`.

3) Netlify

- Acesse https://app.netlify.com e faça login. Arraste o arquivo `painel-sos-docs.html` para o painel de deploy (drag & drop) ou conecte seu repositório Git para deploy automático.

4) Surge (CLI simples)

Com Node/npm instalado:

$ npm install --global surge
$ surge painel-sos-docs.html --domain seu-subdominio.surge.sh

Posso continuar e:

- iniciar um repositório git local e commitar; ou
- ajudar a configurar push para um repo GitHub (preciso do URL ou token).

Diga qual opção prefere que eu proceda automaticamente.
