Таски с [picoCTF](https://picoctf.com/)
---------------------------------------

Зарегистрируйтесь и залогиньтесь на picoCTF. Ваш логин-пароль к серверу указан на странице [Shell](https://picoctf.com/webshell).
Изначально задачи overflow и ROP от вас скрыты в веб-интерфейсе, но они находятся в приведенных ниже директориях.
Цель: прочесть флаг из файла key, сохранить его и сдать потом в веб-интерфейс picoCTF.

Сначала решите задачи Overflow 1-3, затем переключитесь на ROP 1-3.

Overflow 1: `/problems/stack_overflow_1_3948d17028101c40`

Overflow 2: `/problems/stack_overflow_2_44e63640e033ff2b`

Overflow 3: `/problems/stack_overflow_3_28d8a442fb232c0c`

Overflow 4: `/problems/stack_overflow_4_4834efeff17abdfb`

Overflow 5: `/problems/stack_overflow_5_0353c1a83cb2fa0d`

ROP 1: `/problems/ROP_1_fa6168f4d8eba0eb`

ROP 2: `/problems/ROP_2_20f65dd0bcbe267d`

ROP 3: `/problems/ROP_3_7f3312fe43c46d26`

ROP 4: `/problems/ROP_4_887f7f28b1f64d7e`

[Introduction to ROP](http://codearcana.com/posts/2013/05/28/introduction-to-return-oriented-programming-rop.html) - подробный разбор ROP-заданий с picoCTF


Сложная задача
--------------

[RuCTF Quals 2014: vuln 300](posts) - ELF 32-bit executable. Представьте, что в текущей директории с этим скриптом лежит файл key,
содержимое которого необходимо прочитать.


Материалы
---------

[Д. Юричев. Reverse Engineering для начинающих](http://yurichev.com/writings/RE_for_beginners-ru.pdf)

[А. В. Столяров. Программирование на языке ассемблера NASM для ОС Unix](http://www.stolyarov.info/books/pdf/nasm_unix.pdf)

[Материалы по ассемблеру на acm.mipt.ru](http://acm.mipt.ru/twiki/bin/view/Asm/WebHome)

[Г. Курячий, К. Маслинский. Операционная система Linux](http://docs.altlinux.org/books/altlibrary-linuxintro2.pdf)

[В. Е. Карпов, К. А. Коньков. Основы операционных систем](http://lib.mipt.ru/book/265926/Karpov-VE-Konkov-KA-Osnovy-operatsionnyh-sistem-Kurs-lektsii-Uchebnoe-posobie.djvu)

[Таблица системных вызовов Linux](http://syscalls.kernelgrok.com/)

[Курс Хакердома по реверсу](http://reverse.binchewer.org/2013/)

[Бродкасты Егора Федосеева](http://www.twitch.tv/binchewer/profile/pastBroadcasts)
