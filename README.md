<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Интернет қауіпсіздігі</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(to bottom, #e8f5fe, #f3f3f3);
            color: #333;
        }
        header {
            background: #0078d7;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            margin: 5px 0 0;
            font-size: 1.2rem;
        }
        main {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
            gap: 20px;
        }
        .country-card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
            padding: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .country-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }
        .country-card img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .country-card h2 {
            margin: 10px 0;
            font-size: 1.8rem;
            color: #0078d7;
        }
        .country-card a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #0078d7;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background 0.3s ease;
        }
        .country-card a:hover {
            background: #005bb5;
        }
    </style>
</head>
<body>
    <header>
        <h1>Интернет қауіпсіздігі</h1>
        <p>Ақпараттық қауіпсіздік</p>
    </header>
    <main>
        <div class="country-card">
            <img src="https://via.placeholder.com/300x200?text=Қазақстан" alt="Қазақстан">
            <h2>Интернет қауіпсіздігі</h2>
            <a href="5.html">Толығырақ</a>
        </div>
        <div class="country-card">
            <img src="https://via.placeholder.com/300x200?text=Өзбекстан" alt="Өзбекстан">
            <h2>Фишинг</h2>
            <a href="6.html">Толығырақ</a>
        </div>
        <div class="country-card">
            <img src="https://via.placeholder.com/300x200?text=Қырғызстан" alt="Қырғызстан">
            <h2>Зиянды бағдарлама</h2>
            <a href="7.html">Толығырақ</a>
        </div>
        <div class="country-card">
            <img src="https://via.placeholder.com/300x200?text=Тәжікстан" alt="Тәжікстан">
            <h2>Бізден кеңес</h2>
            <a href="8.html">Толығырақ</a>
        </div>
        <div class="country-card">
            <img src="https://via.placeholder.com/300x200?text=Түрікменстан" alt="Түрікменстан">
            <h2>Кері байланыс</h2>
            <a href="9.html">Толығырақ</a>
        </div>
    </main>
