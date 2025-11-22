---
navigation:
    parent: epp_intro/epp_intro-index.md
    title: ME Беспроводной соединитель
    icon: expatternprovider:wireless_connect
categories:
- extended devices
item_ids:
- expatternprovider:wireless_connect
- expatternprovider:wireless_tool
---

# ME Беспроводной соединитель

<Row gap="20">
<BlockImage id="expatternprovider:wireless_connect" scale="6"></BlockImage>
<ItemImage id="expatternprovider:wireless_tool" scale="6"></ItemImage>
</Row>

ME Беспроводной соединитель может связывать две ME Сети, как <ItemLink id="ae2:quantum_link" />, но на ограниченном расстоянии и не может
пересекать измерения. ME Беспроводной соединитель поддерживает только соединения типа «один к одному». Для соединений типа «многие ко многим»
необходимо использовать <ItemLink id="expatternprovider:wireless_hub" />.

## Связывание ME Беспроводных соединителей

Щёлкните на два ME Беспроводных соединителя, которые нужно связать с помощью ME Беспроводного инструмента настройки, чтобы связать их.

Удерживайте [Shift + ПКМ], чтобы очистить текущие настройки ME Беспроводного инструмента настройки.

ME Беспроводной соединитель изменит свою текстуру после успешного установления связывания.

Неподключенные ME Беспроводные соединители:

<GameScene zoom="5" background="transparent">
  <ImportStructure src="../structure/wireless_connector_off.snbt"></ImportStructure>
</GameScene>

Подключенные ME Беспроводные соединители:

<GameScene zoom="5" background="transparent">
  <ImportStructure src="../structure/wireless_connector_on.snbt"></ImportStructure>
</GameScene>

## Цвет

ME Беспроводные соединители могут быть окрашены так же, как и кабели, и подключать только кабель/соединение того же цвета.

Для окрашивания ME Беспроводного соединителя вам понадобится <ItemLink id="ae2:color_applicator" />.

Таким образом, вы можете настроить ME Беспроводные соединители следующим образом:

<GameScene zoom="3" background="transparent" interactive={true}>
  <ImportStructure src="../structure/wireless_connector_setup.snbt"></ImportStructure>
</GameScene>

## Энергопотребление

ME Беспроводные соединители потребляют больше энергии, когда они расположены дальше друг от друга. Зависимость стоимости от расстояния не является линейной,
поэтому расходы энергии могут стать очень высокими, если они находятся слишком далеко друг от друга.

Вы можете использовать <ItemLink id="ae2:energy_card" /> для экономии энергии: каждая карта может снизить расход энергии на 10%.

