---
navigation:
    parent: epp_intro/epp_intro-index.md
    title: ME Пороговая шина экспорта
    icon: expatternprovider:threshold_export_bus
categories:
- extended devices
item_ids:
- expatternprovider:threshold_export_bus
---

# ME Пороговая шина экспорта

<GameScene zoom="8" background="transparent">
  <ImportStructure src="../structure/cable_threshold_export_bus.snbt"></ImportStructure>
</GameScene>

ME Пороговая шина экспорта работает, когда количество предметов, хранящихся в ME Сети, выше/ниже порогового значения.

## Пример

![GUI](../pic/thr_bus_gui1.png)

Пороговое значение меди установлено на 128, поэтому она экспортирует медь, когда количество хранящейся в сети меди превышает 128.

![GUI](../pic/thr_bus_gui2.png)

Пороговое значение такое же, как указано выше, но режим установлен на «Работать, когда НИЖЕ порога». Она экспортирует медь, когда количество хранящейся в сети меди ниже 128.
