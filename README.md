Первое приложение в Android Studio.
Здесь реализован вывод строки "Привет, пользователь" через использование "строковых ресурсов".
В файле res/values/strings.xml добавлен строковый ресурс:
```xml
<resources>
    <string name="app_name">My Application</string>
    <string name="hello_user">Привет, пользователь!</string>
</resources>
```
а в файле res/layout/activity_main.xml макета изменена строка на наш строковый ресурс hello_user
```xml
android:text="@string/hello_user"
```
![image](https://github.com/user-attachments/assets/e779c4cb-aab9-4653-90ee-e39e18e35839)
