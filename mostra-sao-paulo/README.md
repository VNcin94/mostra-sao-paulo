# São Paulo — Mostra dos Estados do Brasil

Site escolar desenvolvido para o 9º ano do Colégio IPE Centro.

## Executar localmente
1. Extraia o arquivo ZIP.
2. Abra a pasta `mostra-sao-paulo` no VS Code.
3. Inicie um servidor local, por exemplo com a extensão Live Server.
4. Abra `index.html` pelo servidor. A subpágina do vídeo está em `/video/`.

Também é possível executar com Python, dentro desta pasta:
`python -m http.server 8000`
e acessar `http://localhost:8000`.

## Conteúdo
- `index.html`: landing page.
- `video/index.html`: página exclusiva do vídeo.
- `assets/video-da-turma.mp4`: vídeo original enviado pela turma.
- `assets/pesquisas/`: cópias dos quatro materiais de pesquisa originais.
- `assets/css/styles.css`: estilos responsivos.
- `assets/js/main.js`: menu mobile.

As fotografias ilustrativas são carregadas de imagens remotas do Unsplash; portanto, exigem conexão com a internet. O vídeo e os documentos de pesquisa estão armazenados localmente no projeto.
