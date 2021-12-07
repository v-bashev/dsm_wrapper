# dsm_wrapper
DSM врапер генератора для ядра языка poST

# Ссылки
- Ядро языка poST: https://github.com/v-bashev/post_core
- Пример с генераторами в ST и XML: https://github.com/v-bashev/post_to_st

# Как использовать
Склонировать проект (или просто скачать архив), переименовать под имя своего DSM, закинуть в корень проекта jar со своим генератором (jar с st генератором можно удалить), исправить 4 TODO в файлах: build.gradle, AppLauncher и WrappedServer, вызвать `./gradlew jar`, сгенерированный jar с вашим dsm будет лежать в `build/libs`
