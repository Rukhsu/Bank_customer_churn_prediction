Bank Customer Churn Prediction

Loyiha haqida

Ushbu loyiha bank mijozlarining ketish (churn) ehtimolini bashorat qilishga qaratilgan. Ma'lumotlar to'plami bank mijozlarining turli xususiyatlarini (masalan, kredit reytingi, yosh, balans, mahsulotlar soni va boshqalar) o'z ichiga oladi va maqsad mijozning bankni tark etish ehtimolini (0 yoki 1) aniqlashdir. Ushbu loyihada CatBoost algoritmidan foydalanib, yuqori aniqlikdagi bashorat modelini yaratishga erishildi.

Loyiha tarkibi

customer-churn-pred.ipynb: Loyiha uchun Jupyter Notebook fayli. 
Unda quyidagilar mavjud:

Ma'lumotlarni yuklash va tahlil qilish.

Ma'lumotlarni oldindan ishlov berish (keraksiz ustunlarni olib tashlash, kategorik o'zgaruvchilarni boshqarish).

CatBoostClassifier yordamida modelni o'qitish va baholash.

Xususiyatlarning ahamiyatini tahlil qilinadi.

Test ma'lumotlari uchun bashoratlar va submission faylini yaratish.

submission.csv: Test ma'lumotlari uchun bashorat qilingan natijalar.
