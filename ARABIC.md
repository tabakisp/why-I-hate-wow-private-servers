# &#x202b; لماذا اكره معظم السيرفرات الخاصة للعبة WoW

*&#x202b; كتبه 'Francesco Borzi المعروف أيضاً باسم Shin *

&#x202b; لماذا لا يزال هناك الكثير من الاخطاء في السيرفرات الخاصة لWoW, علي الرغم من أنها موجودة منذ سنوات عديدة؟

![Wow-facepalm](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/wow-facepalm.jpeg)

&#x202b; لا تقلق, هذه ليست محاضرة حقوق الطبع والنشر المعتادة عن شركة Blizzard.
&#x202b; أريد فقط أن أشرح لماذا أكره معظم السيرفرات الخاصة ل[World of Warcraft](https://en.wikipedia.org/wiki/World_of_Warcraft)

## مقدمة

&#x202b; لقد كنت مبهورا بمحاكاة WoW منذ أن كان عمري 14 عاما. أتذكر أنه في المرة الأولي التي انضممت فيها إلى أحد هذه "العوالم الخاصة"، كان هناك الكثير من الأخطاء، ولكن كان بإمكانك اللعب مجانًا على الأقل. كما تعلم, لم أكن املك الا القليل من المال في ذلك الوقت, لذا لما يكن لدي أي بديل.

&#x202b; في سن ال15 بدأت أتساءل كيف تعمل الخوادم الخاصة بالفعل وكيف يمكن أن توجد, خاصة من منظور تقني. هل سرق أحدهم الكود من [Blizzard](https://en.wikipedia.org/wiki/Blizzard_Entertainment) ربما؟ لم يكن لدي أي فكرة - كنت صغيرا جدا وعديم الخبرة في ذلك الوقت! على الرغم من ذلك، بدأت في العبث، وبمساعدة صديق قديم لي (Fabio), تمكنت أخيرًا من تثبيت سيرفر WoW على جهاز الكمبيوتر الخاص بي.

&#x202b; في ذلك الوقت لم أكن أتخيل مقدار السعادة التي كنت سأحصل عليها وكم الأشياء التي كنت سأتعلمها بفضل هذا العالم السحري.

&#x202b; قد يبدو الأمر غريبًا، لكن هذا العالم لا يزال يسحرني الآن، وأنا بالغ، لدرجة أنني خصصت [رسالة ماجستير كاملة في علوم الحاسب الآلي لهذا الموضوع](https://community.trinitycore.org/topic/13025-just-thank-you-wow-emulation).

![wow-emulation-thesis](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/wow-emulation-thesis.jpeg)

لكن مع ذلك: **أنا أكره معظم السيرفرات الخاصة وأريد حقاً أن أشرح السبب.**

## بعض المصطلحات التقنية

![Wow-sleeping](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/wow-sleeping.jpg)

&#x202b; لكي أجعلك تفهم وجهة نظري، فأنا بحاجة إلى التوقف عند نقطة تقنية صغيرة حول إجراءات عمل WoW، والتي سأحاول وضعها في كلمات بسيطة.

### &#x202b; كيف تعمل لعبة World of Warcraft الأصلية

&#x202b; على مستوى البرمجيات، هناك برنامجان يمكن اعتبارهما الفاعلين الرئيسيين في هذه اللعبة:

- &#x202b;  **تطبيق الClient**: وهو برنامج "World of Warcraft" الفعلي الذي يثبته كل لاعب على جهاز الكمبيوتر الخاص به من أجل الوصول إلى اللعبة

- &#x202b;  **تطبيق السيرفر **: وهو البرنامج الذي يعمل على أجهزة السيرفر.

&#x202b; العملية بسيطة للغاية: جميع الClients (اللاعبين) يتصلون بسيرفر من أجل التفاعل مع بعضهم البعض. يعرف الClient عنوان السيرفر، لأنه مخزّن في ملف "**realmlist.wtf**" الشهير (لهذا السبب عليك تعديل هذا الملف من أجل التبديل إلى سيرفر آخر).

![Client-server](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/client-server.png)


### &#x202b;  كيف تعمل السيرفرات الخاصة لWoW

