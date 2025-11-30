# ✨ Reaction Reel

### 💎 1-Bosqich: Asosiy Zaminni Qurish (Backend & Client Core)
**Maqsad:** Flutter ilovasi ulanishi mumkin bo‘lgan ma'lumotlar bazasi va API nuqtasini yaratish.

* **Vazifa 1.1 (Backend):** Django/FastAPI loyihasini yaratish.
* **Vazifa 1.2 (Backend):** Videolarni saqlash uchun API nuqtasini (`/videos`) yaratish va bir nechta sinov videosini yuklash.
* **Vazifa 1.3 (Client - Flutter):** Flutter ilovasini sozlash, **Backend API'ga ulanish** va videolarni ro‘yxat shaklida olish.
* **Vazifa 1.4 (Client - Flutter):** Yaratilgan Flutter ilovasida **Reels ko‘rish interfeysini** (`video_player` yordamida) ishga tushirish.

### 📤 2-Bosqich: Oddiy Avtomatik Yuklash va Tarqatish (Telegram Inline)
**Maqsad:** Telegram orqali kontentni boshqarish va Instagramga yuklash funksiyasini qurish.

* **Vazifa 2.1 (Backend):** **Instagram Content Publishing API** ruxsatlarini olish.
* **Vazifa 2.2 (Backend):** Telegram Bot API yordamida videoni **to‘g‘ridan-to‘g‘ri Instagramga yuklash** (yoki yuklashga tayyorlash) funksiyasini yozish.
* **Vazifa 2.3 (Telegram UI):** Telegramga yuborilgan video ostida videoning nomi va teglarini aks ettiruvchi **inline tugmani** qo‘shish (bu tugma yuklashni amalga oshiradi).
* **Vazifa 2.4:** Yuklash tugmasi bosilganda, original nomi va teglari bilan Instagramga yuklashni test qilish.

### 📝 3-Bosqich: Kontentni Tahrirlash Orqali Yuklash (Inline Web App)
**Maqsad:** Yuklashdan oldin matn va teglar kabi metadata'ni tahrirlash imkonini berish.

* **Vazifa 3.1 (Backend):** Telegram Botdan keluvchi so‘rovlarni qabul qilish va **video metadata'sini tahrirlash** uchun alohida veb-sahifani (API nuqtasi orqali) yaratish.
* **Vazifa 3.2 (Telegram UI):** Telegramdagi inline tugmani shu **veb-sahifaga ulab qo‘yish** (Telegram Web App funksiyasiga o‘xshash).
* **Vazifa 3.3:** Foydalanuvchi veb-sahifada nom va teglarni o‘zgartirgandan so‘ng, ularni yangi metadata bilan Instagramga yuklashni yakunlash.

### 🎬 4-Bosqich: Asosiy Reaction Avtomatizatsiyasi (Ovozsiz Variant)
**Maqsad:** Flutterda sinxron yozib olish va serverda faqat ovozsiz montajni avtomatlashtirish.

* **Vazifa 4.1 (Client - Flutter):** **Video ko‘rish vaqti bilan birga, kamerani sinxron yoqish va yozishni** amalga oshirish mantiqini yozish.
* **Vazifa 4.2 (Client - Flutter):** Yozib olingan videoni (reaksiyani) serverga yuborish funksiyasini yakunlash.
* **Vazifa 4.3 (Backend/FFmpeg):** FFmpeg orqali faqat **ovozsiz (original audio + sizning ovozingiz o‘chirilgan) montaj variantini** yaratish va natijani Telegramga yuborish.

### 🎤 5-Bosqich: Kengaytirilgan Reaction Mantiqi (Kombinatsiyalar)
**Maqsad:** Oldi/orqa kamera va audio variantlarini o‘z ichiga olgan eng murakkab montaj kombinatsiyasini avtomatlashtirish.

* **Vazifa 5.1 (Client - Flutter):** Oldi va orqa kamerani **parallel yozib olish** va serverga yuborish mantiqini yozish.
* **Vazifa 5.2 (Backend/FFmpeg):** Barcha kirish fayllaridan (2 ta video, 2 ta audio) foydalanib, FFmpeg orqali **har xil montaj kombinatsiyalarini** (masalan, ovozli + orqa kamera) yaratish buyrug‘ini yozish.
* **Vazifa 5.3:** Bir tugma orqali (Telegram orqali) ushbu murakkab montajni ishga tushirish imkoniyatini yaratish.
