# مهارات كدان متين لـ Claude

## التثبيت (مرة واحدة لكل عضو في الفريق)
1. في تطبيق Claude: Customize ← Plugins ← Personal plugins ← زر + ← Add marketplace ← Add from a repository.
2. الصق رابط هذا المستودع واضغط Sync.
3. ثبّت إضافة kidan-nonprofit.
4. فعّل Sync automatically على السوق (أو استخدم Check for updates).
5. للعمل على رافد: ثبّت إضافة Claude in Chrome وسجّل الدخول في نظام الجمعية.

## التحديث (للمسؤول)
1. عدّل plugins/kidan-nonprofit/skills/nonprofit-accounting/SKILL.md
2. ارفع رقم version في plugins/kidan-nonprofit/.claude-plugin/plugin.json (مثلًا 1.0.0 ← 1.1.0)
3. ارفع التعديل (commit + push) على الفرع الرئيسي — يصل للفريق تلقائيًا.

ملفات تحليلية إضافية: ضعها داخل مجلد المهارة (مثل references/) واذكرها في SKILL.md.
لا تضع أبدًا بيانات عملاء (أكواد، أسماء، أرصدة) في هذا المستودع.
