# SPZ_CP_Rud_VI_KI_306

## ------------------------------Feature 1------------------------------

### Опис: створити функціонал автоматичного створення резервних копій з вказаної "трек" папки у папку "призначення"

### Функція:

### 1. CreateTrackFolder()

Що робить: за вказаною "трек" папкою буде автоматично копіювати файли у папку "призначення"

## ------------------------------Feature 2------------------------------
### Опис: створити автоматичне створення резервних копій деяких важливих системних файлів, драйверів у певний період часу 

### Функції:

### 1. SelectDirectory()

Що робить: за вказаним користувачем шляхом генерує каталог папок "ReserveCatalog" де зберігатимуться резервні копії у відповідних папках, таких як "Config" та "Drivers"

### 2. SaveManager()

Що робить: працює в фоновому режимі та періодично створює резервні копії

### 3. CopyConfigFiles()

Що робить: копіює деякі папки та файли в котрих налаштована робота операційної системи Windows у папку "Config" в "ReserveCatalog".
Наприклад: файли Registry Hive, pagefile.sys

### 4. CopyDrivers()

Що робить: копіює деякі папки та файли в котрих налаштовані драйвери пристроїв у папку "Drivers" в "ReserveCatalog".
