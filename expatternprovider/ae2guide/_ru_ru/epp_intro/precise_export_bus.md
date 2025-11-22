---
navigation:
    parent: epp_intro/epp_intro-index.md
    title: ME Точная шина экспорта
    icon: expatternprovider:precise_export_bus
categories:
- extended devices
item_ids:
- expatternprovider:precise_export_bus
---

# ME Точная шина экспорта

<GameScene zoom="8" background="transparent">
  <ImportStructure src="../structure/cable_precise_export_bus.snbt"></ImportStructure>
</GameScene>

ME Точная шина экспорта экспортирует предметы/жидкости в заданных количествах. Экспорт осуществляется только в том случае, если контейнер может полностью принять весь объём.

## Пример

![GUI](../pic/pre_bus_gui1.png)

Это означает экспорт 3 булыжников за операцию. Экспорт прекращается, когда количество булыжника в сети становится меньше 3.

![GUI](../pic/pre_bus_gui2.png)

Экспорт также прекращается, когда целевой контейнер не может вместить всё экспортированное. Теперь сундук может вместить только 2 булыжника, поэтому ME Точная шина экспорта останавливается.
