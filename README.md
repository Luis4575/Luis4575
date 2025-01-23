- 👋 Hi, I’m @Luis4575
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Luis4575/Luis4575 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Мощный калькулятор</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="calculator">
    <h1>Мощный Калькулятор</h1>
    <div class="output">
      <input type="text" id="result" readonly>
    </div>
    <div class="buttons">
      <button onclick="clearDisplay()">C</button>
      <button onclick="backspace()">←</button>
      <button onclick="append('%')">%</button>
      <button onclick="append('/')">÷</button>
      <button onclick="append('7')">7</button>
      <button onclick="append('8')">8</button>
      <button onclick="append('9')">9</button>
      <button onclick="append('*')">×</button>
      <button onclick="append('4')">4</button>
      <button onclick="append('5')">5</button>
      <button onclick="append('6')">6</button>
      <button onclick="append('-')">−</button>
      <button onclick="append('1')">1</button>
      <button onclick="append('2')">2</button>
      <button onclick="append('3')">3</button>
      <button onclick="append('+')">+</button>
      <button onclick="append('0')">0</button>
      <button onclick="append('.')">.</button>
      <button class="equal" onclick="calculate()">=</button>
    </div>
    <div class="converter">
      <h2>Конвертер</h2>
      <div class="conversion">
        <input type="number" id="convertValue" placeholder="Введите значение">
        <select id="convertFrom">
          <option value="km">Километры</option>
          <option value="miles">Мили</option>
        </select>
        <button onclick="convert()">Конвертировать</button>
      </div>
      <p id="conversionResult"></p>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>