&#x202b; عند اللعب على خوادم خاصة، فإن المبدأ هو نفسه تمامًا. يكمن الاختلاف في البرنامج الذي تستخدمه.

![Wow-Defias](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/wow-defias.jpg)

&#x202b; **Client**: يمكن للجميع الوصول إلى الClient الخاص ب World of Warcraft الأصلي. يمكنك الحصول عليه بسهولة عن طريق شرائه أو تنزيله عبر الإنترنت. هذا البرنامج هو بالضبط البرنامج الذي ستستخدمه للعب على السيرفر الرسمي. من الواضح أن السيرفرات الخاصة المختلفة لديها إصدارات مختلفة، لكنها تشير دائمًا إلى الClient الأصلي. تحتاج فقط إلى إجراء تغيير بسيط على ملف "realmlist.wtf"، واستبدال عنوان السيرفر الرسمي بعنوان السيرفر خاص. هذا كل شيء.

&#x202b; **السيرفر**: هذا مختلف تمامًا. لا أحد خارج Blizzard لديه حق الوصول إلى البرنامج الأصلي الذي يدير سيرفرات World of Warcraft الرسمية. لذا فإن هذه التطبيقات مختلفة تمامًا عن التطبيقات الأصلية.

### الهندسة العكسية

![Reverse engineering](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/reverse-engineering.jpeg)

 كل البرامج التي تعمل على السيرفرات الخاصة تم إنشاؤها من خلال تقنية "الهندسة العكسية"، والتي تعني بكلمات بسيطة "أحاول كتابة برنامج يحاكي سلوك برنامج آخر، دون النظر إلى الكود الأصلي".

السؤال الآن هو: من قام بتنفيذ هذا البرنامج ومتى حدث ذلك؟


#### نبذة عن حقوق الطبع والنشر

&#x202b; *المواد المحمية بحقوق الطبع والنشر بالكامل (الصور، الأصوات، النماذج ثلاثية الأبعاد، الشعارات، إلخ...) موجودة داخل الClient الخاص باللعبة.
يحتوي تطبيق السيرفر على أرقام ونصوص فقط. لذلك، فهو قانوني تمامًا إذا كنت تستخدمه لأغراض تعليمية.*

## &#x202b; تطبيقات سيرفر WoW غير الرسمية

&#x202b; من الذي ينشئ تطبيقات البرامج التي تدير السيرفرات الخاصة لWoW (التي يُطلق عليها عادةً "المحاكيات"؟) وكيف يفعلون ذلك؟



### التعقيد

![Complex](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/complex.jpg)

&#x202b; لا تحتاج إلى أن تكون خبيرًا لفهم أن كتابة تطبيق سيرفر للعبة MMORPG ذات نطاق كبير مثل World of Warcraft ليس بالأمر السهل بالتأكيد.

&#x202b; Blizzard شركة كبيرة تضم آلاف الموظفين. من المؤكد أن كتابة برنامج "يحاكي" تشغيل تطبيق السيرفر الخاص بهم ليس بالأمر الهيّن أو الممكن لشخص واحد (أو مجموعة صغيرة من المبرمجين).

&#x202b; والأمر لا يتعلق فقط بالتعقيد. لنفكر في مهام تافهة جدًا ولكنها متكررة، مثل إضافة كل الNPCs في العالم، بما في ذلك كل عنصر من غنائمهم مع نسبة الحظ الخاصة به، إلخ. مهمة رائعة في الأساس. ناهيك عن كل المهام المعقدة جدًا التي تتطلب ساعات من الدراسة والاختبار، مثل آليات الSpell وآليات الBoss، إلخ.

وباختصار .... لا يمكن حتى لأفضل مبرمج في العالم أن يقوم بكل هذا العمل بمفرده.

&#x202b; ومع ذلك هناك سيرفرات خاصة، والبرامج التي تجعلها تعمل. وبعض السيرفرات الخاصة قادرة الآن على تقديم جودة لعبة ليست بعيدة عن الجودة الأصلية (أشير هنا بشكل أساسي إلى الexpansions القديمة).


كيف يمكن ذلك؟

### &#x202b; MaNGOS ونموذج تطوير المصادر المفتوحة

