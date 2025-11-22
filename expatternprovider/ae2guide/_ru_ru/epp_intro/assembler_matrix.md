---
navigation:
    parent: epp_intro/epp_intro-index.md
    title: Матрица ассемблера
    icon: expatternprovider:assembler_matrix_frame
categories:
- extended devices
item_ids:
- expatternprovider:assembler_matrix_frame
- expatternprovider:assembler_matrix_wall
- expatternprovider:assembler_matrix_glass
- expatternprovider:assembler_matrix_pattern
- expatternprovider:assembler_matrix_crafter
- expatternprovider:assembler_matrix_speed
---

# Матрица ассемблера

<Row>
<BlockImage id="expatternprovider:assembler_matrix_frame" p:formed="true" p:powered="true" scale="5"></BlockImage>
<BlockImage id="expatternprovider:assembler_matrix_wall" scale="5"></BlockImage>
<BlockImage id="expatternprovider:assembler_matrix_glass" scale="5"></BlockImage>
</Row>
<Row>
<BlockImage id="expatternprovider:assembler_matrix_pattern" scale="5"></BlockImage>
<BlockImage id="expatternprovider:assembler_matrix_crafter" scale="5"></BlockImage>
<BlockImage id="expatternprovider:assembler_matrix_speed" scale="5"></BlockImage>
</Row>

Матрица ассемблера — это многоблочная структура. Она представляет собой комбинацию <ItemLink id="ae2:molecular_assembler" /> и <ItemLink id="ae2:pattern_provider" />.
Она может выполнять множество задач по созданию одновременно (при наличии достаточного количества <ItemLink id="ae2:crafting_accelerator" /> в вашей ME Сети) и экономить каналы.

## Структура

<GameScene zoom="3" background="transparent" interactive={true}>
  <ImportStructure src="../structure/assembler_matrix.snbt"></ImportStructure>
</GameScene>

Это прямоугольная призма с длиной рёбер от 3 до 7.
- Рёбра состоят из рамки матрицы ассемблера.
- Грани состоят из стены/стекла матрицы ассемблера.
- Внутренняя часть состоит из ядер шаблона/создания/скорости матрицы ассемблера.

Корректная матрица ассемблера должна содержать как минимум одно ядро ​​шаблона и ядро создания.
Она должна быть полностью заполнена и не может быть полой.
Когда матрица ассемблера правильно сформирована и подключена, линии на рамке матрицы ассемблера становятся синими.

## Ядро матрицы ассемблера

Существует 3 различных ядра матрицы ассемблера.

- Ядро шаблона матрицы ассемблера

Матрица ассемблера берёт шаблоны только из своего ядра шаблона. Каждое ядро ​​шаблона предоставляет 36 слотов шаблонов для матрицы ассемблера.

- Ядро создания матрицы ассемблера

Матрица ассемблера назначает полученные задачи на создание своему ядру создания. Каждое ядро ​​создания может выполнять 8 задач создания одновременно.

- Ядро скорости матрицы ассемблера

Это <ItemLink id="ae2:speed_card" /> для матрицы ассемблера. 5 ядер скорости позволяют матрице ассемблера работать на полной скорости.
Установка более 5 ядер скорости не даст дополнительного прироста скорости.

## Графический интерфейс

Щёлкните [ПКМ] по сформированной и подключенной матрице ассемблера, чтобы открыть её GUI.

![GUI](../pic/assembler_matrix.png)

Вы можете добавлять или искать в ней шаблоны, а также просматривать количество выполняемых задач на создание.
