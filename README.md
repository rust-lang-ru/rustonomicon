% Растономикон

Перевод "Rustonomicon"

> Растономикон - это игра слов Rust и Некрономикон - книга, которой обладал 
каждый алхимик в средние века, ее название дословно можно перевести как 
 "Воплощение закона мертвых"

# Оригинал

https://github.com/rust-lang/rust/tree/master/src/doc/nomicon

# Статус

Книга в процессе перевода. В данный момент она не публикуется в виде
веб-страниц, но её можно читать прямо на GitHub (с определёнными неудобствами).
Вот [содержание][summary], и оттуда можно переходить на все остальные разделы.

[summary]: https://github.com/mkpankov/rustonomicon/blob/master/src/SUMMARY.md

# Темное искусство продвинутого и небезопасного программирования на Rust

Внимание: Это сырой документ, поэтому может содержать серьезные ошибки.

> Вместо писания программ, что было моей мечтой, мной овладела тоска и 
невыразимое одиночество; и наконец я увидел страшную правду, в сторону которой 
остальные боялись даже дышать — непроизносимая тайна тайн открылась мне: этот 
язык камня и режущих звуков не способен сохранить в себе черт старого языка как 
Лондон старого Лондона, а Париж старого Парижа, и что на самом деле он довольно 
небезопасный, а его   распростертые внутренности дурно набальзамированы и 
заселены странными существами, в  действительности не имеющими ничего общего с 
тем, как все выглядит на этапе компиляции.

Эта книга зарывается в ужасающие подробности, которые нужно понять для правильного 
написания небезопасных программ на Rust. В связи с характером проблем, 
все может привести к высвобождению невыразимого ужаса, который разорвет вашу 
душу на миллиард бесконечно малых фрагментов отчаяния.

Хотите иметь долгую и счастливую карьеру программиста на Rust? Закройте и
никогда не вспоминайте, что видели эту книгу. Она вам не нужна. Но если вы
все же захотите написать небезопасный код - или просто покопаться во
внутренностях языка - здесь содержится бесценная информация.

В отличие от [книги][trpl] мы предполагаем, что у вас есть обширные базовые
знания. По крайней мере вы должны быть знакомы с системным программированием и
Rust. Если это не так, то сначала почитайте [книгу][trpl]. Хотя мы не
предполагаем, что вы знаете все вообще, и будем время от времени освежать основы
там, где это нужно. Вы можете пропустить чтение той книги, если хотите; просто
знайте, что мы не будем объяснять все, начиная с основ.

Для ясности, эта книга погрузит вас в глубокие детали. Мы нырнем в безопасность
во время исключительных ситуаций, псевдонимы указателей, модели памяти и даже
теорию типов. Мы будем много рассказывать о различных типах безопасности и
гарантий.

[trpl]: https://github.com/ruRust/rust_book_ru
