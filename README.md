# NOCTIS Android

Projeto Android nativo que carrega a interface HTML local dentro de um WebView. Mantém a tela ligada com `FLAG_KEEP_SCREEN_ON` e permite escolher imagens/GIFs pelo seletor de arquivos do Android.

## Gerar o APK pelo GitHub
1. Crie um repositório público chamado `noctis-clock`.
2. Envie **o conteúdo desta pasta** para a raiz do repositório.
3. Abra **Actions** e aguarde o workflow **Build NOCTIS APK** terminar.
4. Abra a execução concluída, vá em **Artifacts** e baixe `noctis-debug-apk`.
5. Extraia o ZIP do artifact para obter `app-debug.apk` e instale no Android.

O APK de debug é adequado para teste pessoal. Para distribuição pública, gere uma versão release assinada.
