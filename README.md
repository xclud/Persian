# persian
[![pub package](https://img.shields.io/pub/v/persian.svg)](https://pub.dartlang.org/packages/persian)

Implements helper functions/extensions for Persian language/culture. Includes number replacement methods for String class and PersianDate class.

This package is a Dart package, which can be used in both Flutter and Dart projects.

## Getting Started

**Import the package**

```dart
import 'package:persian/persian.dart';
```

**Use the extension methods**
```dart
String myText = '123456789';
String myPersianText = myText.withPersianNumbers(); //Will be ۱۲۳۴۵۶۷۸۹
```

```dart
DateTime myDate = DateTime.now();
PersianDate myPersianDate = myDate.toPersian(); //Will be 1398/10/19
```

```dart
int number = 123456789;
String myPersianNumber = number.toPersianString(); //Will be صد و بیست و سه میلیون و چهارصد و پنجاه و شش هزار و هفتصد و هشتاد و نه
```