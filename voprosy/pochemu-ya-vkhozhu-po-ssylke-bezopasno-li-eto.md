---
order: 1.8
title: 🔗 Почему я вхожу по ссылке? Безопасно ли это?
---

[html]

<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<style>
* { box-sizing: border-box; margin: 0; padding: 0; }
body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; background: #fff; }

.hero {
  background: #EEF4FB;
  border-radius: 12px;
  padding: 20px 24px;
  margin-bottom: 16px;
  display: flex;
  gap: 16px;
  align-items: flex-start;
  opacity: 0;
  animation: up 0.4s ease 0.1s forwards;
}
.hero-icon { font-size: 32px; flex-shrink: 0; }
.hero-title { font-size: 15px; font-weight: 600; color: #0C447C; margin-bottom: 6px; }
.hero-desc { font-size: 13px; color: #185FA5; line-height: 1.6; }

.cards { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; margin-bottom: 16px; }
.card {
  background: #F7F9FC;
  border-radius: 12px;
  border: 1px solid #E4E8EF;
  padding: 14px 16px;
  opacity: 0;
  transform: translateY(10px);
}
.card:nth-child(1) { animation: up 0.4s ease 0.3s forwards; }
.card:nth-child(2) { animation: up 0.4s ease 0.45s forwards; }
.card:nth-child(3) { animation: up 0.4s ease 0.6s forwards; }

.card-badge {
  display: inline-block;
  background: #E6F1FB;
  color: #0C447C;
  font-size: 10px;
  font-weight: 600;
  padding: 2px 8px;
  border-radius: 20px;
  margin-bottom: 8px;
  letter-spacing: 0.04em;
}
.card-title { font-size: 13px; font-weight: 600; color: #1A1D23; margin-bottom: 4px; }
.card-desc { font-size: 12px; color: #5A6478; line-height: 1.5; }

.info {
  background: #E1F5EE;
  border-left: 3px solid #1D9E75;
  border-radius: 0 8px 8px 0;
  padding: 10px 14px;
  font-size: 12px;
  color: #085041;
  line-height: 1.5;
  opacity: 0;
  animation: up 0.4s ease 0.75s forwards;
}

@keyframes up { to { opacity: 1; transform: translateY(0); } }
</style>
</head>
<body>

<div class="hero">
  <div class="hero-icon">🔐</div>
  <div>
    <div class="hero-title">Да, это безопасно. Ссылка — это и есть ваш ключ для входа.</div>
    <div class="hero-desc">Мы не используем логин и пароль, чтобы вы не могли их забыть или потерять. Вместо этого система генерирует персональную ссылку — она работает только для вас.</div>
  </div>
</div>

<div class="cards">
  <div class="card">
    <div class="card-badge">SAML 2.0</div>
    <div class="card-title">Промышленный стандарт</div>
    <div class="card-desc">Протокол SAML используют банки, госсервисы и корпорации по всему миру для безопасной аутентификации.</div>
  </div>
  <div class="card">
    <div class="card-badge">ПЕРСОНАЛЬНАЯ ССЫЛКА</div>
    <div class="card-title">Только для вас</div>
    <div class="card-desc">Перед отправкой система верифицирует ваши данные. Ссылка привязана к вашему email и действует ограниченное время.</div>
  </div>
  <div class="card">
    <div class="card-badge">ШИФРОВАНИЕ</div>
    <div class="card-title">Данные защищены</div>
    <div class="card-desc">Обмен данными происходит по зашифрованному протоколу — никто посторонний не может перехватить вашу ссылку или войти вместо вас.</div>
  </div>
</div>

<div class="info">
  Письмо приходит только с адреса <strong>info@tgu-dpo.ru</strong>. Если вам пишут с другого адреса и просят перейти по ссылке — это мошенники.
</div>

</body>
</html>

[/html]



Нашей системой безопасности используется протокол аутентификация SAML.

:::info 

Аутентификация - это проверка подлинности пользователя.

:::

**Для чего используют именно данный метод аутентификации?**

Вам не придется запоминать/держать в памяти многочисленные логины и пароли, чтобы избежать утери паролей и потери доступа к Вашим данным.

Мы используем язык разметки SAML (Security Assertion Markup Language), который представляет собой стандарт на основе XML, который предназначен для обмена данными аутентификации и авторизации между сторонами процесса.

SAML работает путем обмена пользовательской информацией между системой управления доступами и поставщиком услуг. В результате это упрощает и обеспечивает безопасность процесса аутентификации. Таким образом, когда пользователь запрашивает доступ к сайту, SAML передает аутентификационные данные поставщику услуг, который впоследствии предоставляет доступ пользователю.

**Перед предоставлением доступа к информации обязательно проверяются ваши личные данные, чтобы индивидуальная ссылка для входа была сгенерирована и предоставлена только вам.**