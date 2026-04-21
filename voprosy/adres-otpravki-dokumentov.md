---
order: 1
title: 📨 Адрес отправки документов
---



[html]

<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; background: #fff; }

.cards { display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; margin-bottom: 12px; }

.card {
  background: #F7F9FC;
  border-radius: 12px;
  border: 1px solid #E4E8EF;
  padding: 14px 16px;
  display: flex;
  gap: 12px;
  align-items: flex-start;
  opacity: 0;
  transform: translateY(10px);
}
.card:nth-child(1) { animation: up 0.4s ease 0.1s forwards; }
.card:nth-child(2) { animation: up 0.4s ease 0.3s forwards; }
@keyframes up { to { opacity: 1; transform: translateY(0); } }

.card-icon { font-size: 22px; flex-shrink: 0; margin-top: 2px; }
.card-title { font-size: 13px; font-weight: 600; color: #1A1D23; margin-bottom: 4px; }
.card-desc { font-size: 12px; color: #5A6478; line-height: 1.5; }

.info {
  background: #FCEBEB;
  border-left: 3px solid #E24B4A;
  border-radius: 0 8px 8px 0;
  padding: 10px 14px;
  font-size: 12px;
  color: #501313;
  line-height: 1.5;
  opacity: 0;
  animation: up 0.4s ease 0.5s forwards;
}
.info a { color: #A32D2D; }
</style>
</head>
<body>

<div class="cards">
  <div class="card">
    <div class="card-icon">📬</div>
    <div>
      <div class="card-title">Адрес — в вашем договоре</div>
      <div class="card-desc">У каждой образовательной организации свой почтовый адрес. Найдите его в договоре, сгенерированном во Flow. На конверте укажите название вашей программы.</div>
    </div>
  </div>
  <div class="card">
    <div class="card-icon">📦</div>
    <div>
      <div class="card-title">Отправляйте заказным письмом</div>
      <div class="card-desc">После отправки внесите трек-номер и дату отправки в ЛК Flow. Один экземпляр договора вернётся вам вместе с документом о квалификации после завершения обучения.</div>
    </div>
  </div>
</div>

<div class="info">
  Отправлять оригиналы можно только после <strong>одобрения документов в ЛК</strong> и <strong>подписания договора о намерениях</strong> на портале Работа России всеми сторонами.
</div>

</body>
</html>

[/html]