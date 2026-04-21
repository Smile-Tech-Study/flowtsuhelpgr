---
order: 1
title: Где будет проходить обучение?
---

[html]

<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; background: #fff; }

.odin-wrap {
  background: #EEF1F5;
  border-radius: 16px;
  overflow: hidden;
  padding: 28px 28px 24px;
}

.odin-header {
  display: flex;
  align-items: center;
  gap: 14px;
  margin-bottom: 24px;
  opacity: 0;
  animation: fadeUp 0.5s ease 0.2s forwards;
}

.odin-logo-circle {
  width: 48px; height: 48px;
  border-radius: 12px;
  background: #1A6FDB;
  display: flex; align-items: center; justify-content: center;
  flex-shrink: 0;
}

.odin-logo-circle svg { width: 26px; height: 26px; }

.odin-name { font-size: 22px; font-weight: 600; color: #1A1D23; }
.odin-tagline { font-size: 13px; color: #7A8494; margin-top: 2px; }

.cards-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 12px;
  margin-bottom: 16px;
}

.card {
  background: #fff;
  border-radius: 12px;
  padding: 18px 16px;
  border: 1px solid #E4E8EF;
  opacity: 0;
  transform: translateY(12px);
}

.card:nth-child(1) { animation: fadeUp 0.5s ease 0.4s forwards; }
.card:nth-child(2) { animation: fadeUp 0.5s ease 0.6s forwards; }
.card:nth-child(3) { animation: fadeUp 0.5s ease 0.8s forwards; }

@keyframes fadeUp { to { opacity: 1; transform: translateY(0); } }

.card-icon {
  width: 38px; height: 38px;
  border-radius: 10px;
  background: #EEF3FD;
  display: flex; align-items: center; justify-content: center;
  font-size: 18px;
  margin-bottom: 12px;
}

.card-title { font-size: 13px; font-weight: 600; color: #1A1D23; margin-bottom: 5px; }
.card-desc { font-size: 12px; color: #7A8494; line-height: 1.5; }

.odin-footer {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 16px;
  border-top: 1px solid #DDE1E9;
  opacity: 0;
  animation: fadeUp 0.5s ease 1.0s forwards;
}

.odin-hint { font-size: 12px; color: #7A8494; display: flex; align-items: center; gap: 6px; }
.dot-live { width: 7px; height: 7px; border-radius: 50%; background: #2ECC71; animation: pulse 2s ease infinite; flex-shrink: 0; }
@keyframes pulse { 0%,100%{opacity:1} 50%{opacity:0.3} }

.odin-btn {
  background: #1A6FDB;
  color: #fff;
  border: none;
  border-radius: 8px;
  padding: 8px 18px;
  font-size: 13px;
  font-weight: 500;
  cursor: pointer;
  text-decoration: none;
  display: inline-block;
}
.odin-btn:hover { background: #155BB5; }
</style>
</head>
<body>

<div class="odin-wrap">
  <div class="odin-header">
    <div class="odin-logo-circle">
      <svg viewBox="0 0 26 26" fill="none">
        <circle cx="13" cy="13" r="9" stroke="#fff" stroke-width="1.8"/>
        <circle cx="13" cy="13" r="3.5" fill="#fff"/>
        <line x1="13" y1="4" x2="13" y2="7" stroke="#fff" stroke-width="1.8" stroke-linecap="round"/>
        <line x1="13" y1="19" x2="13" y2="22" stroke="#fff" stroke-width="1.8" stroke-linecap="round"/>
        <line x1="4" y1="13" x2="7" y2="13" stroke="#fff" stroke-width="1.8" stroke-linecap="round"/>
        <line x1="19" y1="13" x2="22" y2="13" stroke="#fff" stroke-width="1.8" stroke-linecap="round"/>
      </svg>
    </div>
    <div>
      <div class="odin-name">Odin</div>
      <div class="odin-tagline">Онлайн-платформа для обучения в рамках проекта «Активные меры содействия занятости» ФО ТГУ. Доступ открывается за сутки до старта — вы получите письмо-приглашение на почту.</div>
    </div>
  </div>

  <div class="cards-grid">
    <div class="card">
      <div class="card-icon">📹</div>
      <div class="card-title">Видеолекции и материалы</div>
    </div>
    <div class="card">
      <div class="card-icon">📝</div>
      <div class="card-title">Задания и тесты</div>
    </div>
    <div class="card">
      <div class="card-icon">📊</div>
      <div class="card-title">Прогресс и расписание</div>
    </div>
  </div>

  <div class="odin-footer">
    <div class="odin-hint">
      <div class="dot-live"></div>
      Логин — ваша почта из заявки · в письме придёт ссылка на установку пароля, или войдите через раздел «Обучение» в ЛК Flow
    </div>
    <a href="https://www.odin.study/studentshelp" class="odin-btn" target="_blank">Справка по Odin →</a>
  </div>
</div>

</body>
</html>

[/html]