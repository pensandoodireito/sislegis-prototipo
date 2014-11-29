sislegis-prototipo
==================

Protótipo de telas do SISLEGIS

Acesso a tela de login: http://pensandoodireito.github.io/sislegis-prototipo/Telas/login.html

Procedimentos executados para a publicação desse repositório a partir do protótipo criado:
```bash
git clone git@github.com:pensandoodireito/sislegis-prototipo.git
cd sislegis-prototipo
git checkout --orphan gh-pages
git rm -rf .
rsync -av ~/Downloads/_Prototipo\ -\ SISLEGIS/ .
git add .
git commit 'adição do protótipo 01'
git push origin gh-pages
```
