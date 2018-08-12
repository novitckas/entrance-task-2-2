# entrance-task-2-2

Посмотреть можно тут https://astatsegre.github.io/entrance-task-2-2/

Модальные окна открываются у первых трех плашек в разделе "Избранные устройства"

Сборка через gulp

Для запуска локально:

1. Установить зависимости
``` npm install ```

2. Собрать спрайт иконок
```gulp svg```

3. Собрать стили
```gulp sass```

4 Можно автоматическую пересборку запустить при изменении
``` gulp sass:watch```

# Над чем можно еще поработать
1. Доступность. Можно поработать над тем, чтобы сайтом было удобно пользоваться через screen readers.
2. Оптимизировать анимацию.
3. Оптимизировать графику. Избавиться от лишней информации в SVG, которая есть в файлах после экспорта из Скетча. Фоновую картинку тоже можно попробовать оптимизировать, например, попробовать WebP.
