---
title: Code Smells
localeTitle: قانون الروائح
---
## قانون الروائح

تعتبر "رائحة الشمعة" في برمجة الكمبيوتر مؤشراً سطحياً على أنه قد تكون هناك مشكلة فيما يتعلق بنظامك وجودة التعليمات البرمجية الخاصة بك. قد تتطلب هذه المشكلة إعادة بيعها ليتم إصلاحها.

من المهم أن نفهم أن الشفرة كريهة الرائحة تعمل ، لكنها ليست ذات نوعية جيدة.

#### أمثلة

1.  رمز مكرر - كتل من التعليمات البرمجية التي تم نسخها نسخاً متماثلاً عبر قاعدة التعليمات البرمجية. قد يشير ذلك إلى أنك تحتاج إلى تعميم الشفرة في وظيفة واستدعاءها في مكانين ، أو قد يكون الطريقة التي تعمل بها الشفرة في مكان واحد غير مرتبطة تمامًا بالطريقة التي تعمل بها في مكان آخر ، على الرغم من نسخها.
2.  فصول كبيرة - فئات تحتوي على عدد كبير جدًا من أسطر الشفرة. قد يشير هذا إلى أن الفصل يحاول القيام بأشياء كثيرة جدًا ، ويجب تقسيمه إلى فئات أصغر.

#### معلومات اكثر:

*   _إعادة بيع ديون: تحسين تصميم المدونة الحالية - كنت بيك ، مارتن فاولر_
*   _كود النظيفة: دليل للأعمال الحرفية رشيقة - مارتن ، روبرت C. (2009)._
*   [قانون الروائح على ويكيبيديا](https://en.wikipedia.org/wiki/Code_smell)
*   [قانون الروائح على مدونة جيف اتوود (ترميز الرعب)](https://blog.codinghorror.com/code-smells/)
*   [رمز الروائح على وارد Cunningham في C2 ويكي](http://wiki.c2.com/?CodeSmell)
*   [مارتن فاولر - رمز الرائحة](https://martinfowler.com/bliki/CodeSmell.html)