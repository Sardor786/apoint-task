### ✅ APOINT TASK

**Muhim:**
Avval quyidagilarni barchasini diqqat bilan o'qing.

**Maqsad:**
Nomzodning Reactjs, Code structure, Autentifikatsiya, Data bilan ishlash bo‘yicha ko‘nikmalarini baholash.

---

### 🔧 Texnologiyalar

-   `Reactjs` – asosiy framework

---

### Topshiriq

1. **Login:**

    - Login page bo'lsin va autorizatsiyasiz boshqa routega o'ta olmaslik kerak
    - `POST /hr/user/sign-in` queryda `include=token`
    - Body:

    ```json
    {
    	"username": "",
    	"password": ""
    }
    ```

2. **Fetch:**

    - `GET /reports/reports/materials` queryda `sort=name` `&start=` shu oyning boshi `&end=` shu oyning oxiri

3. **Table:**

    - Ma’lumotlarni ko’rsatish uchun table yasang.
    - Table qo’shimcha kutubxonalarsiz yasalashi kerak.
    - Datada `parent` va `category` keylar bor shu bo'yicha groupping qilish kerak va collapse ko'rinishida chiqarish kerak. (parent -> category -> item)
    - Data category bo'yicha va parent bo'yicha total count total sumlarni hisoblab chiqarish.
    - Eng tepadan umumiy barcha field bo'yicha total.

    - Keys

    ```json
    {
    	"remind_end_amount": "",
    	"remind_end_sum": "",
    	"remind_income_amount": "",
    	"remind_income_sum": "",
    	"remind_outgo_amount": "",
    	"remind_outgo_sum": "",
    	"remind_start_amount": "",
    	"remind_start_sum": ""
    }
    ```

4. **Taxminiy ko'rinish:**
   [Example](./images/example.png)

### Ko'rsatmalar

-   Muddat 48 soat.
-   Ishlatish uchun sizga domain, username va password beriladi.
-   https://t.me/sr_shodmonov ga yozing.
-   Ishingizni tekshirish uchun netlify yoki vercelga yuklang.
-   Tayyor bo‘lgach, GitHub linkni va site link yuboring.
-   Savollar bo‘lsa, issue qoldiring.

---

# Omad!
