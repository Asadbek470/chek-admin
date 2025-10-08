# chek-admin
admin.com
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Тест для администраторов и модераторов</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #f7f9fc;
    color: #333;
    margin: 0;
    padding: 20px;
  }
  h1 {
    text-align: center;
    margin-bottom: 30px;
  }
  .question {
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    padding: 20px;
    margin-bottom: 20px;
  }
  .answers label {
    display: block;
    padding: 8px;
    border: 1px solid #ddd;
    border-radius: 8px;
    margin-top: 5px;
    cursor: pointer;
    transition: background 0.3s;
  }
  .answers label:hover {
    background: #f0f0f0;
  }
  button {
    display: block;
    margin: 30px auto;
    padding: 12px 30px;
    border: none;
    border-radius: 10px;
    background-color: #007bff;
    color: white;
    font-size: 16px;
    cursor: pointer;
  }
  button:hover {
    background-color: #0056b3;
  }
  #result {
    text-align: center;
    font-size: 20px;
    font-weight: bold;
    margin-top: 20px;
  }
</style>
</head>
<body>

<h1>Тест для администраторов, модераторов и владельцев</h1>

<form id="quizForm">

<div class="question">
  <p><strong>1. Пользователь и модератор поссорились в чате, начались взаимные оскорбления. Ваши действия?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q1" value="A"> A. Разделить конфликт: временно отстранить обоих, провести разбор отдельно.</label>
    <label><input type="radio" name="q1" value="B"> B. Встать на сторону модератора, ведь он из команды.</label>
    <label><input type="radio" name="q1" value="C"> C. Игнорировать, это их личное дело.</label>
    <label><input type="radio" name="q1" value="D"> D. Сразу забанить пользователя навсегда.</label>
  </div>
</div>

<div class="question">
  <p><strong>2. Модератор злоупотребляет правами, но это ваш друг. Что делать?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q2" value="A"> A. Объективно собрать факты и сообщить вышестоящему админу или владельцу.</label>
    <label><input type="radio" name="q2" value="B"> B. Замять ситуацию, чтобы не было скандала.</label>
    <label><input type="radio" name="q2" value="C"> C. Попросить его вести себя тише и забыть.</label>
    <label><input type="radio" name="q2" value="D"> D. Сразу выгнать его без объяснений.</label>
  </div>
</div>

<div class="question">
  <p><strong>3. Несколько пользователей жалуются на администратора. Что делает владелец?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q3" value="A"> A. Проверяет жалобы объективно, запрашивает доказательства, слушает обе стороны.</label>
    <label><input type="radio" name="q3" value="B"> B. Игнорирует, ведь админ — доверенное лицо.</label>
    <label><input type="radio" name="q3" value="C"> C. Сразу снимает администратора без разбора.</label>
    <label><input type="radio" name="q3" value="D"> D. Обвиняет пользователей во лжи.</label>
  </div>
</div>

<div class="question">
  <p><strong>4. Модератор неактивен уже месяц, но он давно в команде. Ваши действия?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q4" value="A"> A. Связаться с ним, уточнить причину и принять решение по ситуации.</label>
    <label><input type="radio" name="q4" value="B"> B. Уволить без предупреждения.</label>
    <label><input type="radio" name="q4" value="C"> C. Просто оставить, вдруг вернётся.</label>
    <label><input type="radio" name="q4" value="D"> D. Игнорировать, не его проблема.</label>
  </div>
</div>

<div class="question">
  <p><strong>5. Админ принял спорное решение, и часть команды недовольна. Что делает владелец?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q5" value="A"> A. Собирает внутреннее обсуждение, выслушивает всех и фиксирует решение в правилах.</label>
    <label><input type="radio" name="q5" value="B"> B. Отменяет решение без объяснений.</label>
    <label><input type="radio" name="q5" value="C"> C. Объявляет, что его слово закон, без обсуждений.</label>
    <label><input type="radio" name="q5" value="D"> D. Просит команду «не драматизировать».</label>
  </div>
</div>

<div class="question">
  <p><strong>6. Пользователь обвиняет администратора в хамстве, но при этом сам провоцировал. Ваш шаг?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q6" value="A"> A. Проверить обе стороны и рассмотреть поведение обоих по логам и контексту.</label>
    <label><input type="radio" name="q6" value="B"> B. Встать на сторону администратора.</label>
    <label><input type="radio" name="q6" value="C"> C. Сразу забанить пользователя.</label>
    <label><input type="radio" name="q6" value="D"> D. Извиниться перед пользователем без проверки.</label>
  </div>
</div>

<div class="question">
  <p><strong>7. Модератор публикует личную информацию пользователя. Что должен сделать админ?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q7" value="A"> A. Немедленно снять модератора с должности и зафиксировать нарушение конфиденциальности.</label>
    <label><input type="radio" name="q7" value="B"> B. Предупредить и закрыть глаза.</label>
    <label><input type="radio" name="q7" value="C"> C. Удалить пост, но оставить модератора.</label>
    <label><input type="radio" name="q7" value="D"> D. Посмеяться и ничего не делать.</label>
  </div>
</div>

