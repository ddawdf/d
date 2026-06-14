import webbrowser
import os

# كود الموقع المحدث بالأسئلة والخيارات المخصصة لعام 2026
html_content = """
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اختبار الصداقة المخصص 🌟</title>
    <style>
        * { box-sizing: border-box; }
        body { 
            display: flex; justify-content: center; align-items: center; min-height: 100vh; 
            background-color: #0b0c10; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; color: #fff;
        }
        .quiz-container { 
            background-color: #1f2833; padding: 30px; border-radius: 20px; 
            box-shadow: 0px 10px 30px rgba(0,255,204,0.1); width: 100%; max-width: 500px; text-align: center;
        }
        h1 { color: #66fcf1; font-size: 24px; margin-bottom: 25px; }
        .question { font-size: 18px; margin-bottom: 20px; display: none; line-height: 1.6; }
        .question.active { display: block; }
        .answers-grid { display: flex; flex-direction: column; gap: 12px; }
        button { 
            padding: 14px; border-radius: 10px; border: 2px solid #45f3ff; background-color: transparent; 
            color: #fff; font-size: 16px; cursor: pointer; transition: 0.3s ease; text-align: right;
        }
        button:hover { background-color: #45f3ff; color: #000; font-weight: bold; box-shadow: 0 0 15px #45f3ff; }
        .result-box { display: none; }
        .result-box h2 { color: #66fcf1; font-size: 28px; }
        .percentage { font-size: 48px; font-weight: bold; color: #45f3ff; margin: 20px 0; }
        .restart-btn { 
            background-color: #66fcf1; color: #000; font-weight: bold; border: none; 
            width: 100%; margin-top: 15px; text-align: center;
        }
        .restart-btn:hover { background-color: #45f3ff; box-shadow: 0 0 15px #66fcf1; }
    </style>
</head>
<body>

<div class="quiz-container">
    <div id="quiz-box">
        <h1>✨ هل تعرفني جيداً؟ اختبار الصداقة ✨</h1>
        
        <!-- السؤال الأول مخصص -->
        <div class="question active" id="q1">
            <p>1. كم عمري؟ 🤔</p>
            <div class="answers-grid">
                <button onclick="nextQuestion(1, 10)">18 سنة</button>
                <button onclick="nextQuestion(1, 50)">أنت (تعرف عمري بالضبط)</button>
                <button onclick="nextQuestion(1, 20)">22 سنة</button>
            </div>
        </div>

        <!-- السؤال الثاني مخصص -->
        <div class="question" id="q2">
            <p>2. من عم سالم؟ 🧔</p>
            <div class="answers-grid">
                <button onclick="nextQuestion(2, 20)">أبو فهد</button>
                <button onclick="nextQuestion(2, 10)">خالد</button>
                <button onclick="nextQuestion(2, 50)">دحوم</button>
            </div>
        </div>

        <!-- السؤال الثالث مخصص -->
        <div class="question" id="q3">
            <p>3. وش اختباري بكرة؟ 📝</p>
            <div class="answers-grid">
                <button onclick="nextQuestion(3, 10)">رياضيات</button>
                <button onclick="nextQuestion(3, 50)">انقليزي</button>
                <button onclick="nextQuestion(3, 20)">فيزياء</button>
            </div>
        </div>
    </div>

    <!-- صندوق النتيجة النهائية -->
    <div id="result-box" class="result-box">
        <h2>📊 تقرير الصداقة والتحليل</h2>
        <div class="percentage" id="score-percent">0%</div>
        <p id="analysis-text" style="font-size: 16px; line-height: 1.6; color: #c5c6c7;"></p>
        <button class="restart-btn" onclick="restartQuiz()">إعادة الاختبار 🔄</button>
    </div>
</div>

<script>
    let totalScore = 0;
    const maxScore = 150; 

    function nextQuestion(currentQ, points) {
        totalScore += points;
        document.getElementById('q' + currentQ).classList.remove('active');
        
        let nextQ = currentQ + 1;
        let nextElem = document.getElementById('q' + nextQ);
        
        if (nextElem) {
            nextElem.classList.add('active');
        } else {
            showResult();
        }
    }

    function showResult() {
        document.getElementById('quiz-box').style.display = 'none';
        document.getElementById('result-box').style.display = 'block';
        
        let percentage = Math.round((totalScore / maxScore) * 100);
        document.getElementById('score-percent').innerText = percentage + "%";
        
        let analysis = "";
        if (percentage >= 90) {
            analysis = "🥇 خويي الأسطوري! تعرف عني كل صغيرة وكبيرة وجاوبت على الأسئلة الخاصة (أنت، دحوم، وانقليزي) بشكل صح 100%. أهنيك على هالمعزة!";
        } else if (percentage >= 60) {
            analysis = "🥈 كفو، جاوبت على بعض الأشياء صح، لكن يبغالك تركز وتعرف تفاصيلي أكثر عشان تقفل ملف الاختبار!";
        } else {
            analysis = "⚠️ أفا! شكل المعلومات ضاعت منك أو جاوبت عشوائي. ركز معي المرة الجاية وسألك من جديد!";
        }
        document.getElementById('analysis-text').innerText = analysis;
    }

    function restartQuiz() {
        totalScore = 0;
        document.getElementById('result-box').style.display = 'none';
        document.getElementById('quiz-box').style.display = 'block';
        document.getElementById('q1').classList.add('active');
        document.getElementById('q2').classList.remove('active');
        document.getElementById('q3').classList.remove('active');
    }
</script>
</body>
</html>
"""

# حفظ الملف بصيغة ويب
filename = "my_friendship_test.html"
with open(filename, "w", encoding="utf-8") as f:
    f.write(html_content)

print("[+] تم تحديث الأسئلة بنجاح!")
print("[+] الملف باسم (my_friendship_test.html) جاهز الآن.")

# فتحه في المتصفح للتجربة الشخصية أولاً
webbrowser.open('file://' + os.path.realpath(filename))