> &#x202b; إذا كان لديك تفاحة ولديّ تفاحة وتبادلنا هذه التفاحات، فسيظل لدى كل منا تفاحة واحدة. ولكن إذا كانت لديك فكرة ولديّ فكرة وتبادلنا هذه الأفكار، فسيكون لدى كل منا فكرتين. (George Bernard Shaw)

فقط لتبسيط الأمر: البرنامج المفتوح المصدر هو برنامج تكون أكواده البرمجية متاحة للعامة.

في سياق السيرفرات الخاصة، يلعب البرنامج المفتوح المصدر دورًا أساسيًا.

&#x202b; قد يتذكر بعض اللاعبين القدامى أن جودة اللعبة على السيرفرات الخاصة كانت سيئة للغاية. لم يكن هناك شيء يعمل تقريبًا.
على سبيل المثال، إذا كنت Rogue وكنت متخفي فيمكن استهدافك من قبل أي شخص كتب `/target Yourname`. خمن أي class قمت باختياره لشخصيتي الأولى ...

![Mangos-logo](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/mangos-logo.gif)

&#x202b; كانت الثورة الحقيقية هي [MaNGOS](https://it.wikipedia.org/wiki/MaNGOS)، وهو مشروع مفتوح المصدر تم إنشاؤه في عام 2005، وكان الغرض منه توفير تطبيق سيرفر للعبة World of Warcraft.
كان الخبر الرائع في MaNGOS، بالإضافة إلى قوته أنه كتطبيق مفتوح المصدر، كانت أكواده البرمجية متاحة للعامة تمامًا، ويمكن لأي مستخدم من جميع أنحاء العالم دراستها وتقديم مساهمته الخاصة (سواء من حيث إضافة أو إصلاح آليات اللعبة، أو من حيث الإبلاغ عن الأخطاء).

&#x202b; وبهذه الطريقة فقط، وبفضل مساهمة العديد من المتطوعين من جنسيات مختلفة، أصبح من الممكن تطوير تطبيق سيرفر قادر على محاكاة لعبة World of Warcraft بجودة لعب أعلى.

&#x202b; في عام 2009، وُلد مشروع مهم آخر [TrinityCore](https://www.trinitycore.org/)، بالاعتماد على نظام MaNGOS.

![Trinitycore-logo](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/trinitycore-logo.png)

&#x202b; حتى الآن، تعمل الغالبية العظمى من السيرفرات الخاصة على التطبيقات المستندة إلى MaNGOS/TrinityCore.

&#x202b; على مر السنين، وُلدت [مشاريع مختلفة](http://mangosrumors.org/best-wow-emulator-2020/)، وكانت تستند إلى كود MaNGOS/TrinityCore، والتي تختلف بشكل أساسي وفقًا لإصدار WoW المدعوم.
&#x202b; على سبيل المثال [AzerothCore](https://www.azerothcore.org/) لـ 3.3.5، [OregonCore](https://github.com/OregonCore) لـ 2.4.3، [SkyFire](https://www.projectskyfire.org/) لـ 5.4.8، [CMaNGOS](https://cmangos.net/) لـ Classic/TBC/WOTLK، وغيرها الكثير ... كلها تعتمد على MaNGOS و/أو TrinityCore.

![Azerothcore-authserver](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/azerothcore-authserver.png)

### الملخص

&#x202b; لذا فإن السيرفرات الخاصة لم تصل إلى هذه الجودة إلا بفضل العديد من المساهمين الذين قاموا بتنفيذ المزيد والمزيد من مميزات اللعبة على مر السنين (من 2005 إلى يومنا هذا).

&#x202b; يمكن لأي مستخدم كمبيوتر متمرس اليوم تثبيت سيرفر WoW بسهولة، بدون أن يكون مبرمجًا.

## السيرفرات مفتوحة المصدر مقابل السيرفرات الخاصة

![Alice-and-bob](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/alice-and-bob.jpg)

### سيناريو افتراضي

لنفترض أن لدى كل من أليس وبوب سيرفر خاص لكل منهما، ولنفترض أنهما يستخدمان نفس الإصدار من اللعبة.
&#x202b; يريد كل من أليس وبوب إصدار محتوى جديد للاعبيهما، والذي تم إغلاقه حتى الآن لأن الBosses "أ" و"ب" و"ج" و"د" بهم أخطاء كثيرة.

