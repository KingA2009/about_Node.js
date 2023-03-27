# 1.1)Node.js nima?
```Node.js
Node.js - bu Windows , Linux , Unix , macOS va boshqalarda ishlashi mumkin bo'lgan o'zaro platforma ,
ochiq manba server muhiti. Node.js JavaScript ish vaqti muhiti boʻlib ,
V8 JavaScript Engine da ishlaydi va JavaScript kodini veb-brauzerdan tashqarida bajaradi .
```

# 1.2)Node.js xususiyatlari
```Node.js
Buferlash yo'q - Node.js ilovalari hech qachon hech qanday ma'lumotni bufer
Juda tez – Google Chrome’ning V8 JavaScript dvigatelida yaratilgan Node.js kutubxonasi kodni bajarishda juda tezdir.lamaydi. Ushbu ilovalar shunchaki ma'lumotlarni qismlarga bo'lib chiqaradi.
Asinxron va hodisalarga asoslangan - Node.js kutubxonasining barcha API'lari asinxron, ya'ni bloklanmaydi. Bu aslida Node.js-ga asoslangan server hech qachon API ma'lumotlarini qaytarishini kutmasligini anglatadi. Server qo‘ng‘iroq qilgandan so‘ng keyingi APIga o‘tadi va Events of Node.js bildirishnoma mexanizmi serverga avvalgi API chaqiruvidan javob olishga yordam beradi.
```

# 1.3)Node.js-dan kim foydalanadi?
```Node.js
Quyida Node.js dan foydalanayotgan loyihalar, ilovalar va kompaniyalarning toʻliq roʻyxatini oʻz ichiga olgan github wiki-dagi havola. Ushbu ro'yxatga eBay, General Electric, GoDaddy, Microsoft, PayPal, Uber, Wikipins, Yahoo! va Yammer kiradi.
```

# 1.4)Node.js-dan qayerda foydalanish kerak?
* I/U bilan bog'langan ilovalar
* Ma'lumotlar oqimi uchun ilovalar
* Haqiqiy vaqtda ma'lumotlarni ko'p talab qiluvchi ilova(DIRT)
* JSON API-ga asoslangan ilovalar
* Bir sahifali ilovalar


# 2.1) Versiya
```
C:\Users\777>node -v
v18.14.2

C:\Users\777>
```


# 3.1)
##  Code
```
http.createServer(function (request, response) {

   response.writeHead(200, {'Content-Type': 'text/plain'});
   
   response.end('Hello World\n');
}).listen(8081);

console.log('Server running at http://127.0.0.1:8081/');

 ```
## about
### //http modulini yuklash va qaytarilgan HTTP misolini http o'zgaruvchisiga quyidagi tarzda saqlayapti
### //yaratilgan http misolidan foydalanib va server misolini yaratish uchun http.createServer() usulini chaqirib va
### ///keyin uni server misoli bilan bog'langan tinglas usuli yordamida 8081 portga bog'lyapti.

# 3.2)

















<!-- ![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQtKOdbHk7qew2XJ3JVHdJZjCUnjGJ6nHGHNMu9i3d4&s) -->