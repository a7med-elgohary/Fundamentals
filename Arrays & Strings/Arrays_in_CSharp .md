
# المصفوفات في لغة #C
## مزايا المصفوفات:
1. **التخزين المتتالي**: العناصر تُخزن في الذاكرة بشكل متتالٍ، مما يجعل الوصول إليها سريعًا باستخدام الفهرس.
2. **ثابتة الحجم**: بمجرد إنشاء المصفوفة، لا يمكن تغيير حجمها.
3. **سهولة الوصول**: الوصول إلى العناصر يكون عن طريق الفهرس، مما يجعل العملية سريعة وبسيطة.
4. **أداء عالي**: استخدام المصفوفات يعتبر أكثر كفاءة من الهياكل الأخرى في بعض الحالات بسبب التخزين المتتابع.

## عيوب المصفوفات:
1. **ثابتة الحجم**: لا يمكن زيادة حجم المصفوفة أو تقليله بعد تعريفها، مما قد يحد من مرونتها.
2. **التكرار اليدوي**: لا توفر وسائل مدمجة مثل إضافة أو حذف العناصر بسهولة كما هو الحال في الهياكل الأخرى مثل القوائم (List).
3. **عدم القدرة على تخزين أنواع بيانات مختلطة**: يجب أن تكون جميع العناصر في المصفوفة من نفس النوع.
4. **قد يؤدي استخدام المصفوفات الكبيرة إلى استهلاك الذاكرة**: خاصة إذا كان هناك الكثير من المساحة غير المستخدمة.

> في لغة #C، المصفوفات (Arrays) هي هياكل بيانات تُستخدم لتخزين مجموعة من العناصر ذات النوع نفسه. كل عنصر في المصفوفة يُخزن في مكان متتالٍ من الذاكرة، ويمكن الوصول إليه عن طريق فهرس (Index). يبدأ فهرس المصفوفة دائمًا من الصفر، مما يعني أن العنصر الأول في المصفوفة يمكن الوصول إليه عبر الفهرس 0.

## تعريف المصفوفة:
يمكنك تعريف مصفوفة في #C باستخدام الصيغة التالية:

```csharp
int[] numbers = new int[5];  // مصفوفة تحتوي على 5 عناصر من نوع int
```

في هذا المثال، يتم تعريف مصفوفة تسمى `numbers` تحتوي على 5 عناصر من نوع `int`.

## تهيئة المصفوفة:
يمكن تهيئة المصفوفة بالقيم عند تعريفها:

```csharp
int[] numbers = new int[] { 1, 2, 3, 4, 5 };
```

أو يمكنك استخدام شكل مختصر:

```csharp
int[] numbers = { 1, 2, 3, 4, 5 };
```

## الوصول إلى العناصر:
يمكنك الوصول إلى عنصر معين في المصفوفة باستخدام الفهرس:

```csharp
int firstNumber = numbers[0];  // الحصول على العنصر الأول
numbers[1] = 10;  // تعديل العنصر الثاني
```

## الميثودز (Methods) الخاصة بالمصفوفات:
في C#، توجد العديد من الميثودز التي تسهل العمل مع المصفوفات، بعضها مدمج في فئة `Array` وبعضها متوفر من خلال مكتبة `System.Linq`.

### 1. `Array.Sort()` - ترتيب العناصر:
يمكنك استخدام هذا الميثود لترتيب العناصر في المصفوفة تصاعدياً:

```csharp
int[] numbers = { 5, 3, 8, 1, 2 };
Array.Sort(numbers);

foreach (int number in numbers)
{
    Console.WriteLine(number);  // 1, 2, 3, 5, 8
}
```

### 2. `Array.Reverse()` - عكس ترتيب العناصر:
لعكس ترتيب العناصر في المصفوفة:

```csharp
Array.Reverse(numbers);

foreach (int number in numbers)
{
    Console.WriteLine(number);  // 8, 5, 3, 2, 1
}
```

### 3. `Array.IndexOf()` - البحث عن عنصر:
يمكنك استخدام هذا الميثود للبحث عن موقع عنصر معين في المصفوفة:

```csharp
int index = Array.IndexOf(numbers, 3);
Console.WriteLine(index);  // 2 (موقع العنصر 3)
```

### 4. `Array.Resize()` - تغيير حجم المصفوفة:
لا يمكن تغيير حجم المصفوفة بشكل مباشر، ولكن يمكن استخدام `Array.Resize` لإنشاء مصفوفة جديدة ذات حجم مختلف:

```csharp
Array.Resize(ref numbers, 10);  // تغيير حجم المصفوفة إلى 10
numbers[5] = 7;  // إضافة عنصر جديد بعد تغيير الحجم
```

### 5. `Array.Clear()` - مسح العناصر:
يُستخدم هذا الميثود لتفريغ العناصر في المصفوفة (أي إعادة القيم إلى القيمة الافتراضية):

```csharp
Array.Clear(numbers, 0, numbers.Length);  // تفريغ جميع العناصر
```

### 6. `Array.Exists()` - التحقق من وجود عنصر:
يمكن استخدام هذا الميثود للتحقق مما إذا كان عنصر معين موجودًا في المصفوفة:

```csharp
bool exists = Array.Exists(numbers, element => element == 3);
Console.WriteLine(exists);  // True إذا كان العنصر 3 موجودًا
```

### 7. `Array.Find()` - العثور على أول عنصر يطابق شرطًا:
يمكنك البحث عن أول عنصر يحقق شرطًا باستخدام `Array.Find`:

```csharp
int result = Array.Find(numbers, element => element > 3);
Console.WriteLine(result);  // أول عنصر أكبر من 3 (5)
```

### 8. `Array.FindAll()` - العثور على جميع العناصر التي تطابق شرطًا:
يمكنك استخدام هذا الميثود للعثور على جميع العناصر التي تحقق شرطًا معينًا:

```csharp
int[] results = Array.FindAll(numbers, element => element > 3);

foreach (int number in results)
{
    Console.WriteLine(number);  // 5, 8
}
```

## ملاحظة:
إذا كنت بحاجة إلى هياكل بيانات أكثر مرونة (تغيير الحجم بسهولة، إضافة أو حذف العناصر)، يمكنك استخدام `List<T>` من مكتبة `System.Collections.Generic`، والتي تقدم المزيد من المرونة مقارنة بالمصفوفات الثابتة.