- &#x202b;   أليس مطورة جيدة جدًا ويمكنها إصلاح كلا  "أ" و "ب"
- &#x202b;  لا يزال بوب مبتدئًا ويقوم فقط بإصلاح ''C"

### في عالم مثالي

&#x202b; تعمل أليس وبوب معًا ويتبادلان الإصلاحات الخاصة بهما. ونتيجة لذلك، سيكون لدى كلا سيرفراتهم Bosses تم إصلاحها بشكل مثالي "أ" و"ب" و"ج".

&#x202b; بالإضافة إلى ذلك، سيتعاون أليس وبوب من أجل العمل على "D" أيضًا.

### في العالم الواقع

&#x202b; أليس وبوب خصمان ولذلك يخوضان حرباً ضد بعضهما البعض. في سيرفر أليس، لا يعمل سوى الBoss "أ" و"ب". بينما في سيرفر بوب يعمل فقط "C".
&#x202b; ينتقل بعض اللاعبين من سيرفر بوب إلى سيرفر أليس. يغلق سيرفر بوب بعد فترة من الوقت. بعض لاعبي سيرفر أليس يتوقفون عن اللعب لأنهم سئموا من القيام بـ "أ" و"ب" فقط لأن "ج" و"د" لا يعملان.

&#x202b; ونتيجة لذلك، أصبح اللاعبون على كلا السيرفرين أقل سعادة مما كانوا عليه في السيناريو السابق. حققت أليس أموالاً من تبرعات اللاعبين أكثر مما حققه بوب.

### &#x202b; ترخيص محاكيات WoW

&#x202b; في الواقع، يتم إصدار كود MaNGOS/TrinityCore (والمشاريع المشتقة منها) بموجب [رخصة GNU GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License).

&#x202b; وبكلمات بسيطة، تنص هذه الرخصة على ما يلي: استخدم الكود لفعل ما تريد، دون دفع أي شيء، طالما أن أي تعديل على الكود الأصلي يتم إصداره أيضًا بموجب نفس الرخصة.
&#x202b; بشكل أساسي، يتطلب ترخيص هذه المشاريع من الذين يستخدمونها أن ينشروا أي تغييرات تطرأ عليها للعامة.


&#x202b; بالطبع، معظم السيرفرات الخاصة تستخدم هذه الرخصة كـ **ورقة مرحاض**. وبخلاف ذلك، لا ينبغي أن يكون هناك سيرفر خاص "أفضل إصلاحاً" من غيره.

![Toilet-paper](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/toilet-paper.jpg)

## الأكاذيب حول السيرفرات الخاصة

&#x202b; فيما يلي قائمة بالأكاذيب التي يستمر مديرو العديد من خوادم WoW الخاصة في ترديدها على لاعبيهم:


### "نحن قمنا ببرمجة هذا المحاكي"

&#x202b; أخبار كاذبة. لا يهم عدد التغييرات "التي أجريتها". ومع ذلك، لقد بدأت بمشروع قائم على MaNGOS.

&#x202b; ربما تكون قد أجريت بعض التحسينات، ولكن معظم الكود لا يزال يخص MaNGOS/TrinityCore.

&#x202b; ربما تكون جيدًا حقًا وأعدت كتابة معظم الكود على مر السنين. ومع ذلك، فقد بدأت من MaNGOS. بدونها، لم تكن لتتمكن في اليوم الأول من تشغيل ميزة تسجيل الدخول.

### &#x202b;  "لقد قمنا بإصلاح X"

&#x202b; في معظم الحالات، لم يقم أي منهم بإصلاح أي شيء بالفعل.
&#x202b; لقد قاموا فقط بتحميل الإصلاحات التي تأتي من مجتمع المصادر المفتوحة وطبّقوها على السيرفرات الخاصة بهم.
&#x202b; ومع ذلك يأخذون كل الفضل.

### &#x202b; "نحن (حقًا) أصلحنا X"

