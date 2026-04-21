---
description: >-
  Все документы необходимо оперативно загружать через личный кабинет Flow.
  Загрузка документов через личный кабинет - безопасный способ передачи
  документов в образовательную организацию.
order: 0.9
title: ❌ Отклонены документы?
---

Все документы необходимо оперативно загружать через личный кабинет Flow. Загрузка документов через личный кабинет - безопасный способ передачи документов в образовательную организацию.

[html]

<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; background: #fff; }
.section-title { font-size: 12px; font-weight: 600; color: #7A8494; text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 10px; opacity: 0; animation: up 0.4s ease 0.1s forwards; }
.types { display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; margin-bottom: 20px; }
.type-card { background: #F7F9FC; border-radius: 12px; border: 1px solid #E4E8EF; padding: 14px 16px; display: flex; gap: 12px; align-items: flex-start; opacity: 0; transform: translateY(10px); }
.type-card:nth-child(1) { animation: up 0.4s ease 0.2s forwards; }
.type-card:nth-child(2) { animation: up 0.4s ease 0.35s forwards; }
.type-card:nth-child(3) { animation: up 0.4s ease 0.5s forwards; }
.type-card:nth-child(4) { animation: up 0.4s ease 0.65s forwards; }
.type-num { width: 24px; height: 24px; border-radius: 50%; font-size: 11px; font-weight: 600; display: flex; align-items: center; justify-content: center; flex-shrink: 0; margin-top: 1px; }
.type-card:nth-child(1) .type-num { background: #E6F1FB; color: #185FA5; }
.type-card:nth-child(2) .type-num { background: #E1F5EE; color: #0F6E56; }
.type-card:nth-child(3) .type-num { background: #EEEDFE; color: #3C3489; }
.type-card:nth-child(4) .type-num { background: #FAEEDA; color: #633806; }
.type-title { font-size: 13px; font-weight: 600; color: #1A1D23; margin-bottom: 4px; line-height: 1.3; }
.type-desc { font-size: 12px; color: #5A6478; line-height: 1.5; }
.divider { border: none; border-top: 1px solid #EEF1F5; margin: 4px 0 16px; }
.actions { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; margin-bottom: 16px; }
.action-card { background: #F7F9FC; border-radius: 12px; border: 1px solid #E4E8EF; padding: 14px 16px; display: flex; flex-direction: column; gap: 6px; opacity: 0; transform: translateY(10px); }
.action-card:nth-child(1) { animation: up 0.4s ease 0.8s forwards; }
.action-card:nth-child(2) { animation: up 0.4s ease 0.95s forwards; }
.action-card:nth-child(3) { animation: up 0.4s ease 1.1s forwards; }
.action-icon { font-size: 20px; }
.action-title { font-size: 13px; font-weight: 600; color: #1A1D23; line-height: 1.3; }
.action-desc { font-size: 12px; color: #5A6478; line-height: 1.5; }
.alert { background: #FCEBEB; border-left: 3px solid #E24B4A; border-radius: 0 8px 8px 0; padding: 10px 14px; font-size: 12px; color: #501313; line-height: 1.5; margin-bottom: 10px; opacity: 0; animation: up 0.4s ease 1.2s forwards; }
.info { background: #EEF4FB; border-left: 3px solid #378ADD; border-radius: 0 8px 8px 0; padding: 10px 14px; font-size: 12px; color: #0C447C; line-height: 1.5; opacity: 0; animation: up 0.4s ease 1.3s forwards; }
.info a { color: #185FA5; }
@keyframes up { to { opacity: 1; transform: translateY(0); } }
</style>
</head>
<body>

<div class="section-title">Документы во Flow условно можно разделить на 4 категории:</div>
<div class="types">
  <div class="type-card">
    <div class="type-num">1</div>
    <div>
      <div class="type-title">Первичные документы</div>
      <div class="type-desc">Сканы паспорта (главная страница + прописка), документ об образовании. При смене фамилии — приложите все подтверждающие документы.</div>
    </div>
  </div>
  <div class="type-card">
    <div class="type-num">2</div>
    <div>
      <div class="type-title">Документы ДЗС</div>
      <div class="type-desc">Договор на обучение, заявление на зачисление, согласие на обработку персональных данных.</div>
    </div>
  </div>
  <div class="type-card">
    <div class="type-num">3</div>
    <div>
      <div class="type-title">Документы от организации</div>
      <div class="type-desc">Добавляет образовательная организация: приказ на зачисление, приказ об отчислении, подписанный договор, документ о квалификации. Доступны в разделе <strong>«Мои документы»</strong>.</div>
    </div>
  </div>
  <div class="type-card">
    <div class="type-num">4</div>
    <div>
      <div class="type-title">Дополнительные документы</div>
      <div style="display:inline-block;background:#FAEEDA;color:#633806;font-size:11px;font-weight:600;padding:2px 8px;border-radius:20px;margin-bottom:6px;">Только по запросу организации</div>
      <div class="type-desc">Например, документ о смене ФИО после начала обучения. Доступно в <strong>«Мои документы» → «Дополнительные документы»</strong> после одобрения ДЗС.</div>
    </div>
  </div>
</div>

<hr class="divider">

<div class="section-title">Что делать если документ отклонили</div>
<div class="actions">
  <div class="action-card">
    <div class="action-icon">🔔</div>
    <div class="action-title">Придёт уведомление</div>
    <div class="action-desc">В ЛК появится комментарий — что именно нужно исправить.</div>
  </div>
  <div class="action-card">
    <div class="action-icon">✏️</div>
    <div class="action-title">Исправьте и загрузите снова</div>
    <div class="action-desc">Внесите правки и повторно загрузите документ во Flow на проверку.</div>
  </div>
  <div class="action-card">
    <div class="action-icon">⏳</div>
    <div class="action-title">Дождитесь одобрения</div>
    <div class="action-desc">Документы из категорий 1 и 2 проходят ручную проверку — после одобрения откроется следующий шаг.<br><br>Дополнительные документы (категория 4) тоже проверяются, но их статус <strong>не влияет на шаги</strong> в личном кабинете.</div>
  </div>
</div>

<div class="alert">
  Если вы подали <strong>повторную заявку</strong> — первичные документы будут отклонены автоматически. Проверьте актуальность данных и загрузите их заново.
</div>

<div class="info">
  Сканы должны быть <strong>чёткими и читаемыми</strong> — это главная причина отклонения. Нужна помощь? См. <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/kak-skanirovat-s-telefona">«Как сканировать с телефона?»</a>
</div>

</body>
</html>

[/html]