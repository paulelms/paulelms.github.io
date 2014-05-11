---
layout: post
title: Скромное мнение о редакторах текста
description: emacs, vim, sublime text, atom и light table
date: 2014-05-12 00:40
comments: true
categories: emacs vim atom lighttable sublime
---

Я люблю экспериментировать с разными редакторами кода для программистов.
Особый интерес проявляю к так называемым "hackable" редакторам кода (затрудняюсь перевести на русский).
Давно хотел написать такой пост – просто мнение о тех редакторах, на которые обращаю внимание.

## VIM (MacVim)

Автор vim-плагина Airline очень хорошо охарактеризовал его, когда [сваливал на Emacs](http://bling.github.io/blog/2013/10/27/emacs-as-my-leader-vim-survival-guide/).
Он написал примерно так: "VIM лучше в редактировании текста, но Emacs лучше для работы".
Я полностью согласен, команды vim очень хороши в навигации по тексту и его редактировании.
Только для того, чтобы понять эту магию, необходимо хорошо изучить vim.
Но vim тормоз и ограниченный. Если попытаться добавить в него часть функциональности, которую я привык видеть в Emacs,
он начинает дико тормозить. Я пробовал профилировать плагины, тормозят все по немногу.

## Emacs

До сих пор считаю эту среду лучшей для множества задач.
Emacs это не редактор, а интерпретатор лиспа – этим всё сказано.
Если в виме есть работа с метками (закладками) и история изменений в виде дерева,
то для Emacs существует несколько пакетов рыботы с метками и пакет для реализации истории, как в vim.
Всё это реализовано на elisp и программист (у Emacs нет "просто пользователей") может в реальном времени
изменять или полностью переделывать реализацию этих функций.
Emacs – замечательный почтовый и jabber клиент, [лучший органайзер](http://doc.norang.ca/org-mode.html) и т.д.
Но всё это великолепие затмевается высоким порогом вхождения. Если не углубиться в Emacs и сразу свалить на vim,
то так и не познаешь всю эту магию (у большинства заявляющих "пробовал я этот ваш emacs" именно так и было, не распробовал).
Кстати, упомянутый выше автор Airline перешел на Emacs только потому, что для Emacs существует лучшая
реализация эмуляции vim-а. Работают все команды, которые я знаю в vim (а я их знаю много, целенаправленно изучал).
Некоторые считают evil-mode реализацией недостающего текстового редактора в операционной системе Emacs.
Для него даже замечательный плагин surround реализован и работает точно как в vim, а не так, как жалкое подобие в sublime.

## Sublime Text 3

Действительно хороший редактор, но с ним как-то скучно. UI для плагинов у него слишком простой,
но зато это единственный редактор, в котором есть умный авто-комплит и переход к определению для PHP.
Всё благодаря плагину Sublime CodeIntel, код которого был взят из Komodo IDE.
Плагины в саблайме работают в отдельном потоке, именно поэтому линтеры работают в фоне, а не при каждом сохранеии (как vim).
И именно поэтому возможна реализация CodeIntel, который в фоне индексирует код.
Не тормозит с кучей плагинов, красивый, всё работает.

## Atom

Вроде как "hackable editor for the 21st Century", но пока слишком тормозной.
Зато сразу на старте появилась почти вся нужная мне функциональность, потому что
плагины клепают очень быстро, они ведь на javascript (и coffee).
Плагины на javascript это хорошо.
А вот "taking the web native" пока не в полной мере присутствует.
Где live-coding для javascript как в LightTable?
Кстати, они, кажется, хотели его продавать. А как это, если исходники открыты под
либеральной лицензией?

## LightTable

По задумке классный проект, но в данный момент больше напоминает демку.
Из коробки live coding для нескольких языков: html/css, javascript, clojure, clojurescript, python. Можно ещё плагин для ruby доустановить.
Live coding реализован классно – можно видеть результат выполнения кода прямо в редакторе,
а можно подключиться к своему браузеру/repl/приложению и выполнять его там.
Но много чего пока нету и самое печальное – нет документации для разработчиков. Так – пару статей в блогах о внутренностях LT.
Короче говоря нет такой инструкции как у атома – садимся и за пять минут пишем демо-плагин.
Кстати, сделан этот редактор (IDE?) тоже на web-технологиях, поэтому в качестве редактора используется [CodeMirror](http://codemirror.net).
Ощущения от редактирования как-то не очень, хотя тормозит меньше чем atom.
Тем не менее, что бы я там себе не думал, программисты на clojure уже используют его в работе.