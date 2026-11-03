# 3 Interactive Network Demos

مواقع تفاعلية مستقلة لعرض 3 أفكار أمام الدكتور. المحرك يعمل داخل المتصفح فقط بآلية Discrete-event.

## Open demos
- [Network Escape](network-escape/)
- [MeetBlackbox](meetblackbox/)
- [Operation Total Lockdown](total-lockdown/)

## Features
- Sensor message generation, AP/router path, gateway queuing, packet drops, congestion, QoS and controlled gateway isolation.
- Live dashboard with counters, chart, events and JSON export.
- Repeatable A/B simulation comparisons with fixed seeds.
- Lockdown uses Logistic Regression trained in browser on **synthetic** data with separate synthetic holdout; this does not prove real-world cybersecurity accuracy.

## تشغيل
حمّل ملفات المستودع وافتح `index.html` من أي متصفح. أو فعّل GitHub Pages في Settings → Pages → Deploy from branch → main / (root) → Save.

## Accuracy and limits
هذه **محاكاة حسابية** وليست شبكة حقيقية؛ لا توجد ESP32 أو Wi-Fi radio أو MQTT broker أو Linux kernel firewall. النتائج لا تصلح كبديل لقياسات مختبرية على هاردوير حقيقي.

## Public site after enabling GitHub Pages
- https://rot520734-lang.github.io/simulation/
- https://rot520734-lang.github.io/simulation/network-escape/
- https://rot520734-lang.github.io/simulation/meetblackbox/
- https://rot520734-lang.github.io/simulation/total-lockdown/
