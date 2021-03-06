# Alyahmor اليحمور
Arabic flexionnal morphology generator

## Description
The Alyahmor produce a word form from (prefix, lemma, suffix).
I has many fucntionalities:
- Generate word from from given word and affixes
- Generate all word forms by adding verbal or nominal affixes according to word type
- Generate all affixes combination for verbs or nouns.

### Generate a vocalized word form

It joins word with affixes with suitable correction
for example

بال+كتاب +ين => بالكتابين
ب+أبناء+ه => بأبنائه

All this affixations are vocalized


### Generate all word forms

It joins word with affixes with suitable correction
	for example
	```
			كتاب =>[(u'كتَاب', u'كتَاب', u'-كتاب--'),
		
		 (u'كتَابهَا', u'كتَابهَا', u'-كتاب--ها'),
		 (u'كتَابكُمَا', u'كتَابكُمَا', u'-كتاب--كما'),
		  (u'كتَابكَ', u'كتَابكَ', u'-كتاب--ك'),
		 (u'كتَابهُ', u'كتَابهُ', u'-كتاب--ه'),
		 (u'كتَابي', u'كتَابي', u'-كتاب--ي'),
		 (u'كتَابكُنَّ', u'كتَابكُنَّ', u'-كتاب--كن'),
		 (u'كتَابكُمْ', u'كتَابكُمْ', u'-كتاب--كم'),
		 (u'كتَابهُنَّ', u'كتَابهُنَّ', u'-كتاب--هن'),
		 (u'كتَابهُمْ', u'كتَابهُمْ', u'-كتاب--هم'),
		 (u'كتَابهُمَا', u'كتَابهُمَا', u'-كتاب--هما'),
		 (u'كتَابنَا', u'كتَابنَا', u'-كتاب--نا'),
		.....
		```
	
All this affixations are vocalized

### Generate all affixes combination for verbs or nouns.
This program can generate all valid affixes for verbs and nouns

**Nouns**
``` python
NOUN_AFFIX_LIST=
[u'وك-ياتك',
 u'وبال-تين',
 u'وك-ياته',
 u'-وها',
 u'وك-ياتي',
 u'ل-ياتكما',
 u'وك-',
 u'أفك-تهن',
 u'أفك-تهم',
 u'أفب-يهم',
 u'أفب-يهن',
 ....
```

**Verbs**
```python
VERB_AFFIX_LIST=
[u'ي-ونكن',
 u'ي-ونكم',
 u'أولن-ها',
 u'فل-وهما',
 u'-وها',
 u'ولت-ن',
 u'ولي-نها',
 u'-تمه',
 u'أس-',
 u'أفت-ونني',
 u'ول-تمه',
 ....
```

##أصل التسمية

**اليَحْمُور،** وهو الحسن بن المعالي الباقلاني شيخ العربية في زمانه في بغداد من تلامذة أبي البقاء العكبري ت ٦٣٧هـ


**ابن الباقلاني النحوي**

الحسن بن معالي بن مسعود بن الحسين بن الباقلاني، أبو علي النحوي الحلي.
قدم بغداد في صباه، وقرأ بها المذهب والكلام على الشيخ يوسف بن إسماعيل اللامغاني الحنفي، وعلى النصير عبد الله بن حسن الطوسي، وعلي المجير محمود بن المبارك. 

وقرأ الحكمة على المسعودي غلام عمر بن سهلان الساوي صاحب البصائر، والأدب على أبي الحسن بن بانويه، وأبي البقاء العكبري، ومصدق الواسطي، واللغة على القاضي أبي محمد عبد الله بن أحمد بن المأمون وغيره.

ولازم الاشتغال والتحصيل إلى أن برع في هذه العلوم، وصار مشاراً إليه فيها معتمداً على ما يقوله. وسمع من أبي محمد بن المأمون المذكور، ومن مسعود بن علي بن النادر، وعبد الوهاب بن هبة الله ابن أبي حبة، ومن أبي الفرج بن كليب، وآخرين.


وكتب بخطه كثيراً من الأدب واللغة وسائر الفنون، وكان له همةٌ عالية، وحرصٌ شديد؛ وتحصيل الفوائد مع علو سنه، وضعف بصره، وكثرة محفوظه، وصدقه، وثقته، وحسن طريه، وتواضعه، وكرم أخلاقه.

وانتقل آخر عمره إلى مذهب الشافعي، **وانتهت إليه رياسة النحو.** مولده سنة ثمان وستين وخمسمائة، وتوفي سنة سبع وثلاثين وستمائة.
ومن شعره، وقد أمره بعض أصدقائه بطلاق امرأته لما كبرت: من البسيط

- وقائلٍ لي وقد شابت ذوائبها ... وأصبحت وهي مثل العود في النحف
- لم لا تجذ حبال الوصل من نصفٍ ... شمطاء من غير ما حسنٍ ولا ترف
- فقلت هيهات أن أسلو مودتها ... يوماً ولو أشرفت نفسي على التلف
- وأن أخون عجوزاً غير خائنةٍ ... مقيمةً لي على الإتلاف والسرف
