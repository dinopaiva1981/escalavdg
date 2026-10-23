# Escala 5×2 · Videografismo

Plataforma da escala de plantões, folgas e férias do departamento de Videografismo.

**Acesso:** abra o link do GitHub Pages deste repositório.

- **Colaborador:** clique em *Colaborador* para ver a escala, o calendário e as férias e baixar os PDFs.
- **Gestor:** entre com a senha para editar e publicar.

## Como o gestor publica

1. Entre como **Gestor**.
2. Na primeira vez em cada computador, vá em **Exportar → Configurar GitHub** e informe o repositório e o token.
3. Edite o que precisar. Cada alteração fica salva como **rascunho** automaticamente: no navegador e, com o GitHub configurado, também na branch `rascunho` deste repositório (criptografado com a senha do gestor).
4. O rascunho se acumula até a próxima publicação: pode fechar a página, trocar de computador ou atualizar o `index.html`, que nada se perde e nada é perguntado. Se duas edições mexerem no mesmo campo, vale a mais recente.
5. Clique em **Exportar → Publicar agora**. O `index.html` deste repositório é atualizado, e em cerca de 1 minuto todos veem a nova versão pelo link.

## Token do GitHub (fine-grained)

Em *Settings → Developer settings → Personal access tokens → Fine-grained tokens*:

- **Repository access:** somente este repositório.
- **Permissions:** Contents: *Read and write* · Pages: *Read and write*.

O token fica salvo apenas no navegador do gestor e nunca é publicado. A branch `rascunho` é criada automaticamente na primeira edição; não mude o GitHub Pages para ela.

## Ativar o GitHub Pages (uma vez)

Em *Settings → Pages*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
