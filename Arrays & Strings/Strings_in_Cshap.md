## Copilot
بالطبع! سأقوم بإعادة تنسيق المعلومات حول السلاسل النصية (Strings) في C# بشكل مشابه للمثال الذي قدمته.
السلاسل النصية (Strings) في C#في لغة C#، السلاسل النصية هي نوع بيانات يُستخدم لتمثيل النصوص. تُخزَّن السلاسل النصية في الذاكرة كنمط من الأحرف المتتابعة، ويتم تمثيلها باستخدام فئة string.
المزايا- سهولة الاستخدام: توفر C# ميثودز متعددة تعمل على تسهيل التعامل مع السلاسل النصية، مما يجعل البرمجة أكثر كفاءة.
- أداء جيد: أداء معالجة السلاسل النصية في C# جيد جدًا، خاصة عند استخدام فئة StringBuilder لمعالجة السلاسل النصية الكبيرة.
- دعمتها اللغة: تقدم C# دعمًا قويًا للسلاسل النصية، مما يسمح بتعزيز تجربة البرمجة.
- الدعم الدولي: تدعم C# السلاسل النصية المتعددة اللغات، مما يجعلها مناسبة للتطبيقات العالمية.
العيوب- غير قابلة للتعديل: السلاسل النصية في C# غير قابلة للتعديل (immutable)، مما يعني أنه عند إجراء تعديل على سلسلة نصية، يتم إنشاء سلسلة جديدة بدلًا من تعديل السلسلة الأصلية.
- استخدام الذاكرة: قد تؤدي العمليات المتكررة على السلاسل النصية (مثل التكرار أو التعديل) إلى استخدام مفرط للذاكرة، لذا يُفضل استخدام StringBuilder في بعض الحالات.
- الأداء في بعض العمليات: عمليات التعديل المتكررة على السلاسل النصية قد تؤدي إلى تدهور في الأداء، لذا يُفضل استخدام أنواع أخرى عند الحاجة إلى تعديلات مكثفة.
ميثودز السلاسل النصية في C#1. Length- الوصف: تُستخدم للحصول على طول السلسلة النصية.
- الاستخدام:

int length = myString.Length;  // returns 13

2. ToLower()- الوصف: تُحول جميع الأحرف إلى حروف صغيرة.
- الاستخدام:

string lowerString = myString.ToLower();  // returns 'hello, world!'

3. ToUpper()- الوصف: تُحول جميع الأحرف إلى حروف كبيرة.
- الاستخدام:

string upperString = myString.ToUpper();  // returns 'HELLO, WORLD!'

4. Trim()- الوصف: تُزيل المسافات البيضاء من البداية والنهاية.
- الاستخدام:

string trimmedString = myString.Trim();  // returns 'Hello, World!'

5. Replace(oldValue, newValue)- الوصف: تستبدل جزءًا من السلسلة النصية بنص آخر.
- الاستخدام:

string replacedString = myString.Replace("World", "Everyone");  // returns 'Hello, Everyone!'

6. Split(separator)- الوصف: تُقسم السلسلة النصية إلى مصفوفة من السلاسل باستخدام الفاصل المحدد.
- الاستخدام:

string[] words = myString.Split(',');  // returns ['Hello', ' World!']

7. Join(separator, array)- الوصف: تُدمج عناصر مصفوفة من السلاسل النصية باستخدام السلسلة النصية كفاصل.
- الاستخدام:

string joinedString = string.Join(", ", new string[] { "Hello", "World!" });  // returns 'Hello, World!'

8. IndexOf(substring)- الوصف: تُرجع فهرس بداية الجزء المطلوب، أو -1 إذا لم يتم العثور عليه.
- الاستخدام:

int index = myString.IndexOf("World");  // returns 7

9. Count(substring)- الوصف: لا يوجد ميثود مباشر في C# لحساب عدد مرات ظهور جزء محدد، لكن يمكن استخدام Split وLength لتحقيق ذلك.
- الاستخدام:

int count = myString.Split('o').Length - 1;  // returns 2

10. StartsWith(prefix)- الوصف: تتحقق مما إذا كانت السلسلة النصية تبدأ بالجزء المحدد.
- الاستخدام:

bool startsWithHello = myString.StartsWith("Hello");  // returns true

11. EndsWith(suffix)- الوصف: تتحقق مما إذا كانت السلسلة النصية تنتهي بالجزء المحدد.
- الاستخدام:

bool endsWithExclamation = myString.EndsWith("!");  // returns true

12. Capitalize()- الوصف: لا توجد دالة مباشرة، لكن يمكنك تحقيق ذلك باستخدام ToUpper() مع الفهرس.
- الاستخدام:

string capitalizedString = char.ToUpper(myString[0]) + myString.Substring(1);  // returns 'Hello, World!'

13. ToTitleCase()- الوصف: لتحويل الحرف الأول من كل كلمة إلى حرف كبير، تحتاج إلى استخدام TextInfo من System.Globalization.
- الاستخدام:

var textInfo = new System.Globalization.CultureInfo("en-US", false).TextInfo;
string titleCaseString = textInfo.ToTitleCase(myString.ToLower());  // returns 'Hello, World!'

14. IsNullOrEmpty()- الوصف: تتحقق مما إذا كانت السلسلة فارغة أو تساوي null.
- الاستخدام:

bool isNullOrEmpty = string.IsNullOrEmpty(myString);  // returns false

15. Contains(substring)- الوصف: تتحقق مما إذا كانت السلسلة تحتوي على جزء محدد.
- الاستخدام:

bool containsWorld = myString.Contains("World");  // returns true

سأقوم الآن بإنشاء الملف المطلوب.
