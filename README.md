 Chukhlomina-Ekaterina-Nikolaevna
# Руководство по установке и настройке AndroidStudio
## 1. AndroidStudio
*Android Studio — интегрированная среда разработки (IDE) для работы с платформой Android*
1. скачать [установщик AndroidStudio](https://developer.android.com/studio?hl=ru) (Develop → Download → ***android-studio-2024.2.1.11-windows.exe***)
2. запустить установщик AndroidStudio ***android-studio-2024.2.1.11-windows.exe***
3. запустить приложение AndroidStudio
## 2. SDK Flutter, Dart
*SDK (англ. software development kit — комплект для разработки программного обеспечения) — набор инструментов для разработки программного обеспечения, объединённый в одном пакете. Для работы потребуется две SDK: Flutter(платформа), Dart (язык).*
1. установить плагины Flutter и Dart в AndroidStudio:
    - settings
    - plugins
    - Flatter/Dart
    - install
    - перезапустить IDE (restart)
2. настроить пути к SDK  
    -скачать [Flutter SDK](https://docs.flutter.dev/release/archive)  
    -скачать [Dart SDK](https://dart.dev/get-dart)  
    -указать в New Flutter Project во вкладках Flutter и Dart пути до cкачанных SDK ***..//flutter_windows_3.19.0-stable.zip***,  ***..//Git-2.47.0.2-64-bit.exe***
## 3. Flutter проект
1. Создать проект Flutter (New → NewProject → Flutter → Create)
2. Запустить проект Flutter (Select device → run)
:blush:
