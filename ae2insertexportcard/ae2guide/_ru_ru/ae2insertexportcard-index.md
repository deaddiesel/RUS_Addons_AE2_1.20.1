---
navigation:
  title: "Дополнение: Карты вставки и экспорта"
  icon: ae2insertexportcard:export_card
  position: 150
categories:
  - tools
item_ids:
- ae2insertexportcard:export_card
- ae2insertexportcard:insert_card
---

# Карты вставки и экспорта

<Row>
  <ItemImage id="ae2insertexportcard:export_card" scale="2" />

  <ItemImage id="ae2insertexportcard:insert_card" scale="2" />
</Row>

Карты вставки и экспорта позволяют вставлять/экспортировать предметы из вашего инвентаря.

## Карта вставки

<ItemImage id="ae2insertexportcard:insert_card" scale="2" />

Карта вставки берёт предметы из определённых слотов вашего инвентаря и помещает их в вашу ME Систему.

![Insert Card](diagrams/insert_card.png)

Нажатие на слоты помечает их галочкой. Любой предмет в слоте с галочкой будет импортирован в вашу ME Систему. Перетащите предметы из инвентаря наверх, чтобы изменить фильтр.

### Улучшения

Карта вставки поддерживает следующие [улучшения](items-blocks-machines/upgrade_cards.md):

*   <ItemLink id="fuzzy_card" /> фильтрует по уровню повреждения и/или игнорирует NBT-предмет.
*   <ItemLink id="inverter_card" /> переключает фильтр с белого списка на чёрный.

### Рецепт

<RecipeFor id="ae2insertexportcard:insert_card" />

## Карта экспорта

<ItemImage id="ae2insertexportcard:export_card" scale="2" />

Карта экспорта работает точно так же, но переносит предметы из вашей ME Системы в ваш инвентарь.

![Export Card](diagrams/export_card.png)

Чтобы указать, какие предметы нужно перетащить, перетащите предмет из инвентаря в один из слотов сверху и нажмите на слот в инвентаре, чтобы изменить его номер на нужный. Щелчок [ПКМ] очистит список, вернув его к положению X.

### Улучшения

Карта вставки поддерживает следующие [улучшения](items-blocks-machines/upgrade_cards.md):

*   <ItemLink id="fuzzy_card" /> фильтрует по уровню повреждения и/или игнорирует NBT-предмет.
*   <ItemLink id="speed_card" /> увеличивает скорость перемещения предметов от одного до целого стека.
*   <ItemLink id="crafting_card" /> автоматически запрашивает и создаёт предметы, которые в данный момент недоступны.

### Рецепт

<RecipeFor id="ae2insertexportcard:export_card" />
