# Portfólio — Maria Eduarda Guerra

## Como abrir no VS Code

1. Extraia o arquivo ZIP em `Documentos\\Projetos`.
2. No VS Code, clique em **File > Open Folder** e abra a pasta extraída.
3. Instale a extensão **Live Server**, caso ainda não tenha.
4. Abra `dist/index.html`, clique com o botão direito e escolha **Open with Live Server**.

Não é necessário executar `npm install`: este projeto usa apenas HTML, CSS e JavaScript.

## Onde alterar cada parte

- Textos, contatos, competências e projetos: `dist/index.html`
- Cores, tamanhos, espaçamentos e versão para celular: `dist/styles.css`
- Menu e animações: `dist/script.js`
- Foto do perfil: `dist/assets/maria-eduarda.png`

Para trocar a foto sem alterar o código, coloque a nova imagem na pasta `dist/assets` e dê a ela o nome `maria-eduarda.png`, substituindo a anterior.

## Como conferir alterações

Salve o arquivo com `Ctrl + S`. A página aberta pelo Live Server deve atualizar automaticamente. Se não atualizar, pressione `Ctrl + F5` no navegador.

## Como enviar as mudanças ao GitHub depois

Quando o repositório estiver configurado:

```powershell
git add .
git commit -m "Atualiza portfolio"
git push
```

Para republicar a versão do site criada no ChatGPT, envie o ZIP alterado novamente nesta conversa.
