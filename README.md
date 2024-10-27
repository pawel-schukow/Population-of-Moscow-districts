# Исследование плотности населения и застройки в районах Москвы

Плотность населения и застройки – пожалуй, одни из важнейших характеристик городских территорий. В зависимости от степени населенности, разные жилые кварталы сталкиваются с разными проблемами, им требуются разные решения, нормы регулирования и подходы в управлении. Кроме того, перечисленные выше характеристики являются крайне важными критериями для оценки качества городской среды экспертами и выбора жилья обывателями.

## Цель проекта

Целью нашего проекта было исследовать плотность населения, застройки и обеспеченность жилым фондом в разных районах города Москвы, визуализировать и проанализировать полученные данные.

## Датасет

Мы использовали данные, найденные на просторах интернета по запросу «население районов Москвы» – Moscow Population 2018.csv, файл в одном из практикумов в Практических руководствах к Yandex.Cloud. Ссылку на практикум можно найти [здесь](https://yandex.cloud/ru/docs/tutorials/datalens/data-from-csv-to-public-visualization?utm_referrer=https%3A%2F%2Fwww.yandex.ru%2F).

## Задачи проекта

1. Приведение данных из CSV-файла в формат, понятный для Python (замена запятых точками и т.п.)
2. Вычисление относительных показателей из абсолютных (плотность населения)
3. Определение районов лидеров/антилидеров по показателям
4. Визуализация показателей в столбчатых диаграммах 
5. Создание карт для отображения районов лидеров/антилидеров по исследуемым показателям

## Результаты работы

Ниже приведены получившиеся диаграммы и карты.

![image](https://github.com/user-attachments/assets/34ff4911-6868-4c7c-a8f2-1253c4acaca6)
![image](https://github.com/user-attachments/assets/33435831-7a6a-46be-b4cf-cae5a5a04e46)
![image](https://github.com/user-attachments/assets/442b4e69-2620-4064-8c0b-73df43a51189)
![image](https://github.com/user-attachments/assets/e8aef1d4-873e-4020-8438-9fd34590acf8)
![image](https://github.com/user-attachments/assets/164551aa-9d69-45f6-b37d-321d46681401)
![image](https://github.com/user-attachments/assets/d52ccd48-746b-4075-9d4a-f3db43fcc561)
![image](https://github.com/user-attachments/assets/703afccd-5eeb-4a6c-b6bb-89150e0ff6f0)
![image](https://github.com/user-attachments/assets/3301fd04-daa2-4ac1-8d86-3a48d7ae7cd8)
![image](https://github.com/user-attachments/assets/b1d1a9f1-fa72-4d78-a757-106b5fe93223)
![image](https://github.com/user-attachments/assets/025b4217-729f-4006-aa1c-3687cd7923d4)
![image](https://github.com/user-attachments/assets/43dcd438-81ad-4e44-bde9-6ded17fb2371)
![image](https://github.com/user-attachments/assets/438b02fd-740a-471a-8f1c-0587066de127)


## Выводы

- **Наиболее плотно заселенные районы** Москвы — это, в основном, спальные районы на окраинах, которые застраивались преимущественно панельными многоэтажными (20+) домами в 80-х – начале 90-х, а также в границах которых довольно мало зеленых зон и промышленных территорий, участков без застройки. Это Зябликово, Новокосино, Восточное Дегунино, Бибирево, Бескудниково, Северное и Южное Медведково и Новогиреево (8 районов из топ-10, исключение – Ломоносовский, ввиду маленькой территории и большого населения, и отсутствия каких-либо других функций у района кроме жилых
  
- **Наименее плотно заселенные районы** Москвы – это бывшие сельские поселения в Новой Москве, т.к. их территория преимущественно представляет собой сельскохозяйственные угодья и зеленые зоны, изредка пересекаемые жилыми зонами с малоэтажной застройкой – частным сектором. В пределах МКАДа наименее плотно населенным районом является Метрогородок, т.к. в его административные границы попадает огромный участок национального парка «Лосиный остров».

- **Наиболее обеспеченными жилым фондом районы**, в основном, являются стереотипные благополучные и элитные районы: на юго-западе – Ломоносовский, Проспект Вернадского, Гагаринский, Раменки; районы недалеко от центра, но в которых чуть больше жилого фонда, чем в пределах Бульварного кольца – Якиманка, Даниловский, Дорогомилово, Хамовники, Мещанский; северо-запад Москвы в пределах Малого кольца Московской железной дороги (МЦК) – Хорошевский, Аэропорт, Коптево, плюс Тропарево-Никулино. Также есть не совсем понятные выбросы в виде Ховрина, Куркина и Центрального Чертанова, мы можем попробовать объяснить их в будущем.

- К сожалению, выявить одну или несколько полноценных закономерностей для **наименее обеспеченных жилым фондом районов** не получилось. Выделяются как районы с нвой застройкой и огромным населением (Некрасовка), районы, где часто селятся мигранты (Измайлово, Бирюлево), районы с большими промзонами (Капотня), так и районы в старой части города (Пресненский. 

- **Районы с наибольшей плотностью застройки**, как и районы с наибольшей плотностью населения, чаще всего – это те районы, в административные границы которых включены только селитебные территории, и мало зеленых зон и промзон.

- И районы, в которых **самая маленькая плотность жилой застройки**, как и районы с наименьшей плотностью населения – это районы, в административные границы которых входят большие зеленые зоны (Метрогородок, Молжаниновский)

## Список авторов

- Жукова Виктория
- Пинтелина Полина
- Жуков Павел