<div class="question">
  <p><strong>8. Администратор уходит в отпуск и не предупредил. Что делает владелец?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q8" value="A"> A. Временно перераспределяет обязанности и проводит разговор после возвращения.</label>
    <label><input type="radio" name="q8" value="B"> B. Увольняет за самовольство.</label>
    <label><input type="radio" name="q8" value="C"> C. Игнорирует отсутствие.</label>
    <label><input type="radio" name="q8" value="D"> D. Делает публичное предупреждение.</label>
  </div>
</div>

<div class="question">
  <p><strong>9. Пользователь обвиняет всю команду администрации в предвзятости. Что делать?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q9" value="A"> A. Проверить ситуацию, объяснить политику сервера и пригласить на конструктивный диалог.</label>
    <label><input type="radio" name="q9" value="B"> B. Заблокировать за «наглость».</label>
    <label><input type="radio" name="q9" value="C"> C. Игнорировать, пусть кричит.</label>
    <label><input type="radio" name="q9" value="D"> D. Устроить голосование среди пользователей.</label>
  </div>
</div>

<div class="question">
  <p><strong>10. Модератор случайно выдал бан не тому пользователю. Ваши действия?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q10" value="A"> A. Снять бан, извиниться от лица команды и провести разбор с модератором.</label>
    <label><input type="radio" name="q10" value="B"> B. Снять бан и забыть.</label>
    <label><input type="radio" name="q10" value="C"> C. Ничего не делать — ошибка бывает у всех.</label>
    <label><input type="radio" name="q10" value="D"> D. Уволить модератора сразу.</label>
  </div>
</div>

<div class="question">
  <p><strong>11. Админ спорит с владельцем по решению. Как поступить владельцу?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q11" value="A"> A. Обсудить аргументы, дать возможность высказать позицию и вместе найти решение.</label>
    <label><input type="radio" name="q11" value="B"> B. Игнорировать и приказать «делать как сказано».</label>
    <label><input type="radio" name="q11" value="C"> C. Уволить за непослушание.</label>
    <label><input type="radio" name="q11" value="D"> D. Вынести спор на публику.</label>
  </div>
</div>

<div class="question">
  <p><strong>12. Модератор отказывается выполнять указания администратора. Что делать?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q12" value="A"> A. Провести разговор, выяснить причину отказа и при необходимости применить меры дисциплины.</label>
    <label><input type="radio" name="q12" value="B"> B. Сразу выдать предупреждение без диалога.</label>
    <label><input type="radio" name="q12" value="C"> C. Уволить немедленно.</label>
    <label><input type="radio" name="q12" value="D"> D. Игнорировать конфликт.</label>
  </div>
</div>

<div class="question">
  <p><strong>13. Пользователь публично оскорбил администратора, но затем извинился. Что делает модератор?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q13" value="A"> A. Принять извинения, но зафиксировать нарушение для повторных случаев.</label>
    <label><input type="radio" name="q13" value="B"> B. Забанить всё равно.</label>
    <label><input type="radio" name="q13" value="C"> C. Игнорировать.</label>
    <label><input type="radio" name="q13" value="D"> D. Публично унизить пользователя.</label>
  </div>
</div>

<div class="question">
  <p><strong>14. Владелец замечает, что команда выгорает. Что он делает?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q14" value="A"> A. Проводит отдых, пересматривает нагрузку и мотивацию.</label>
    <label><input type="radio" name="q14" value="B"> B. Требует больше активности.</label>
    <label><input type="radio" name="q14" value="C"> C. Игнорирует, ведь работа должна делаться.</label>
    <label><input type="radio" name="q14" value="D"> D. Увеличивает количество отчётов.</label>
  </div>
</div>

<div class="question">
  <p><strong>15. Пользователь утверждает, что модератор удалил сообщение из-за личной неприязни. Что делать админу?</strong></p>
  <div class="answers">
    <label><input type="radio" name="q15" value="A"> A. Проверить журнал действий и оценить по правилам, а не эмоциям.</label>
    <label><input type="radio" name="q15" value="B"> B. Поверить пользователю сразу.</label>
    <label><input type="radio" name="q15" value="C"> C. Защитить модератора без проверки.</label>
    <label><input type="radio" name="q15" value="D"> D. Снять модератора на всякий случай.</label>
  </div>
</div>

<button type="button" onclick="checkAnswers()">Проверить результаты</button>
<div id="result"></div>

</form>

<script>
const correctAnswers = {
  q1: 'A', q2: 'A', q3: 'A', q4: 'A', q5: 'A',
  q6: 'A', q7: 'A', q8: 'A', q9: 'A', q10: 'A',
  q11: 'A', q12: 'A', q13: 'A', q14: 'A', q15: 'A'
};

function checkAnswers() {
  let score = 0;
  let total = Object.keys(correctAnswers).length;
  for (let q in correctAnswers) {
    let answer = document.querySelector(`input[name="${q}"]:checked`);
    if (answer && answer.value === correctAnswers[q]) score++;
  }

  let message = '';
  if (score >= 13) message = 'Отлично! Вы справились с тестом уверенно.';
  else if (score >= 10) message = 'Хорошо! Но есть, что улучшить.';
  else message = 'Нужно пересмотреть подход и укрепить навыки.';

  document.getElementById('result').textContent = 
    `Результат: ${score} из ${total}. ${message}`;
}
</script>

</body>
</html>
