---
navigation:
    parent: epp_intro/epp_intro-index.md
    title: ME Шина хранения по тегу
    icon: expatternprovider:tag_storage_bus
categories:
- extended devices
item_ids:
- expatternprovider:tag_storage_bus
---

# ME Шина хранения по тегу

<GameScene zoom="8" background="transparent">
  <ImportStructure src="../structure/cable_tag_storage_bus.snbt"></ImportStructure>
</GameScene>

ME Шина хранения по тегу — это <ItemLink id="ae2:storage_bus" /> , которую можно фильтровать по тегам предметов или жидкостей, и которая поддерживает некоторые базовые логические операторы.

Вот несколько примеров правил:

- Принимать только необработанную руду

forge:raw_materials/*

- Принимать все слитки и драгоценные камни

forge:ingots/* | forge:gems/*

