# 🧠 AI News Automation (بالعربي)

نظام ذكي تلقائي بيقرأ، يحلل، يلخص، ويترجم مقالات الذكاء الاصطناعي من مصادر موثوقة، ويجهزها للنشر على LinkedIn باللغة العربية (اللهجة المصرية).

## ✨ الميزات:

- 📰 يسحب المحتوى من مصادر زي OpenAI, The Gradient, MIT Tech Review
- 🤖 يقيّم كل مقال بناءً على breakthrough, novelty, impact, إلخ.
- 📝 يلخص المقال تقنيًا بدقة
- 🇪🇬 يترجم التلخيص للهجة المصرية (مع الحفاظ على المصطلحات التقنية)
- 🧵 يصيغ البوست بأسلوب LinkedIn احترافي
- 🕓 ينشر تلقائيًا في أوقات الذروة

## 🛠️ الأدوات المستخدمة:

- [n8n](https://n8n.io) – orchestration
- [OpenRouter](https://openrouter.ai) – LLM API
- Google Sheets – التخزين المؤقت وجدولة النشر
- Python – parsing + validation
- Prompt Engineering – لبناء سلسلة توليد دقيقة

## 📂 الملفات

- `n8n-workflow/` – يحتوي على JSON لتصدير الـ workflow
- `prompts/` – البرومبت المستخدم داخل الـ LLM Chain
- `scripts/` – أدوات مساعدة بلغة Python
- `examples/` – أمثلة لمدخلات ومخرجات النظام

## 📸 شعار المشروع

![logo](logo/ai-news-bal3araby.png)

## 📜 License

MIT
---

## 👤 عنّي

 – مهندس ذكاء اصطناعي شغوف بالأتمتة ونشر المعرفة التقنية بالعربية.  
📬 للتواصل: [LinkedIn](https://www.linkedin.com/in/a-elbaz/)


