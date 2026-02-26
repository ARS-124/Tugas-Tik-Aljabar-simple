<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Belajar Aljabar Interaktif</title>
<style>
  body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #a1c4fd, #c2e9fb);
    color: #333;
    scroll-behavior: smooth;
  }

  h1, h2, h3 { margin: 0; }

  .container {
    width: 90%;
    max-width: 1000px;
    margin: auto;
    padding: 20px;
  }

  /* Sticky header */
  header {
    position: sticky;
    top: 0;
    background: linear-gradient(to right, #ffecd2, #fcb69f);
    padding: 15px 20px;
    border-radius: 0 0 10px 10px;
    transition: all 0.3s ease;
    z-index: 100;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  header.shrink {
    padding: 8px 20px;
  }

  header h1 {
    font-size: 1.8em;
    transition: font-size 0.3s ease;
  }

  header.shrink h1 {
    font-size: 1.2em;
  }

  .header-description {
    max-height: 40px;
    transition: opacity 0.3s ease;
    opacity: 1;
  }

  header.shrink .header-description {
    opacity: 0;
  }

  .header-buttons {
    margin-top: 10px;
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    justify-content: center;
    transition: all 0.3s ease;
  }

  header.shrink .header-buttons button {
    padding: 6px 12px;
    font-size: 0.9em;
  }

  .header-buttons button {
    padding: 10px 20px;
    font-size: 1em;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    background: linear-gradient(to right, #6a11cb, #2575fc);
    color: white;
    transition: 0.3s;
  }

  .header-buttons button:hover { opacity: 0.9; }

  section {
    background: rgba(255, 255, 255, 0.8);
    padding: 20px;
    border-radius: 10px;
    margin-bottom: 20px;
  }

  .hidden { display: none; }

  .visual-algebra {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    gap: 20px;
  }

  .visual-box {
    background: #f8f9fa;
    padding: 15px;
    border-radius: 10px;
    width: 250px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  }

  .visual-box span {
    display: inline-block;
    font-size: 2em;
    margin: 10px 0;
    color: #007BFF;
  }

  .quiz { display: flex; flex-direction: column; gap: 15px; }
  .question {
    padding: 10px;
    border-left: 5px solid #007BFF;
    background: #e3f2fd;
    border-radius: 5px;
  }

  .question-number { font-weight: bold; font-size: 1.2em; color: #ff6f61; margin-right: 10px; }
  input[type="text"] {
    width: 60px; padding: 5px; font-size: 1em; margin-left: 5px; border-radius: 5px; border: 1px solid #ccc;
  }

  .buttons { text-align: center; margin-top: 20px; }
  button.quiz-btn {
    padding: 10px 20px; font-size: 1em; margin: 5px; border: none; border-radius: 5px;
    cursor: pointer; background: linear-gradient(to right, #6a11cb, #2575fc); color: white; transition: 0.3s;
  }
  button.quiz-btn:hover { opacity: 0.9; }
  .explanation { font-size: 0.95em; color: #555; margin-top: 5px; }
</style>
</head>
<body>

<header id="page-header">
  <h1>Belajar Aljabar Interaktif</h1>
  <p class="header-description">Pelajari aljabar dengan cara yang mudah dan menyenangkan!</p>
  <div class="header-buttons">
    <button onclick="showSection('materi')">Materi Aljabar</button>
    <button onclick="showSection('quiz')">Quiz</button>
  </div>
</header>

<div class="container">
  <section id="materi">
    <h2>Materi Aljabar</h2>
    <div class="visual-algebra">
      <div class="visual-box"><h3>Variabel</h3><span>x</span><p>Simbol yang bisa diganti angka.</p></div>
      <div class="visual-box"><h3>Operasi</h3><span>2x + 3</span><p>2 dikali x ditambah 3</p></div>
      <div class="visual-box"><h3>Penyederhanaan</h3><span>3x + 2x = 5x</span><p>Gabungkan angka sejenis.</p></div>
    </div>
  </section>

  <section id="quiz" class="hidden">
    <h2>Quiz Singkat</h2>
    <div class="quiz" id="quiz-container"></div>
    <div class="buttons">
      <button class="quiz-btn" onclick="checkAnswers()">Cek Jawaban</button>
      <button class="quiz-btn" onclick="shuffleQuestions()">Acak Soal</button>
    </div>
  </section>
</div>

<script>
  const header = document.getElementById('page-header');
  window.addEventListener('scroll', () => {
    if(window.scrollY > 50){ header.classList.add('shrink'); }
    else{ header.classList.remove('shrink'); }
  });

  function showSection(id){
    document.getElementById('materi').classList.add('hidden');
    document.getElementById('quiz').classList.add('hidden');
    document.getElementById(id).classList.remove('hidden');
    document.getElementById(id).scrollIntoView({behavior:'smooth'});
  }

  const questions = [
    { q: "2x + 3x = ?", a: "5x", e: "Gabungkan 2x + 3x menjadi 5x" },
    { q: "4y - 2y = ?", a: "2y", e: "4y dikurangi 2y menjadi 2y" },
    { q: "3x + 2 + 5x + 4 = ?", a: "8x + 6", e: "Gabungkan x dan angka: 3x+5x=8x, 2+4=6" },
    { q: "x + x + x = ?", a: "3x", e: "Jumlahkan x: x+x+x=3x" },
    { q: "6y - y + 2 = ?", a: "5y + 2", e: "6y - y = 5y, tambahkan 2" },
    { q: "2x + 3 - x + 5 = ?", a: "x + 8", e: "2x-x=x, 3+5=8" },
    { q: "7x - 2x + 4 = ?", a: "5x + 4", e: "7x-2x=5x, tambahkan 4" },
    { q: "5y + 3y - 2 = ?", a: "8y - 2", e: "5y+3y=8y, kurangi 2" },
    { q: "x + 4 + 2x + 3 = ?", a: "3x + 7", e: "x+2x=3x, 4+3=7" },
    { q: "4x + 5y + x + 2y = ?", a: "5x + 7y", e: "Gabungkan yang sejenis: 4x+x=5x, 5y+2y=7y" }
  ];
  let shuffledQuestions = [...questions];

  function renderQuiz() {
    const container = document.getElementById("quiz-container");
    container.innerHTML = "";
    shuffledQuestions.forEach((item,index)=>{
      const div = document.createElement("div");
      div.className="question";
      div.innerHTML=`<span class="question-number">${index+1}.</span> ${item.q} <input type="text" id="answer-${index}" placeholder="Jawaban"><div class="explanation" id="exp-${index}"></div>`;
      container.appendChild(div);
    });
  }

  function checkAnswers(){
    shuffledQuestions.forEach((item,index)=>{
      const userAnswer=document.getElementById(`answer-${index}`).value.trim().toLowerCase();
      const exp=document.getElementById(`exp-${index}`);
      if(userAnswer===item.a.toLowerCase()){
        exp.innerHTML=`<span style="color:green">Benar! ✅ ${item.e}</span>`;
      }else{
        exp.innerHTML=`<span style="color:red">Salah ❌ Jawaban: ${item.a}. ${item.e}</span>`;
      }
    });
  }

  function shuffleQuestions(){
    shuffledQuestions.sort(()=>Math.random()-0.5);
    renderQuiz();
  }

  renderQuiz();
</script>

</body>
</html>
