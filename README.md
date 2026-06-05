# AsemAinala — InDrive Автокликер

## 📁 Жоба құрылымы

```
AsemAinala/
├── app/src/main/
│   ├── java/com/asemainala/
│   │   ├── service/
│   │   │   └── AutoClickService.kt     ← Негізгі автокликер логикасы
│   │   ├── ui/
│   │   │   ├── MainActivity.kt         ← Басты экран
│   │   │   └── RouteAdapter.kt         ← Маршруттар тізімі
│   │   ├── model/
│   │   │   └── RouteManager.kt         ← Маршруттарды басқару
│   │   └── utils/
│   │       └── PrefsManager.kt         ← Деректерді сақтау
│   ├── res/
│   │   ├── layout/
│   │   │   ├── activity_main.xml       ← Басты экран UI
│   │   │   └── item_route.xml          ← Маршрут элементі
│   │   ├── xml/
│   │   │   └── accessibility_service_config.xml
│   │   └── values/strings.xml
│   └── AndroidManifest.xml
└── app/build.gradle
```

## 🚀 Android Studio-да орнату

1. **Android Studio** ашыңыз (жоқ болса жүктеңіз: developer.android.com/studio)
2. **File → New → Import Project** таңдаңыз
3. `AsemAinala` папкасын таңдаңыз
4. **Gradle sync** күтіңіз
5. **Build → Build APK** басыңыз

## 📱 Телефонға орнату

1. APK файлын телефонға жіберіңіз
2. **Белгісіз дереккөздерден** орнатуға рұқсат беріңіз
3. Қосымшаны ашыңыз
4. **Параметрлер → Арнайы мүмкіндіктер → AsemAinala → Қосу**
5. Маршруттарды таңдаңыз
6. **ІСКЕ ҚОСУ** батырмасын басыңыз

## ⚙️ Жұмыс принципі

1. **Accessibility Service** InDrive экранын үнемі тексереді
2. Жаңа тапсырыс пайда болғанда — мәтінді оқиды
3. Таңдалған маршруттармен салыстырады
4. Сәйкес болса — автоматты түрде қабылдайды

## ⚠️ Ескерту

- Бұл InDrive-тың ресми қосымшасы емес
- Пайдалану — аккаунт бұғатталу қаупін туғызуы мүмкін
- Тек өз жауапкершілігіңізбен пайдаланыңыз
