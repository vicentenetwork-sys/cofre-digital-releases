# Cofre Digital — Downloads

Controle financeiro pessoal **offline e portátil** para Windows, com dados criptografados no seu computador.

Este repositório contém **apenas os pacotes de instalação e atualização**. O código-fonte não é público.

## Como instalar
1. Abra a [última versão](../../releases/latest) e baixe `CofreDigital-<versão>-portable.zip`.
2. Extraia em uma pasta sua (Documentos, outra unidade ou pendrive). Evite pastas sincronizadas (OneDrive, Google Drive, Dropbox).
3. Execute `CofreDigital.exe`.

Requisitos: Windows 10 ou 11 (64 bits) com Microsoft Edge WebView2 Runtime (já incluso no Windows 11).

## Atualizações
O app verifica novas versões aqui automaticamente quando há internet e só aplica pacotes com assinatura digital válida. Sem internet, ele continua funcionando normalmente.

## Verificação manual
Cada release traz `SHA256SUMS.txt` e `latest.json.minisig` (assinatura minisign/Ed25519).