&#x202b; بعض السيرفرات الخاصة تقوم بالفعل بإصلاح الأشياء من تلقاء نفسها. وغالبًا ما يكون لديهم فرق تطوير مخصصة يتم الدفع لها من الأموال التي تأتي من تبرعات اللاعبين.

&#x202b; لا يشارك معظمهم هذه الإصلاحات مع مجتمع التطوير.

&#x202b; حسنًا، يطلب منك المجتمع الذي قدم (مجانًا) البرنامج الذي تستخدمه لتشغيل السيرفر الخاص بك (مجانًا) أن تشاركه معهم، لكنك لا تزال تحتفظ به بشكل خاص. لذا أكرهك على أي حال.

![Pinocchio](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/pinocchio.jpeg)

## &#x202b; "مبررات" السيرفرات الخاصة


###  &#x202b; "أحتفظ بها بشكل خاص لجعل السيرفر الخاص بي مكاناً مميزاً وأفضل من غيره"

&#x202b; حسنًا أيها البطل. حاول أن تفكر في هذا: إذا كان جميع المطورين يفعلون مثلك، فلن تكون أنت ولا السيرفر الخاص بك موجودًا.

&#x202b; لماذا؟ ببساطة لأنه لن يكون هناك أي من MaNGOS (ولا TrinityCore، ولا AzerothCore، إلخ...).
&#x202b; هذه المشاريع موجودة بفضل المطورين الذين شاركوا أكوادهم البرمجية على عكسك.

&#x202b; إذا أبقى جميع المطورين أكوادهم سرية، فلن يكون لدينا محاكي WoW لائق ولن تتمكن من فتح السيرفر الخاص بك، لأنه لن يكون هناك أي برنامج متاح.


### &#x202b; "إذا شاركت إصلاحاتي، فسوف يسرقها المنافسون"

&#x202b; لا يوجد شيء "ليسرقوه". لا يمكنهم "سرقة" هذا الكود لأنه لا "ينتمي" إليك. لا، ولا حتى لو كنت قد كتبته بالفعل.

&#x202b; إن فلسفة المصدر المفتوح واضحة: يمكنك استخدام هذا الكود مجانًا، بشرط أن يكون أي تعديل عليه يجب أن يكون علنيًا.

&#x202b; ألا توافقني الرأي؟ حسنًا. إذن لا تستخدم أي كود مفتوح المصدر واكتب محاكي WoW الخاص بك من الصفر.

## كيف يؤثر ذلك على اللاعبين

