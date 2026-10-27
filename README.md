# 🤖 امتى تستخدم Claude وامتى تستخدم ChatGPT؟

<p align="center">
  <a href="#prompt"><img src="https://img.shields.io/badge/%E2%9A%A1%20GET%20THE%20PROMPT-COPY%20%26%20PASTE-F97316?style=for-the-badge" alt="خد الـ Prompt على طول" height="44"></a>
  <a href="#fill"><img src="https://img.shields.io/badge/%F0%9F%93%9D%20FILL%20YOUR%20DETAILS-NAME%20%C2%B7%20NICHE%20%C2%B7%20TEXT-2563EB?style=for-the-badge" alt="املا بياناتك" height="44"></a>
</p>

<p align="center"><b>👆 دوس على الزرار البرتقاني وهتروح للـ Prompt على طول — املا الخانات والصقه في Claude.</b></p>

كل يوم حد يسألني: "Claude أحسن ولا ChatGPT؟" 🤔
الإجابة الصح: **مفيش أداة أحسن على طول — فيه أداة أحسن في المهمة بتاعتك النهارده.**

هنا هتلاقي **الفرق بينهم بالظبط من استخدامي اليومي**، وامتى أفتح ده وامتى أفتح ده، و**الـ Prompts اللي بستخدمها** مع كل واحد، وكل Prompt معاه شرح بيعمل إيه.

> 💡 انسخ الـ Prompt زي ما هو، وغيّر بس الحاجات اللي بين `[ ]`.

---

## ⚖️ الفرق في سطرين

| المهمة | أفتح إيه؟ | ليه؟ |
|---|---|---|
| كتابة طويلة بصوتك (Script، بوست، إيميل مهم) | 🟠 **Claude** | بيمسك الـ Style بتاعك كويس وبيكتب كلام طبيعي مش "روبوت" |
| تحليل ملفات كبيرة (PDF، عقود، تقارير، Excel) | 🟠 **Claude** | بيقرا كمية كبيرة من الكلام مرة واحدة ويطلعلك الخلاصة |
| بناء Automations والـ Code | 🟠 **Claude** + **Claude Code** | بيشتغل جوه المشروع بتاعك نفسه، يكتب ويعدل ويشغّل |
| توليد الصور | 🟢 **ChatGPT** | عنده توليد صور جواه على طول، و Claude معندوش ده بشكل مباشر |
| سؤال سريع / استخدام شخصي | 🟢 **ChatGPT** | سريع وسهل للحاجات الخفيفة اليومية |

> ⚠️ ده من تجربتي أنا. الأدوات بتتحدث كل شهر، فجرّب بنفسك على شغلك.

---

## 🔌 الأول: جهّز الأداتين

