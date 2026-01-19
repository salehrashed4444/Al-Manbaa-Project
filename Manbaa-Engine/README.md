<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>محرك رصد ختم المنبع 🚀</title>
    <style>
        body { font-family: sans-serif; text-align: center; background-color: #f4f4f4; padding: 20px; }
        .container { background: white; padding: 30px; border-radius: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); max-width: 600px; margin: auto; }
        input { width: 80%; padding: 12px; margin: 20px 0; border: 2px solid #3498db; border-radius: 5px; font-size: 16px; }
        .rocket-btn { font-size: 50px; cursor: pointer; transition: 0.3s; display: block; margin: 10px auto; }
        .rocket-btn:hover { transform: scale(1.2) rotate(-45deg); }
        #result { font-weight: bold; color: #2c3e50; margin-top: 20px; font-size: 1.2em; }
    </style>
</head>
<body>
    <div class="container">
        <h1>🛡️ محرك الرصد (Manbaa Engine)</h1>
        <p>تفعيل <b>سلاح ابن آدم</b> لرصد الـ 193 دولة</p>
        
        <div class="rocket-btn" onclick="startSearch()">🚀</div>
        
        <input type="text" id="countryInput" placeholder="ادخل اسم الدولة لرصدها...">
        
        <div id="result">جاهز للانطلاق...</div>
    </div>

    <script>
        function startSearch() {
            const input = document.getElementById('countryInput').value;
            const res = document.getElementById('result');
            if(input) {
                res.innerHTML = "🔍 جاري رصد " + input + " ضمن مصفوفة الـ 193 دولة... تم التوثيق بختم المنبع ✅";
            } else {
                res.innerHTML = "يرجى إدخال اسم الدولة أولاً 🚀";
            }
        }
    </script>
</body>
</html>
