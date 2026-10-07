# GosExam AI — APK Ready

Это Android WebView-проект, в который встроена версия `GosExam_AI_v11_apk_ready.html`.

## Что уже сделано
- Supabase Auth + Google OAuth подготовлены.
- Supabase PostgreSQL/Storage.
- Edge Functions `generate-questions` и `ai-tutor`.
- Реальные тесты, экзамен, история, ошибки и прогресс.
- PDF/DOCX/TXT extraction.
- OCR для JPG/PNG через Tesseract.js.
- Личная база знаний пользователя.
- Android WebView shell и file picker.
- GitHub Actions автоматически собирает debug APK.

## Один обязательный шаг перед Google-входом
В Supabase Dashboard добавь redirect URL:
`gosexam://auth-callback`

Для веб-версии оставь обычный URL приложения.

## Сборка
После загрузки проекта в GitHub открой Actions → Build GosExam AI APK → Run workflow.
Готовый файл появится в Artifacts как `GosExam-AI-debug-apk`.
