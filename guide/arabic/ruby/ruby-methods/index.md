---
title: Ruby Methods
localeTitle: طرق روبي
---
## المقدمة

هل سبق لك أن سمعت عن لغات البرمجة التي تشير إلى الوظائف؟ إذا تم تشفيرها في برامج مثل JavaScript ، فيجب أن تكون على دراية بها. لدى روبي أيضًا وظائف لكننا نشير إليها كطرق. إن الطرق هي مجرد مجموعة من الكودات التي يتم إعطاؤها اسمًا لسهولة الاستخدام وإمكانية الوصول وهي حاسمة في نهج DRY (عدم تكرار نفسك) في البرمجة.

## إنشاء واستخدام الأساليب

يجب دوماً تعريف الطرق كـ صغيرة (يمكنك فصل الكلمات بتسطير أسفل السطر إذا كنت تحب) وإلا قد يتم الخلط بينها كـ ثوابت. يجب أيضًا تحديد الطرق قبل محاولة الاتصال بها فعليًا ، وبذلك تكون القاعدة الأساسية هي إنشاء طرقك في بداية ملفك والاتصال بها لاحقًا عند الحاجة. حاول دائمًا تجنب أسماء طرق الكلمة الواحدة عند الضرورة ، فأنت تريد أن تكون قادرًا على معرفة أكثر أو أقل ما تفعله هذه الطريقة دون الحاجة إلى الحفر في الداخل.

## بناء الجملة

من السهل إنشاء طرق ، يمكن إنشاؤها دون القدرة على قبول المعلمات ، مع المعلمات وحتى مع معلمات محددة مسبقًا إذا لم يتم تقديم أي منها.

#### طريقة بسيطة

 `def my_method 
  code goes here 
 end 
` 

#### معلمة قبول الطريقة

 `def my_method (param1, param2) 
  param1 + param2 
 end 
` 

#### طريقة paramter المعرفة مسبقًا (تُستخدم المعلمات المحددة مسبقًا عند عدم تقديم أي منها)

 `def my_method (param1 = parameter1, param2 = parameter2) 
  parm1 + parm2 
 end 
` 

## العودة في أساليب

ستكون القيمة المرتجعة لطريقة ما هي آخر تعبير تم تقييمه في الطريقة. ومع ذلك ، يمكنك استخدام الكلمة الأساسية للعودة لإرجاع أكثر من قيمة واحدة إذا لزم الأمر.