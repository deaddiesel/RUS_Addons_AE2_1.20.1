---
navigation:
    parent: epp_intro/epp_intro-index.md
    title: ME Наполнитель
    icon: expatternprovider:caner
categories:
- extended devices
item_ids:
- expatternprovider:caner
---

# ME Наполнитель

<BlockImage id="expatternprovider:caner" scale="8"></BlockImage>

ME Наполнитель — это машина, которая «консервирует» различные вещества, включая жидкости, газ мода «Меканизм», ману мода «Ботания» и даже энергию!

Первый слот предназначен для заполнения, а второй - для того, что нужно заполнить.

Для работы требуется энергия, и каждая операция стоит 80 AE.

![GUI](../pic/caner_gui.png)

По умолчанию он заполняет только жидкости. Для заполнения других веществ необходимо установить соответствующее дополнение.

### Поддерживаемые дополнения:
- Прикладной флюс [Applied Flux]
- Прикладная меканистика [Applied Mekanistics]
- Прикладная ботания [Applied Botanics Addon]

## Автоматическое создание с ME Наполнителем

Только верхняя и нижняя стороны могут принимать энергию и подключаться к сети.

<GameScene zoom="6" background="transparent">
  <ImportStructure src="../structure/caner_example.snbt"></ImportStructure>
</GameScene>

Простая установка для ME Наполнителя. ME Наполнитель автоматически извлекает заполненный предмет, когда принимает ингредиенты из <ItemLink id="ae2:pattern_provider" />.

<GameScene zoom="6" background="transparent">
  <ImportStructure src="../structure/caner_auto.snbt"></ImportStructure>
</GameScene>

Шаблон должен содержать только заполняемый материал и ёмкость, которую нужно заполнить. Вот пример:

Наполнение ведра водой:

![P1](../pic/fill_water.png)


## Расконсервация

ME Наполнитель также может опустошать контейнер в режиме «Опустошение». Необходимо поменять местами входы и выходы в шаблоне.