![Wow-Dranei-crying](https://raw.githubusercontent.com/FrancescoBorzi/why-I-hate-wow-private-servers/master/img/wow-dranei-crying.jpg)

&#x202b; أتفهم تمامًا أن هذه القصة بأكملها حول الأخلاقيات والتراخيص لا تهم كثيرًا بالنسبة للاعبين العاديين في World of Warcraft.
&#x202b; يرغب اللاعبون فقط في اللعب على سيرفر مستقر وثابت، ولا يهتمون كثيرًا ما إذا كان هذا السيرفر يتعاون مع المصدر المفتوح أم لا.

&#x202b; ولكن... حاول للحظة أن ترى الأمر من منظور آخر.

&#x202b; لا يهتم مطورو المشاريع مفتوحة المصدر (MaNGOS و TrinityCore و AzerothCore وغيرها...) بشكل أساسي بما تفعله السيرفرات الخاصة.
&#x202b; بالطبع، كمطور، يزعجك كمطور أن ترى بعض مسؤولي السيرفرات العشوائية يأخذون الفضل مقابل عملك، ولكن في النهاية لا يغير ذلك من حياتك.
&#x202b; العديد من مطوري البرامج مفتوحة المصدر يفعلون ذلك فقط من أجل المتعة والأغراض التعليمية.

&#x202b; في الواقع، إذا تعاونت جميع السيرفرات الخاصة مع المصادر المفتوحة، فإن حياة اللاعبين ستتغير تماماً!
&#x202b; كما تعلم، في هذه الحالة، سيوفر كل سيرفر في هذه الحالة تجربة لعب أفضل بكثير لأي توسع. يمكن تطبيق مثال أليس وبوب المذكور من قبل على هذه الحالة أيضًا.

&#x202b; ومع ذلك، فإن الواقع هو أن هناك العديد من السيرفرات الخاصة في جميع أنحاء العالم، كل واحد منهم يعمل دائمًا على نفس الأشياء، ويتسابقون للقيام بها بشكل أسرع وأفضل.
&#x202b; إذا تعاونوا مع بعضهم البعض بدلاً من ذلك، فإنهم سيتجنبون القيام بأعمال غير ضرورية وسيكون لديهم المزيد من الوقت والقوى العاملة. لذلك سيتمكنون بالتأكيد من تحقيق المزيد من الإنجازات.

&#x202b; *ملاحظة: جودة (والمنافسة بين) السيرفرات الخاصة لا يجب أن تكون (فقط) حول الإصلاح، ولكن أيضًا حول عوامل أخرى مثل مهارات مديريها في إدارتها. تلعب جودة المجتمع أيضًا دورًا أساسيًا، تمامًا كما يحدث في خوادم Blizzard (التي تتساوى جميعها من منظور تقني).*

&#x202b; إذا تم إغلاق سيرفر خاص، ولم يقم مطوروه بمشاركة عملهم، فسيضيع هذا العمل إلى الأبد.

## كشف الأكاذيب

### القائمة الرسمية للمؤلفين

&#x202b; الشيء الأكثر إثارة للاهتمام هو أن جميع المشاريع القائمة على MaNGOS علنية تمامًا، لذلك من الممكن التحقق بدقة من المساهمين فيها.

&#x202b; ونتيجةً لذلك، فإن جميع قوائم المساهمين في هذه المشاريع علنية تمامًا ويمكن لأي شخص التحقق من الذي أصلح ماذا بالفعل.

&#x202b; على سبيل المثال:

- &#x202b;  القائمة الرسمية للمساهمين في https://github.com/cmangos/mangos-wotlk/blob/master/AUTHORS.md :MaNGOS
- &#x202b; القائمة الرسمية للمساهمين في https://github.com/TrinityCore/TrinityCore/blob/3.3.5/AUTHORS :TrinityCore 
- &#x202b; القائمة الرسمية للمساهمين في https://github.com/AzerothCore/azerothcore-wotlk/graphs/contributors :AzerothCore 

&#x202b; ملاحظة: يمكنك العثور على كاتب هذه المقالة في كل هذه القوائم

###  قائمة النشر الرسمية

&#x202b; يحتوي أي مشروع مفتوح المصدر (مستضاف بشكل عام على GitHub) على قائمة بالمنشورات التي أنجزها مختلف المطورين. لكل منشور، يوجد كل من المؤلف والتاريخ.

&#x202b; من السهل جدًا التحقق من هذه المعلومات، فقط افتح official repository لأي محاكي. ابحث في جوجل على سبيل المثال عن "TrinityCore github" أو "AzerothCore github" وألقِ نظرة فقط.

&#x202b; سترى من فعل ماذا فعل ماذا. سترى جميع أسطر الكود ومؤلفيها وتعليقات المطورين الآخرين وما إلى ذلك. سترى كل شيء. لا مزيد من الأكاذيب!


##ماذا يمكنني أن أفعل كلاعب؟

&#x202b; نصيحتي هي أن تلعب/تدعم السيرفرات الخاصة التي تتعاون مع المصادر المفتوحة، على الرغم من نوع التوسعة والمحاكي الذي تستخدمه.

&#x202b; أو، على الأقل، تجنب تلك السيرفرات التي تبيع أعمال الآخرين على أنها أعمالهم الخاصة، وتزيل الفضل من المؤلفين الأصليين.

&#x202b;  **جديد:** في عام 2021 تم إطلاق المشروع الجديد [ChromieCraft](https://www.chromiecraft.com/about)، الذي يتميز بخادم مفتوح المصدر بالكامل وتقدمي.

![ChromieCraft logo](https://avatars1.githubusercontent.com/u/68329413?s=400&u=084b35243e0aed1becd6a67fa88717eb8c1674d8&v=4)

### اعرف المزيد عن البرامج المجانية

- https://www.gnu.org/software/software.en.html
- https://www.fsf.org/about/what-is-free-software


## شكراً

&#x202b; شكر خاص ل *Laura Bartiromo*
