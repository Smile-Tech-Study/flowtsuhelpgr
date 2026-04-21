---
order: 0.3
title: Содержание
---

:::info 

Здесь собраны инструкции и ответы на частые вопросы для участников проекта «Активные меры содействия занятости» ФО ТГУ.

:::

[html]

<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; background: #fff; }

.intro {
  background: #EEF4FB;
  border-radius: 12px;
  padding: 16px 20px;
  margin-bottom: 24px;
  font-size: 13px;
  color: #185FA5;
  line-height: 1.6;
  opacity: 0;
  animation: up 0.4s ease 0.1s forwards;
}
.intro strong { color: #0C447C; }

.section { margin-bottom: 24px; opacity: 0; transform: translateY(10px); }
.section:nth-child(2) { animation: up 0.4s ease 0.2s forwards; }
.section:nth-child(3) { animation: up 0.4s ease 0.35s forwards; }
.section:nth-child(4) { animation: up 0.4s ease 0.5s forwards; }
.section:nth-child(5) { animation: up 0.4s ease 0.65s forwards; }

.section-header {
  display: flex;
  align-items: center;
  gap: 8px;
  margin-bottom: 10px;
  padding-bottom: 8px;
  border-bottom: 2px solid #EEF1F5;
}
.section-icon { font-size: 18px; }
.section-title { font-size: 14px; font-weight: 600; color: #1A1D23; }

.links { display: grid; grid-template-columns: repeat(2, 1fr); gap: 6px; }
.links.single { grid-template-columns: 1fr; }

.link-card {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 10px 14px;
  background: #F7F9FC;
  border-radius: 10px;
  border: 1px solid #E4E8EF;
  text-decoration: none;
  color: #1A1D23;
  font-size: 13px;
  transition: background 0.15s, border-color 0.15s;
}
.link-card:hover { background: #E6F1FB; border-color: #B5D4F4; color: #0C447C; }
.link-card .arrow { margin-left: auto; color: #B5D4F4; font-size: 14px; flex-shrink: 0; }

.badge {
  font-size: 10px;
  font-weight: 600;
  padding: 2px 7px;
  border-radius: 20px;
  background: #E1F5EE;
  color: #0F6E56;
  flex-shrink: 0;
}
.badge.new { background: #FAEEDA; color: #633806; }

@keyframes up { to { opacity: 1; transform: translateY(0); } }
</style>
</head>
<body>

<div class="intro">
  Добро пожаловать в справку Flow! Здесь вы найдёте всё необходимое для работы в личном кабинете. Если вы только начинаете — <strong>начните с инструкции по работе в ЛК</strong>.
</div>

<div class="section">
  <div class="section-header">
    <div class="section-icon">🚀</div>
    <div class="section-title">Начало работы</div>
  </div>
  <div class="links single">
    <a href="https://www.flow-crm.study/flowtsuhelpgr/LK" class="link-card" target="_blank">
      📋 Инструкция по работе в личном кабинете
      <span class="badge">Начните здесь</span>
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/flow-chto-eto" class="link-card" target="_blank">
      💡 Flow — что это?
      <span class="arrow">→</span>
    </a>
  </div>
</div>

<div class="section">
  <div class="section-header">
    <div class="section-icon">🎓</div>
    <div class="section-title">Обучение</div>
  </div>
  <div class="links">
    <a href="https://www.flow-crm.study/flowtsuhelpgr/obuchenie/gde-budet-prokhodit-obuchenie" class="link-card" target="_blank">
      🖥️ Где будет проходить обучение?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.odin.study/studentshelp/profil/uspevaemost-poseshaemost" class="link-card" target="_blank">
      📊 Успеваемость и посещаемость
      <span class="arrow">→</span>
    </a>
  </div>
</div>

<div class="section">
  <div class="section-header">
    <div class="section-icon">⁉️</div>
    <div class="section-title">Частые вопросы</div>
  </div>
  <div class="links">
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/ssylka-nedeistvitelna.-chto-delat" class="link-card" target="_blank">
      🔗 Ссылка недействительна. Что делать?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/kak-skanirovat-s-telefona" class="link-card" target="_blank">
      📱 Как сканировать с телефона?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/otkloneny-dokumenty" class="link-card" target="_blank">
      ❌ Отклонены документы?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/adres-otpravki-dokumentov" class="link-card" target="_blank">
      📨 Адрес отправки документов
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/kak-otmenit-zayavku-otchislitsya" class="link-card" target="_blank">
      🚫 Как отменить заявку / отчислиться?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/pochemu-ya-vkhozhu-po-ssylke-bezopasno-li-eto" class="link-card" target="_blank">
      🔐 Почему вхожу по ссылке? Безопасно ли?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/shag-7.-gde-moi-dogovor-o-namereniyakh" class="link-card" target="_blank">
      📄 Где мой договор о намерениях?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/kakoi-dogovor-ya-budu-podpisyvat-s-obrazovatelnoi-organizaciei" class="link-card" target="_blank">
      📝 Какой договор подписываю с организацией?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/kakoi-podpisyu-ya-budu-podpisyvat-dogovor-o-namereniyakh-na-portale-rabota-rossii" class="link-card" target="_blank">
      ✍️ Какой подписью подписывать договор о намерениях?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/kak-smenit-pochtu-vo-flow-v-blankakh-dokumentov" class="link-card" target="_blank">
      📧 Как сменить почту во Flow?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/kak-vklyuchit-uvedomleniya-v-brauzere" class="link-card" target="_blank">
      🔔 Как включить уведомления в браузере?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/gde-naiti-ssylku-na-moyu-stranicu-vkontakte" class="link-card" target="_blank">
      💬 Где найти ссылку на страницу ВКонтакте?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/instrukcii-rabota-rossii" class="link-card" target="_blank">
      🇷🇺 Инструкции портала Работа России
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/postanovlenie-ot-7-marta-2025-goda-291" class="link-card" target="_blank">
      📜 Постановление № 291 от 7 марта 2025
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/gde-moi-dokument-o-zavershenii-obucheniya" class="link-card" target="_blank">
      🏆 Где мой документ о завершении обучения?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/kakie-dokumenty-podtverdyat-trudoustroistvo" class="link-card" target="_blank">
      💼 Какие документы подтвердят трудоустройство?
      <span class="arrow">→</span>
    </a>
    <a href="https://www.flow-crm.study/flowtsuhelpgr/voprosy/kak-zagruzit-dopolnitelnyy-dokument" class="link-card" target="_blank">
      📎 Как загрузить дополнительный документ?
      <span class="arrow">→</span>
    </a>
    <a href="#" class="link-card" target="_blank">
      🔄 Договор о намерениях есть, обучение не началось
      <span class="arrow">→</span>
    </a>
    <a href="#" class="link-card" target="_blank">
      👤 Смена фамилии или новый паспорт во время обучения
      <span class="arrow">→</span>
    </a>
    <a href="#" class="link-card" target="_blank">
      ✏️ Ошибка или опечатка в заявлении на зачисление
      <span class="arrow">→</span>
    </a>
    <a href="#" class="link-card" target="_blank">
      🎟️ Квота закончилась — что делать?
      <span class="arrow">→</span>
    </a>
  </div>
</div>


  <div class="links">
    <a href="#" class="link-card" target="_blank">
      🔄 Договор о намерениях есть, обучение не началось
      <span class="arrow">→</span>
    </a>
    <a href="#" class="link-card" target="_blank">
      👤 Смена фамилии или новый паспорт во время обучения
    
      <span class="arrow">→</span>
    </a>
    <a href="#" class="link-card" target="_blank">
      ✏️ Ошибка или опечатка в заявлении на зачисление
      <span class="arrow">→</span>
    </a>
   
  </div>
</div>

<div class="section" style="opacity:0;animation:up 0.4s ease 0.8s forwards;">
  <div class="section-header">
    <div class="section-icon">🆘</div>
    <div class="section-title">Нужна помощь?</div>
  </div>
  <div class="links">
    <a href="https://www.tgu-dpo.ru/Form" class="link-card" target="_blank" style="background:#F0FBF6;border-color:#9FE1CB;" target="_blank">
      🖥️ Проблема в личном кабинете Flow — написать в поддержку ТГУ
      <span class="arrow">→</span>
    </a>
    <a href="https://lk.tgu-dpo.ru" class="link-card" target="_blank" style="background:#EEF4FB;border-color:#B5D4F4;" target="_blank">
      ❓ Вопрос по программе — контакты организации в разделе «Моя программа»
      <span class="arrow">→</span>
    </a>
  </div>
</div>

</body>
</html>

</body>
</html>

[/html]