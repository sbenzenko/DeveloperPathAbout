﻿# Проект "Путь Разработчика"

Часто у изучающих программирование возникают вопросы, вроде:  
- *«Я изучил основы (прочитал книгу XXX, прошёл курс YYY), что изучать дальше?»*  
- *«Стоит ли читать книгу A (проходить курс B)?»*  
- *«Почему все ругают сайт M?»*

Проект "Путь Разработчика" призван ответить на эти и многие другие вопросы.

## Проект сайта

1. Главная страница представляет собой древовидную интерактивную карту знаний разработчика по примеру, предложенному @MoienTajik
https://github.com/MoienTajik/AspNetCore-Developer-Roadmap/blob/master/ReadMe.md. На карте представлен путь изучения технологии от азов до профессионала. На этом пути темы отмечены разными цветами как:
    - обязательные для изучения, 
    - желательные, 
    - сторонние материалы.

2. Каждая из тем кликабельна и открывает список подтем с кратким описанием и списком источников для изучения. Например:

> Tag helpers [ * ]
> 
> В ASP.NET Core на смену помощникам HTML пришли тег-хелперы (теги-помощники). Они позволяют изменять, дополнять или полностью заменять содержимое НТМL-элементов. <...>
>
> Источники:
> - Книга "Pro ASP.NET Core MVC 2" глава 23 [book][RU][ * ]
> - [Tag Helpers in ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/mvc/views/tag-helpers/intro?view=aspnetcore-3.1) [doc][EN]
> - [ASP.NET Core Tag Helpers and View Components](https://app.pluralsight.com/library/courses/aspdotnet-core-tag-helpers) [video][EN][$]
>
> Код:
> - <ссылка на проект по теме на GitHub или другом ресурсе>

Источники в списке отмечены значками:
- [ * ] - уровень материала (начинающий | средний | продвинутый )
- [book] | [doc] | [video] - тип контента: книга, документация, видео и т.п.
- [RU] | [EN] - язык материала
- [$] - платный контент
- [устар.] - устаревшая информация (например, по .NET Framework).

## Стек Технологий Разработки
- .NET 5 (C# 9)
- ASP.NET Web Api +Blazor
- Entity Framework
- MS SQL (?)
- Хостинг Azure
- Git

## Дальнейшие улучшения
1. Добавление отзывов пользователей в виде оценок качества материалов и комментариев к материалам. Возможность предлагать свои источники.

2. На страницах тем добавить:
    - секцию Q&A (Вопросы и Ответы), где желающие могли бы задавать вопросы по теме,
    - топ вопросов по теме со Stackoverflow (см. API https://api.stackexchange.com/docs/questions).

3. На первом этапе планируется реализовать только путь разработчика ASP.NET. В дальнейшем планируется добавить пути по другим технологиям как в экосистеме .NET, так и в других.

4. Локализация сайта на английском и русском языках. Возможность для пользователей отфильтровать источники по выбранному языку.
