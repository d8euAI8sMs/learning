# learning @ d8euAI8sMs

## About d8euAI8sMs

The organization serving as a namespace for personal learning projects.

## About

A number of problems and their solutions along with some infrastructure to automate building and testing.

## Purpose

* All in one place (sources, binary artifacts, pdfs, etc.)
* Automatization (CI as build and test service)
* Reusability of some libs
* Other

The purpose of namely this repository is to collect all the projects together and provide global automatization.

One of these automatizations is pdf report generation. MiKTeX compiler is a comlicated tool to just be installed on AppVeyor builder every time the build starts. But its installation directory (~500MiB being compressed) may be cached. This repository provides a builder with cached MiKTeX installation. (We don't use other CI providers with possibly preinstalled MiKTeX or other `pdflatex`-compatible TeX distribution just because. The goal of getting pdfs from tex sources was achieved. Nothing more.)

## How to Contribute

No way.

## License

All the code is implicitely licensed to [Alexander Vasilevsky (kalaider)](https://github.com/kalaider) under the terms of `Apache 2.0` license starting from the moment of publication without the need of any attribution notice in the source code or somewhere else. There might be some exceptions that are stated explicitely on a per-project (per-source-file or per-source-block) basis. Please contact an author if you need other license for some reasons.

Known exceptions:

* `ml-1-all` is a just-my-code version of https://bitbucket.org/kalaider/machine_learning_fzf. The first commit, [#ed92473](https://github.com/d8euAI8sMs/ml-1-all/commit/ed924739686c443dc4816916cd8a6c9a6be6d1dc), is the squash commit of the previous collective work. The original project is released without any applied license (but the author has a permission to publish and modify the code). So, `Apache 2.0` license is applied to only the changes made by the author that follow the commit above.

## ToC

* `pt-x` _is_ **P**rogramming **T**echnology
* `ss-x` _is_ **S**imulation of **S**ystems
* `ree-x` _is_ **R**adioelectronics and **E**lectronic **E**ngineering
* `sw-x` _is_ **S**cience **W**ork
* `ml-x` _is_ **M**achine **L**earning
* `kr-x` _is_ **K**nowledge **R**epresentation and Reasoning

Other included projects are mostly general-purpose (infrastructure or utilities).

## Getting the Source Code

Use the following command to clone any repository of the organization:

```git
git clone --recurse-submodules https://github.com/d8euAI8sMs/<repository_name>
```

E.g. to clone this repository, use

```git
git clone --recurse-submodules https://github.com/d8euAI8sMs/learning
```

Note that most of the repositories contains submodules (and possibly LFS-managed files) so plain `Download` button might not work as expected. `git clone` is a preferred way.

## Getting Artifacts

pdf reports for all the projects (where applicable) can be found here: [![Build status](https://ci.appveyor.com/api/projects/status/1n2vfw3i1l7mp23x?svg=true)](https://ci.appveyor.com/project/kalaider/learning)

exe, dll, etc. can be found here:

```
https://ci.appveyor.com/project/kalaider/<project_name>
```

where `<project_name>` is a name of the desired project. E.g. https://ci.appveyor.com/project/kalaider/ss-6-heat, etc.

---

# learning @ d8euAI8sMs

## Об организации d8euAI8sMs

Организация служит пространством имен для персональных обучающих проектов.

## О проекте

Набор задач и их решений, а также инфраструктура для автоматизированного процесса сборки и тестирования.

## Зачем

* Все в одном месте (исходники, бинарные артифакты, pdf и т.д.)
* Автоматизация (CI как сервис сборки и тестирования)
* Обеспечение переиспользуемости некоторых библиотек
* И т.д.

Конкретно этот репозиторий служит для глобальной автоматизации всех проектов.

Одна из таких автоматизаций -- автоматическая сборка pdf-отчетов. MiKTeX довольно тяжеловесен, чтобы просто ставить его на AppVeyor CI при каждой сборке. Но директория его устоновки (~500MiB в сжатом виде) может быть закэширована. Данный репозиторий служит конфигурацией сборщика с закэшированным предустановленным MiKTeX. (Другие CI-провайдеры с, возможно, предустановленным MiKTeX или другим `pdflatex`-совместимым дистрибутивом TeX не используются просто потому что. Цель получения pdf из исходников tex достигнута. Большего и не нужно.)

## Как внести свой вклад

Никак.

## Лицензия

Весь код неявно обретает лицензию `Apache 2.0` на имя [Александра Василевского (kalaider)](https://github.com/kalaider) с момента его публикации без необходимости дополнительных отсылок и указаний в исходном коде или где-либо еще. Могут быть исключения, о которых сообщается явно для конкретных проектов (исходных файлов, участков исходного кода). Обратитесь к автору, если Вам по какой-то причине требуется иная лицензия.

Известные исключения:

* `ml-1-all` -- только-мой-код, отзеркаленный из оригинального репозитория https://bitbucket.org/kalaider/machine_learning_fzf. Первый коммит, [#ed92473](https://github.com/d8euAI8sMs/ml-1-all/commit/ed924739686c443dc4816916cd8a6c9a6be6d1dc), -- один большой коммит ранее коллективной работы. Оригинальный проект не имеет какой-либо указанной лицензии (но автор имеет разрешение публиковать и изменять код). Так что лицензия `Apache 2.0` применяется только к последующим изменениям, сделанным автором поверх указанного коммита.

## Содержание

* `pt-x` -- Технология программирования
* `ss-x` -- Моделирование систем
* `ree-x` -- Радиоэлектроника и электронная техника
* `sw-x` -- Научная работа
* `ml-x` -- Машинное обучение
* `kr-x` -- Представление знаний

Иные включенные проекты в основном общего назначения (инфраструктура или утилиты).

## Получение исходников

Для клонирования любого репозитория организации используйте команду

```git
git clone --recurse-submodules https://github.com/d8euAI8sMs/<repository_name>
```

Например, чтобы склонировать данный репозиторий, выполните

```git
git clone --recurse-submodules https://github.com/d8euAI8sMs/learning
```

Многие из репозиториев организации содержат подмодули (submodules; или даже LFS-управляемые файлы), так что загрузка через `Download` (Скачать) может работать некорректно. `git clone` -- предпочтительный вариант.

## Получение артефактов сборки

pdf-отчеты для всех проектов (где применимо) могут быть найдены здесь: [![Build status](https://ci.appveyor.com/api/projects/status/1n2vfw3i1l7mp23x?svg=true)](https://ci.appveyor.com/project/kalaider/learning)

exe, dll и т.д. могут быть найдены здесь:

```
https://ci.appveyor.com/project/kalaider/<project_name>
```

где `<project_name>` -- имя желаемого проекта. Например, https://ci.appveyor.com/project/kalaider/ss-6-heat и т.д.
