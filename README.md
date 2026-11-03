# Versões da tela inicial para Fire TV

Uso pessoal, sem afiliação com a Amazon, a Apple ou os donos dos apps cujos logotipos aparecem na tela.

Este repositório é gerado automaticamente pelo GitHub Actions do projeto. **Não edite à mão:** cada publicação apaga o conteúdo anterior.

- `versao.json`: a versão atual de cada app, com o SHA-256, o tamanho e o histórico de novidades.
- `tela-inicial-<versão>.apk`: a tela inicial.
- `atualizador-<versão>.apk`: o Atualizador, que confere este repositório duas vezes por dia.

Os APKs são assinados. O Atualizador só instala arquivos com a assinatura esperada e com o SHA-256 que está no `versao.json`.

## Licenças do que vai nos APKs

- **Fonte Inter**: SIL Open Font License 1.1. O texto da licença vai no próprio APK (`assets/fonts/OFL.txt`).
- **Papéis de parede**:
  - quatro fotos do Unsplash, sob a Licença Unsplash;
  - a foto "Himalaia" (Machapuchare, de Bijay Chaurasia Photography, Wikimedia Commons), sob a CC BY-SA 4.0. A versão do app é modificada (recorte, desfoque e sombras) e segue a mesma licença.
- **Ícone de engrenagem**: baseado no ícone "settings" do Feather Icons, Copyright (c) 2013-2023 Cole Bemis, licença MIT: <https://github.com/feathericons/feather/blob/main/LICENSE>.
- **Logotipos de apps**: marcas registradas dos seus donos, usadas só para identificar cada app na tela inicial.