1. اعمل حساب على [Claude](https://claude.ai) وعلى [ChatGPT](https://chatgpt.com).
2. في الاتنين، اكتب في الإعدادات حاجة عنك (شغلك، جمهورك، اللغة اللي بتحبها) — عشان أي رد يطلع مظبوط من غير ما تعيد كل مرة.
3. لو هتبني Automations أو Code، نزّل **Claude Code** — الشرح الرسمي هنا: [docs.claude.com](https://docs.claude.com/en/docs/claude-code/overview)

لو محتاج مساعدة في Claude: [support.claude.com](https://support.claude.com)

---

<a id="fill"></a>

## 📝 املا بياناتك الأول (مرة واحدة بس)

كل الـ Prompts اللي تحت بتستخدم نفس الخانات دي، املاها مرة وانسخها في كل مكان.

| الخانة | تكتب فيها إيه | مثال |
|---|---|---|
| `[YOUR NAME]` | اسمك | Steven |
| `[CONTENT TYPE]` | شغلك / المجال بتاعك | Content creator about AI automation |
| `[AUDIENCE]` | مين اللي بتكلمه | Egyptian business owners and freelancers |
| `[LANGUAGE]` | اللغة اللي عايز الرد بيها | Egyptian Arabic |
| `[TODAY'S TASK]` | المهمة اللي عايز تعملها النهارده | Write a 60-second reel script about email automation |
| `[YOUR TEXT]` | 2–3 حاجات كتبتها قبل كده بإيدك | (الصق بوستات أو كابشنز قديمة) |
| `[FILE TOPIC]` | الملف اللي هترفعه بيتكلم عن إيه | Q3 sales report |
| `[IMAGE IDEA]` | فكرة الصورة | Thumbnail: me pointing at two laptops |
| `[YOUR QUESTION]` | سؤالك السريع | What's a good name for my AI page? |

<a id="prompt"></a>

### ⚡ Prompt واحد شامل — املا والصق

الصقه في Claude أو ChatGPT: هيقولك أنهي أداة أحسن لمهمتك، ويديك الـ Prompt الجاهز ليها.

```
Here are my details:
- Name: [YOUR NAME]
- What I do: [CONTENT TYPE]
- My audience: [AUDIENCE]
- Reply language: [LANGUAGE]
- Today's task: [TODAY'S TASK]

Act as my AI tools advisor. Do the following in order:
1. Break my task into its parts (writing, file analysis, code/automation, images, quick lookup).
2. For each part, tell me which tool fits better — Claude, Claude Code, or ChatGPT — and give one clear reason.
3. Write me a ready-to-paste prompt for each part, filled with my details above, including the context the tool needs (who I am, who it's for, tone, length, output format).
4. Tell me what files or examples I should attach to get a better result.
5. If any part sends, posts, or changes something, the prompt must say: draft only, do NOT send or publish.

Keep it short and practical. Use a table for step 2.
```

**بيعمل إيه؟** بدل ما تسأل "مين أحسن"، بتسأل "أنهي واحد أحسن في مهمتي النهارده" — وبيطلعلك الخطة والـ Prompts جاهزة بالـ Context بتاعك.

---

## 💬 الـ Prompts خطوة بخطوة

## 🧠 1. عرّف الأداة بنفسك (أهم Prompt)

استخدمه أول ما تفتح أي شات جديد — في Claude أو ChatGPT. ده الفرق بين رد Generic ورد معمول ليك.

```
Before we start, here's my context:
- I'm [YOUR NAME], I work in: [CONTENT TYPE]
- I create for: [AUDIENCE]
- Always reply in: [LANGUAGE]
- I prefer short, direct answers with clear steps. No fluff.

Here are examples of how I write:
[YOUR TEXT]

Study my style (tone, sentence length, words I use, how I open and close).
Summarize my style in 5 bullet points, then wait for my first task.
```

**بيعمل إيه؟** بيعرّف الأداة إنت مين وبتكتب ازاي، فكل اللي بعد كده يطلع بصوتك.
**نصيحة:** في Claude حط الكلام ده في **Project**، وفي ChatGPT حطه في الـ Custom Instructions — عشان متعيدوش كل مرة.

---

## ✍️ 2. كتابة طويلة بصوتك — 🟠 Claude

لما تكتب Script، بوست طويل، أو إيميل مهم.

```
Using my writing style from the examples below, write: [TODAY'S TASK]

My details:
- I'm [YOUR NAME], [CONTENT TYPE]
- Audience: [AUDIENCE]
- Language: [LANGUAGE]

My writing examples:
[YOUR TEXT]

Rules:
- Sound like me, not like an AI. Use my words and rhythm.
- Strong first line (hook), clear middle, one call to action at the end.
- Give me 2 versions: one short, one detailed.
- After writing, list 3 lines that sound "too AI" and rewrite them.
```

**بيعمل إيه؟** بيكتبلك بصوتك نسختين، وبيصلّح بنفسه الجمل اللي شكلها مكتوبة بـ AI.

---

## 📄 3. تحليل ملف كبير — 🟠 Claude

ارفع الملف (PDF، Word، Excel) في Claude والصق ده.

```
I attached a file about: [FILE TOPIC]
I'm [YOUR NAME], [CONTENT TYPE]. Reply in [LANGUAGE].

1. Summarize the file in 5 bullet points.
2. List the 3 most important numbers or facts, with where they appear in the file.
3. List anything risky, unclear, or that needs my decision.
4. Give me 3 action items I should do next.
Only use what's in the file. If something isn't in it, say "not in the file".
```

**بيعمل إيه؟** بيقرا الملف كله ويطلعلك الخلاصة والأرقام والحاجات اللي محتاجة قرار منك.
**نصيحة:** جملة "Only use what's in the file" بتقلل إنه يألّف حاجات مش موجودة.

---

## 📊 4. مقارنة ملفين — 🟠 Claude

```
I attached two files about: [FILE TOPIC]
Compare them in a table: what's the same, what changed, and what's missing in each.
Then tell me in 3 lines which one is better for [AUDIENCE] and why.
Reply in [LANGUAGE].
```

**بيعمل إيه؟** بيقارن نسختين (عرضين، عقدين، تقريرين) في جدول واضح.

---

## ⚙️ 5. خطة Automation قبل ما تبنيها — 🟠 Claude

```
I'm [YOUR NAME], [CONTENT TYPE].
I want to automate this: [TODAY'S TASK]

1. Ask me up to 5 questions about the tools I use and what triggers the task.
2. Then design the automation: trigger → steps → output, as a numbered list.
3. Suggest whether to build it in n8n or with Claude Code, and why.
4. List what can break and how to handle it.
Do not connect, send, or change anything. Plan only.
```

**بيعمل إيه؟** بيعملك خريطة الـ Automation كاملة قبل ما تلمس أي أداة.

---

## 💻 6. بناء الـ Code والـ Automation — 🟠 Claude Code

افتح Claude Code جوه فولدر المشروع والصق ده.

```
Read this project first and explain in 5 lines what it does.

Then build: [TODAY'S TASK]

Rules:
- Show me your plan before writing code, and wait for my OK.
- Make small changes, one step at a time.
- Don't delete files or push anything without asking me.
- Don't put API keys inside the code; use environment variables.
- After you finish, tell me how to test it.
```

**بيعمل إيه؟** Claude Code بيقرا المشروع بتاعك نفسه، يخطط، يستأذنك، وبعدين يبني.
**نصيحة:** دايمًا خليه يوريك الخطة الأول — أرخص بكتير من إنك تصلّح بعدين.

---

## 🎨 7. الصور — 🟢 ChatGPT (والـ Prompt من Claude)

أحسن تكنيك: خلّي Claude يكتبلك وصف الصورة، والصقه في ChatGPT.

**في Claude:**
```
Write a detailed image prompt for: [IMAGE IDEA]
For: [AUDIENCE]
Include: subject, setting, lighting, colors, camera angle, mood, and any text that must appear (spelled exactly).
Format: square 1:1 and vertical 9:16 versions.
```

**في ChatGPT:**
```
Create this image:
(paste the image prompt from Claude here)
Keep any text exactly as written. Give me 2 variations.
```

**بيعمل إيه؟** Claude بيكتب وصف مظبوط، و ChatGPT بيولّد الصورة — كل واحد في اللي هو شاطر فيه.

---

## ⚡ 8. سؤال سريع — 🟢 ChatGPT

```
Quick question, answer in 3 lines max in [LANGUAGE]:
[YOUR QUESTION]
```

**بيعمل إيه؟** للحاجات الخفيفة: معلومة، فكرة سريعة، ترجمة كلمة.

---

## 🔁 9. خلّي الأداتين يراجعوا بعض

لما الشغل مهم، خد رد واحدة وادّيه للتانية.

```
Here's an answer I got from another AI about [TODAY'S TASK]:
(paste the other AI's answer here)

Review it like a strict expert:
1. What's wrong or missing?
2. What's too generic?
3. Rewrite it better for [AUDIENCE] in [LANGUAGE].
```

**بيعمل إيه؟** بتاخد أحسن ما في الاتنين، وبتمسك الأخطاء قبل ما تنشر.

---

## 🇪🇬 تقدر تكتبله بالمصري كمان

```
أنا [اسمك]، وبشتغل في [مجالك].
بكلم [جمهورك].
عايز النهارده أعمل: [مهمتك]

قولي الأول: Claude أحسن ولا ChatGPT للمهمة دي؟ وليه في سطرين.
وبعدين اكتبلي الـ Prompt الجاهز ليها، وكل الردود تكون بالمصري.
```

---

## ⚠️ نصايح مهمة

- 🧠 **الـ Context أهم من الأداة** — أي أداة من غير ما تعرّفها بنفسك هتديك رد Generic.
- ✍️ أي حاجة بتتبعت أو بتتنشر: خليه يعمل **Draft بس**، وإنت اللي تبعت.
- 👀 راجع الأرقام والمعلومات المهمة بنفسك، الـ AI ممكن يغلط.
- 🔒 متحطش باسوردات أو API Keys أو بيانات عملاء حساسة في الشات.
- 🔄 الأدوات بتتحدث كل شوية، فجرّب المهمة نفسها في الاتنين من وقت للتاني.

---

## 🚀 الخلاصة

| قبل | بعد |
|---|---|
| "مين أحسن؟ Claude ولا ChatGPT؟" | "أنهي واحد أحسن في مهمتي النهارده؟" |
| ردود Generic وعادية | ردود بصوتك ومعمولة لجمهورك |
| أداة واحدة لكل حاجة | كل أداة في اللي هي شاطرة فيه |
| بتعيد تعرّف نفسك كل مرة | الـ Context محفوظ ومستخدم في كل Prompt |

---

لو استفدت، تابعني عشان فيه Prompts وأتمتة أكتر جاية 🔥

**Steven Ayman — Vida AI**
