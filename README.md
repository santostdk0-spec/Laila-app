# Laila — versão inicial para Android

Protótipo web instalável (PWA), feito para ser editado e testado pelo celular.

## Arquivos
- `index.html`: interface, chat, memória e configurações.
- `manifest.webmanifest`: metadados de instalação.

## Publicar pelo celular
1. Abra este repositório no GitHub.
2. Vá em **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Escolha a branch `main` e a pasta `/(root)`, depois **Save**.
5. Aguarde o endereço do GitHub Pages aparecer na mesma página.
6. Abra o endereço no Chrome Android; no menu, escolha **Adicionar à tela inicial** ou **Instalar app**.

## Limitações atuais
- Esta é uma primeira versão; a memória é manual, não extraída automaticamente.
- A interface salva dados no armazenamento local do navegador.
- Para respostas reais, configure em Configurações uma API compatível com `/chat/completions`.
- APIs gratuitas podem impor cotas. Chamadas diretas podem falhar por CORS e não são adequadas para proteger uma chave em um site público. Antes de publicar para uso amplo, vamos implementar um backend seguro.
- Não é um APK nativo e ainda não é uma IA independente/ilimitada.
