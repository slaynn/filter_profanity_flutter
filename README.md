This project is a fork from https://github.com/sergiyvergun/filter_profanity in order to use in our apps and to be able to enrich the dictionnaries for us.

# filter_profanity_flutter

# 🤬

##### Dart package to recognize if provided string contains offensive words.

🌐 Supported languages:

- Arabic
- Chinese
- Czech
- Danish
- Dutch
- English
- Filipino
- French
- Frisian
- German
- Hindi
- Hungarian
- Italian
- Japanese
- Korean
- Norwegian
- Oromo
- Persian
- Polish
- Portuguese
- Russian
- Spanish
- Swedish
- Thai
- Turkish
- Ukrainian

### Usage

---

✅ Import package

```dart
import 'package:filter_profanity_flutter/filter_profanity_flutter.dart';
```

🤬 Check if text has offensive words

```dart
hasProfanity('putin') // returns true
hasProfanity('Hello') // returns false
```

🇬🇧 Set language

```dart
hasProfanity('putin', offensiveWords: englishOffensiveWords) // returns true
```

🇺🇦 🇬🇧 Set languages

```dart
hasProfanity('putin', offensiveWords: ukrainianOffensiveWords +  englishOffensiveWords) // returns true
```

### MIT License

---

    Copyright (c) 2023 Koojira Studio

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
