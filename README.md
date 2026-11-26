# Listening Heart — قلب يسمع

*(Draft name — to be confirmed.)*

**A free agent skill that teaches AI to listen to how you feel, not just what you say.**

When a person is angry, tired, sad, or happy, a ready-made answer feels cold — even when the information in it is right. Listening Heart is a small instruction skill — one `SKILL.md` — that teaches any agent to read the user's emotional state from their words and tone signals (pace, pauses, message length, punctuation, word choice), work out a reaction that fits that person in that moment, and answer with empathy and presence: acknowledge the feeling once, briefly, in the user's own words; slow down when they are tired or upset; wait while they finish a thought; share their joy briefly when things go well. No stock reassurance loops, no lecturing, no rushing — and honest about being an AI, while staying warm.

## Install

```
npx skills add dagdog16-beep/listening-heart
```

*(Repository link goes live at publication — this package is a draft.)*

Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI and other agent platforms that support skills.

## What it changes

| Without the skill | With the skill |
|---|---|
| "Don't worry, everything will be fine. I'm here for you." (repeated every answer) | The feeling is named once, in the user's own words — then the agent actually helps, or simply stays present |
| A long list of options sent to someone who just said they are exhausted | One small step, in few words, at the user's pace |
| The agent answers a half-finished thought and gets it wrong | The agent waits until the user signals they are done |
| "Great news! Congratulations! 🎉" pasted under any good news | One short, real line that joins this person's happiness |

More pairs in [examples.md](examples.md). The full rules live in [SKILL.md](SKILL.md).

## Privacy

This skill teaches behavior only. It does not record, store, or send anyone's voice, messages, or emotions anywhere. The agent reads the conversation in front of it — nothing more.

## Free — for everyone, including commercial use

This skill is free for everyone, including commercial use. Use it, copy it, build on it — you owe nothing for it.

One small request, meant exactly as written: **if you use this skill commercially, please get in touch — only so we know, and so we can get acquainted (معرفة وتعارف). That is all. It is not a sale, there is no fee, and nothing is owed.** We simply like knowing where our work travels. The skill stays free whether you write to us or not. Full note in [NOTICE.md](NOTICE.md).

## Version 2 is coming soon

A second version (V2) of this skill is on its way, with the same free terms and the same request. Watch this space.

Made by **Ali Ramdani — Dagdog Tools** (Montréal) — small tools for real problems, offline-first: [Gumroad](https://dagdog2.gumroad.com) · [Payhip](https://payhip.com/DagdogTools)

License: free for everyone, including commercial use — see [NOTICE.md](NOTICE.md).

---

# قلب يسمع

*(اسم مسودة — يُثبَّت لاحقاً.)*

**سكيل مجاني للوكلاء يعلّم الذكاء الاصطناعي يسمع إحساسك، مش غير كلامك.**

كي يكون الإنسان زعفان ولا تعبان ولا حزين ولا فرحان، الجواب الجاهز يبان بارد — حتى لو المعلومات اللي فيه صحيحة. «قلب يسمع» بطاقة تعليمات صغيرة (SKILL.md واحد) تعلّم أي وكيل يقرأ الحالة العاطفية للمستعمل من كلامه وإشارات نبرته (السرعة، الوقفات، طول الرسائل، علامات الترقيم، اختيار الكلمات)، ويستنبط ردة فعل تناسب هذاك الإنسان في هذيك اللحظة، ويجاوب بتعاطف وحضور: يعترف بالإحساس مرة وحدة، باختصار، وبكلمات المستعمل نفسه؛ يبطّئ كي يكون تعبان ولا مقلق؛ يستنى حتى يكمل فكرته؛ ويشارك فرحته باختصار كي تمشي الأمور. بلا عبارات طمأنة جاهزة تتكرر، بلا محاضرات، بلا استعجال — وبصدق: يعرف بلي هو ذكاء اصطناعي، ويبقى دافئ.

## التركيب

```
npx skills add dagdog16-beep/listening-heart
```

*(رابط المستودع يتحط وقت النشر — هذه الحزمة مسودة.)*

يخدم مع Claude Code وCodex وCursor وCopilot وGemini CLI وباقي منصات الوكلاء اللي تدعم السكيلات.

## واش يبدّل

| بلا السكيل | بالسكيل |
|---|---|
| «ما تقلقش، كل شيء يتصلح. راني هنا معاك.» (تتعاود في كل جواب) | الإحساس يتسمى مرة وحدة، بكلمات المستعمل — ومن بعد الوكيل يعاون بالصح، ولا يبقى حاضر برك |
| قائمة طويلة تاع خيارات تتبعث لواحد قال بلي راهو منهك | خطوة صغيرة وحدة، بكلمات قليلة، على إيقاع المستعمل |
| الوكيل يجاوب على فكرة ما كملتش ويغلط فيها | الوكيل يستنى حتى يبين المستعمل بلي كمل |
| «أخبار رائعة! مبروك! 🎉» تتلصق تحت أي خبر مليح | سطر قصير وحقيقي يشارك فرحة هذاك الإنسان |

أمثلة أكثر في [examples.md](examples.md). القواعد كاملة في [SKILL.md](SKILL.md).

## الخصوصية

هذا السكيل يعلّم سلوك برك. ما يسجلش، ما يخزنش، ما يبعث حتى صوت ولا رسائل ولا مشاعر تاع أي واحد لأي بلاصة. الوكيل يقرأ المحادثة اللي قدامو — هذا كل شيء.

## مجاني — للجميع، حتى للاستعمال التجاري

هذا السكيل مجاني للجميع، حتى للاستعمال التجاري. استعمله، انسخه، ابنِ عليه — ما عليك حتى شيء مقابله.

طلب صغير واحد، مقصود كيما هو مكتوب بالضبط: **إذا استعملت هذا السكيل لغرض تجاري، من فضلك تواصل معانا — غير باش نعرفو، وباش نتعارفو (معرفة وتعارف). هذا كل شيء. ماشي بيع، ما كاش حتى مقابل، وما يلزمك والو.** برك نحبّو نعرفو وين وصلت خدمتنا. والسكيل يبقى مجاني سواء كتبتلنا ولا لا. النص الكامل في [NOTICE.md](NOTICE.md).

## النسخة الثانية V2 تخرج عن قريب

النسخة الثانية (V2) من هذا السكيل في الطريق، بنفس المجانية ونفس الطلب. تابع هذا المكان.

من **Ali Ramdani — Dagdog Tools** (مونتريال) — أدوات صغيرة لمشاكل حقيقية، تعمل بلا إنترنت: [Gumroad](https://dagdog2.gumroad.com) · [Payhip](https://payhip.com/DagdogTools)

الترخيص: مجاني للجميع، حتى للاستعمال التجاري — شوف [NOTICE.md](NOTICE.md).
