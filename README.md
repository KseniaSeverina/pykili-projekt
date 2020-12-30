# Бот-чистописец

[ссылка на слайды](Бот-чистописец.pdf)

__Программа может выполнять две команды:__   
1. Поиск слов-паразитов в предложенном тексте, их замена/удаление 
2. База с синонимами слов

## Подробное описание

__Что должно получиться в итоге?__    
*бот*   
__Что ваша программа принимает как входные данные?__   
*текст/предложение, которые в последствие обрабатываются программой*    
__Какие модули программа будет использовать?__  
*re, telebot, requests, time*  

## Критерий завершенного проекта

Программа работат правильно, если: 
1. бот находит все слова-паразиты, присутствующие в нашем словаре
2. слова-паразиты, имеющие синонимы, выделяются заглавными буквами, а их синонимы выписываются ботом
3. удаленные слова-паразиты выписываются ботом
4. в сообщениях бота с исправленным текстом нет лишних пробелов (напр. перед точками, двойные пробелы, др.)
5. словарь синонимов выдает не более 10 синонимов слова

## Команда проекта

- Седа Хребтовская, БКЛ-194
- Северина Ксения, БКЛ-194

## Таймлайн проекта

__1-2 неделя:__   
~ до 15 марта — создание бота в телеграмм   
~ до 29 марта — программа ищет слова-паразиты в тексте  
__3-4 недели:__   
~ до 6 апреля — составить словарь синонимов для слов-паразитов  
~ до 13 апреля — словарь синонимов для обычных слов    
__5-6 недели:__       
~ до 20 апреля — дополнить словарь синонимов для слов-паразитов    
~ до 27 апреля — доработать код   
## Чего вам не хватает для реализации проекта

- не придумали как убирать омонимию во время поиска слов-паразитов, чтобы не получалось так, что программа будет не понимать в каком контексте слово «типа» — паразит, а в каком — существительное «тип» в форме родительного падежа

## Распределение обязанностей в команде

__Ксения Северина:__
- создание бота
- составить словарь синонимов для слов-паразитов

__Седа Хребтовская:__
- создание бота
- поиск слов-паразитов в тексте 
- словарь синонимов для нормальных слов