</body>
</html>
‎5.html
+80
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,80 @@
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Қазақстан</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #f3f3f3;
            color: #333;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        header h1 {
            font-size: 2.5rem;
            color: #0078d7;
        }
        header a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #0078d7;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background 0.3s ease;
        }
        header a:hover {
            background: #005bb5;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        .content img {
            width: 100%;
            border-radius: 8px;
        }
        .content h2 {
            font-size: 1.8rem;
            color: #0078d7;
        }
        .content p {
            font-size: 1rem;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <h1>Интернет қауіпсіздігі</h1>
        <a href="3.html">← Басты бетке оралу</a>
    </header>
    <div class="content">
        <img src="https://via.placeholder.com/800x400?text=Қазақстан" alt="Қазақстан">
        <h2>Интернет қауіпсіздігі</h2>
        <p>
        Интернет қауіпсіздігі, сондай-ақ интернеттегі қауіпсіздік, киберқауіпсіздік және электрондық қауіпсіздік (электрондық қауіпсіздік), ақпараттық технологияларды (МАЖ) қолдану арқылы адамдарға зиянды азайтуға мүмкіндік беретін саясатты, тәжірибені және процестерді білдіреді.
Интернет қолданушыларының саны бүкіл әлемде өсіп келе жатқандықтан,[1] интернет қолданушылары, үкіметтер мен ұйымдар Интернетті пайдаланатын балалар мен жасөспірімдер мен қарттардың қауіпсіздігіне алаңдаушылық білдірді. 45% -дан астамы қандай-да бір түрге төзгендерін мәлімдеді киберқауіпсіздік. Қауіпсіз Интернет күні бүкіл әлемде ақпан айында интернет қауіпсіздігі туралы хабардарлықты арттыру мақсатында атап өтіледі.[2] Ішінде Ұлыбритания Интернеттегі қауіпсіздікті қамтамасыз ету акциясы мемлекеттік органнан демеушілік көмек алды Ауыр ұйымдасқан қылмыс агенттігі (SOCA) сияқты ірі интернет-компаниялар Microsoft және EBay.[3]
Интернеттегі қауіпсіздік қажет және расталған, өйткені көптеген кәсіпкерлер интернеттегі шабуылдардың шектен шығуына тап болды, соның салдарынан жәбірленушілер өз өмірін қиды, суицидке барды немесе психологиялық ауытқушылық. Кибершабуылдар қосулы кәсіпорындар және ұйымдар өсіп келеді тренд, және Африка босатылмайды. Тұтынушылардың қауіпсіздігі туралы айтпағанда, ұйымдардың өнімділігі, кірісі және клиенттердің сенімі кері әсерін тигізеді.[4]
       	   </p>
        <h2>Ақпараттық қауіпсіздік</h2>
		
		<p>Ақпараттық қауіпсіздік
Сияқты құпия ақпарат жеке ақпарат және жеке басын куәландыратын құжат, парольдер көбінесе жеке меншікпен және жеке өмірмен байланысты және егер олар жария етілсе, қауіпсіздікке қатысты мәселелер туындауы мүмкін. Жеке ақпаратқа рұқсатсыз қол жеткізу және пайдалану келесі салдарға әкелуі мүмкін жеке тұлғаны ұрлау, сондай-ақ мүлікті ұрлау. Жалпы себептері ақпараттық қауіпсіздік бұзушылықтарға мыналар жатады</p>
    </div>
</body>
</html>
‎6.html
+71
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,71 @@
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Қазақстан</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #f3f3f3;
            color: #333;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        header h1 {
            font-size: 2.5rem;
            color: #0078d7;
        }
        header a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #0078d7;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background 0.3s ease;
        }
        header a:hover {
            background: #005bb5;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        .content img {
            width: 100%;
            border-radius: 8px;
        }
        .content h2 {
            font-size: 1.8rem;
            color: #0078d7;
        }
        .content p {
            font-size: 1rem;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <h1>Фишинг</h1>
        <a href="3.html">← Басты бетке оралу</a>
    </header>
    <div class="content">
        <img src="https://via.placeholder.com/800x400?text=Қазақстан" alt="Қазақстан">
        <h2>Фишинг</h2>
        <p>
Фишинг бұл интернет арқылы парольдер, несиелік карталар туралы ақпарат және т.б. сияқты жеке ақпаратты алуға тырысып, алаяқтар өздерін сенімді ақпарат көзі ретінде жасыратын алаяқтық түрі. Бұл жалған веб-сайттар көбінесе пайдаланушының күдігін болдырмау үшін өздерінің заңды аналогтарымен бірдей көріну үшін жасалған.[5] Әдетте, хакерлер жеке ақпаратты сұрайтын үшінші тарапқа электрондық пошта арқылы хабарлама жібереді және олар мұны шабуылды жүзеге асыру үшін кіру нүктесі ретінде пайдаланады.    	   </p>
</div>
</body>
</html>
‎7.html
+71
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,71 @@
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Қазақстан</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #f3f3f3;
            color: #333;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        header h1 {
            font-size: 2.5rem;
            color: #0078d7;
        }
        header a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #0078d7;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background 0.3s ease;
        }
        header a:hover {
            background: #005bb5;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        .content img {
            width: 100%;
            border-radius: 8px;
        }
        .content h2 {
            font-size: 1.8rem;
            color: #0078d7;
        }
        .content p {
            font-size: 1rem;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <h1>Зиянды бағдарлама</h1>
        <a href="3.html">← Басты бетке оралу</a>
    </header>
    <div class="content">
        <img src="https://via.placeholder.com/800x400?text=Қазақстан" alt="Қазақстан">
        <h2>Зиянды бағдарлама</h2>
        <p>
Зиянды бағдарлама, әсіресе шпиондық бағдарлама, болып табылады зиянды бағдарламалық жасақтама құпия сөздер сияқты жеке ақпаратты пайдаланушының келісімінсіз немесе білімінсіз жинауға және беруге арналған. Олар көбінесе электрондық пошта, бағдарламалық жасақтама және бейресми орындардағы файлдар арқылы таратылады. Зиянды бағдарламалық жасақтама қауіпсіздіктің ең кең таралған мәселелерінің бірі болып табылады, өйткені файлдың қайнар көзіне қарамастан файлдың вирус жұқтырғанын анықтау мүмкін емес.</p>
</div>
</body>
</html>
‎8.html
+109
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,109 @@
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Қазақстан</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #f3f3f3;
            color: #333;
            padding: 20px;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        header h1 {
            font-size: 2.5rem;
            color: #0078d7;
        }
        header a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #0078d7;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background 0.3s ease;
        }
        header a:hover {
            background: #005bb5;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
        }
        .content img {
            width: 100%;
            border-radius: 8px;
        }
        .content h2 {
            font-size: 1.8rem;
            color: #0078d7;
        }
        .content p {
            font-size: 1rem;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <header>
        <h1>Бізден кеңес</h1>
        <a href="3.html">← Басты бетке оралу</a>
    </header>
    <div class="content">
        <img src="https://via.placeholder.com/800x400?text=Қазақстан" alt="Қазақстан">
        <h2>Бізден кеңес</h2>
        <p>Интернетте қауіпсіздік сақтау үшін алаяқтық әрекеттерден қалай сақтану керектігін түсіну маңызды. Мошенниктер (алаяқтар) көбінесе адамдарды сендіру арқылы жеке мәліметтерін, ақша қаражатын немесе басқа құнды ақпаратты алуға тырысады. Төменде интернет алаяқтарынан қорғануға арналған негізгі кеңестер берілген:
</p>
<p><b>1. Жалған сілтемелер мен хаттарға назар аударыңыз</p></b>
	<p>•	Жіберушінің кім екенін анықтамай тұрып, бейтаныс адамдардан келген хаттар мен хабарламалардағы сілтемелерге баспаңыз.
	</p><p>•	Электрондық пошта немесе SMS арқылы банктен немесе басқа ұйымдардан келген күмәнді хаттарды мұқият тексеріңіз. Әдетте, олар нақты мекемелердің атын пайдаланып, сізден төлем жасау немесе жеке ақпаратты енгізуіңізді сұрайды.
</p>
<p>Мысал:
Егер хатта “Құпия сөзіңізді қалпына келтіру үшін осында басыңыз” деген сілтеме болса, бірінші кезекте ол сайттың ресми екенін тексеріңіз.
</p>
<p><b>2. Құпия сөздерді қауіпсіз сақтаңыз</b></p>
	<p>•	Құпия сөздеріңізді күрделі етіп жасаңыз: әріптер, сандар және арнайы символдарды пайдаланыңыз (мысалы: Qwerty2025!).
	</p><p>•	Барлық сайттарда бірдей құпия сөзді қолданбаңыз.
	</p><p>•	Құпия сөздеріңізді ешкімге айтпаңыз және оларды жалпыға қолжетімді жерлерде сақтамаңыз.
</p>
<p><b>3. Қоғамдық Wi-Fi желілеріне абай болыңыз</b>
	</p><p>•	Қоғамдық Wi-Fi желілерін қолданған кезде жеке мәліметтерді енгізбеңіз немесе банк операцияларын орындамаңыз.
	</p><p>•	Қосымша қауіпсіздік үшін VPN (Virtual Private Network) қолдануға болады. Ол сіздің деректеріңізді шифрлап, оларды бөгде адамдардан қорғайды.
</p>
<p><b>4. Интернет дүкендерден абай болыңыз</b>
	</p><p>•	Тек ресми және танымал интернет дүкендерден сауда жасаңыз.
	</p><p>•	Егер сайт өте арзан баға немесе ерекше ұсыныстар ұсынса, ол алаяқтық болуы мүмкін.
	</p><p>•	Төлем жасау үшін тек қауіпсіз төлем жүйелерін (мысалы, PayPal немесе банк картасының ресми порталын) қолданыңыз.
</p>
<p><b>5. Жеке мәліметтеріңізді құпия ұстаңыз</b>
	</p><p>•	Әлеуметтік желілерде жеке ақпаратты (телефон нөмірі, мекенжайы, банк деректері) жарияламаңыз.
	</p><p>•	Егер бейтаныс адамдар сізден жеке мәліметтерді сұраса, бермеуге тырысыңыз.
</p>
<p><b>6. Антивирус пен жүйелік жаңартуларды орнатыңыз</b>
</p><p>	•	Құрылғыңызда антивирустық бағдарламалар орнатылып, жаңартылып тұруы керек. Олар зиянды бағдарламалар мен фишинг сайттарынан қорғайды.
	</p><p>•	Операциялық жүйе мен қосымшаларды үнемі жаңартып отырыңыз. Ескірген жүйелерде әлсіздіктер болуы мүмкін.
</p>
<p><b>7. Мошенниктердің жиі қолданатын әдістері</b>
</p><p>	•	Фишинг: Жалған сайттар арқылы жеке деректерді ұрлау.
	</p><p>•	Қоңырау арқылы алдау: Банк қызметкері болып хабарласып, жеке деректерді сұрайды.
	</p><p>•	Жалған ұтыстар: Сізге “ұтыс” жеңіп алғаныңызды айтып, алдын ала төлем жасауды сұрайды.
</p>
<p><b>Егер алдансаңыз не істеу керек?</b>
	</p><p>1.	Банкпен байланысыңыз: Егер сіздің банк шотыңызға қауіп төнсе, картаны бұғаттауды сұраңыз.
	</p><p>2.	Құзырлы органдарға хабарласыңыз: Қазақстанда бұл туралы полицияға немесе Киберқауіпсіздік орталығына (KZ-CERT) хабарласа аласыз.
	</p><p>3.	Барлық аккаунттарыңызды тексеріңіз: Жеке деректеріңізді өзгертуді және құпия сөздерді жаңартуды ұмытпаңыз.</p>
	</div>
</body>
</html>
‎9.html
+61
Original file line number	Diff line number	Diff line change
@@ -0,0 +1,61 @@
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WhatsApp арқылы хабарласу</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            text-align: center;
            background-color: #fff;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 24px;
            margin-bottom: 20px;
        }
        p {
            font-size: 18px;
            margin-bottom: 20px;
        }
        .whatsapp-link {
            font-size: 20px;
            color: #25d366;
            text-decoration: none;
            font-weight: bold;
            border: 2px solid #25d366;
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .whatsapp-link:hover {
            background-color: #128c7e;
            color: #fff;
        }
    </style>
</head>
<body>
<div class="container">
    <h1>Кері байланыс</h1>
    <p>Сіз бізге WhatsApp арқылы хабарласа аласыз:</p>
    <a href="https://wa.me/77058304601" class="whatsapp-link" target="_blank">
        +7(705)830-46-01
    </a>
</div>
</body>
</html>
