---
order: 1.9
title: Шаг 7. Где мой договор о намерениях?
---

[html]

<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; background: #fff; }

.info-box {
  background: #EEF4FB;
  border-left: 3px solid #378ADD;
  border-radius: 0 8px 8px 0;
  padding: 10px 14px;
  font-size: 12px;
  color: #0C447C;
  line-height: 1.5;
  margin-bottom: 20px;
  opacity: 0;
  animation: up 0.4s ease 0.1s forwards;
}

.section-title {
  font-size: 12px;
  font-weight: 600;
  color: #7A8494;
  text-transform: uppercase;
  letter-spacing: 0.06em;
  margin-bottom: 12px;
  opacity: 0;
  animation: up 0.4s ease 0.2s forwards;
}

.timeline {
  display: flex;
  flex-direction: column;
  gap: 0;
  margin-bottom: 20px;
  position: relative;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 19px;
  top: 20px;
  bottom: 20px;
  width: 2px;
  background: #E4E8EF;
}

.tl-item {
  display: flex;
  gap: 16px;
  align-items: flex-start;
  padding: 12px 0;
  opacity: 0;
  transform: translateX(-10px);
}
.tl-item:nth-child(1) { animation: slide 0.4s ease 0.3s forwards; }
.tl-item:nth-child(2) { animation: slide 0.4s ease 0.5s forwards; }
.tl-item:nth-child(3) { animation: slide 0.4s ease 0.7s forwards; }
.tl-item:nth-child(4) { animation: slide 0.4s ease 0.9s forwards; }

.tl-dot {
  width: 40px; height: 40px;
  border-radius: 50%;
  display: flex; align-items: center; justify-content: center;
  font-size: 16px;
  flex-shrink: 0;
  position: relative;
  z-index: 1;
}
.tl-item:nth-child(1) .tl-dot { background: #E6F1FB; }
.tl-item:nth-child(2) .tl-dot { background: #E1F5EE; }
.tl-item:nth-child(3) .tl-dot { background: #EEEDFE; }
.tl-item:nth-child(4) .tl-dot { background: #FAEEDA; }

.tl-body { flex: 1; padding-top: 8px; }
.tl-title { font-size: 13px; font-weight: 600; color: #1A1D23; margin-bottom: 3px; }
.tl-desc { font-size: 12px; color: #5A6478; line-height: 1.5; }

.tl-badge {
  display: inline-block;
  background: #F7F9FC;
  border: 1px solid #E4E8EF;
  color: #5A6478;
  font-size: 11px;
  font-weight: 600;
  padding: 2px 8px;
  border-radius: 20px;
  margin-bottom: 4px;
}
.tl-item:nth-child(4) .tl-badge { background: #FAEEDA; border-color: #EF9F27; color: #633806; }

.alert {
  background: #FCEBEB;
  border-left: 3px solid #E24B4A;
  border-radius: 0 8px 8px 0;
  padding: 10px 14px;
  font-size: 12px;
  color: #501313;
  line-height: 1.5;
  opacity: 0;
  animation: up 0.4s ease 1.1s forwards;
}

@keyframes up { to { opacity: 1; transform: translateY(0); } }
@keyframes slide { to { opacity: 1; transform: translateX(0); } }
</style>
</head>
<body>

<div style="background:#F7F9FC;border:1px solid #E4E8EF;border-radius:8px;padding:10px 14px;font-size:12px;color:#5A6478;line-height:1.5;margin-bottom:12px;display:flex;gap:8px;align-items:flex-start;opacity:0;animation:up 0.4s ease 0.05s forwards;">
  <span style="font-size:16px;flex-shrink:0;">ℹ️</span>
  <span>Информация ниже носит <strong>ознакомительный характер</strong>. Договор о намерениях формируется и подписывается в <strong>личном кабинете портала Работа России</strong> — это отдельная система, не связанная с Flow. За актуальными статусами и сроками следите в личном кабинете портала Работа России.</span>
</div>
<div class="info-box">
  Договор о намерениях подписывается на портале <strong>Работа России</strong> — не во Flow. Генерация доступна ЦЗН не ранее чем за <strong>15</strong> и не позднее чем за <strong>10 рабочих дней</strong> до старта обучения. Если до старта ещё больше 15 рабочих дней — договор ещё не сгенерирован, это нормально.
</div>

<div class="section-title">Порядок подписания</div>

<div class="timeline">
  <div class="tl-item">
    <div class="tl-dot">📋</div>
    <div class="tl-body">
      <div class="tl-badge">За 15–10 рабочих дней до старта</div>
      <div class="tl-title">Генерация договора</div>
      <div class="tl-desc">ЦЗН формирует договор на портале Работа России. Работодатель должен быть зарегистрирован на портале и принимать заявления.</div>
    </div>
  </div>
  <div class="tl-item">
    <div class="tl-dot">🏫</div>
    <div class="tl-body">
      <div class="tl-badge">В течение 3 дней после генерации</div>
      <div class="tl-title">Подписывает первая сторона</div>
      <div class="tl-desc">Образовательная организация <em>(или ЦЗН — для безработных граждан, зарегистрированных в ЦЗН)</em>.</div>
    </div>
  </div>
  <div class="tl-item">
    <div class="tl-dot">💼</div>
    <div class="tl-body">
      <div class="tl-badge">Не позднее 4 р.д. до старта</div>
      <div class="tl-title">Подписывает вторая сторона</div>
      <div class="tl-desc">Работодатель <em>(или образовательная организация — для безработных граждан)</em>. Вторая сторона получает уведомление от портала РР.</div>
    </div>
  </div>
  <div class="tl-item">
    <div class="tl-dot">👤</div>
    <div class="tl-body">
      <div class="tl-badge">⚡ Не позднее 2 р.д. после второй стороны</div>
      <div class="tl-title">Подписываете вы — гражданин</div>
      <div class="tl-desc">Вы всегда подписываете последним. Как только пришло уведомление от РР — подписывайте сразу, не откладывайте.</div>
    </div>
  </div>
</div>

<div class="alert">
  Если любая из сторон не подпишет в срок — портал Работа России автоматически отклонит заявку. Следите за уведомлениями на почте и в ЛК РР.
</div>

</body>
</html>

[/html]