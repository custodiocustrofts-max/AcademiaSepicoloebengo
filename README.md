# Academia SEP — APK via GitHub Actions

Projeto preparado para gerar o APK Android na nuvem, sem Android Studio e sem PC local.

1. Crie um repositório no GitHub.
2. Envie todos os ficheiros desta pasta para a branch `main`.
3. Abra **Actions** → **Construir APK Academia SEP**.
4. Toque em **Run workflow**.
5. Aguarde terminar.
6. Abra a execução concluída e descarregue o artifact `Academia-SEP-APK`.
7. Extraia o ZIP e instale `app-debug.apk`.

O APK é gerado pelo Capacitor e Gradle na infraestrutura do GitHub Actions.
