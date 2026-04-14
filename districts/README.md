# Районы Кашкадарьинской области / Qashqadaryo viloyati tumanlari

## Назначение раздела

Раздел содержит данные по каждому из 13 районов Кашкадарьинской
области. Каждой папке соответствует отдельный заместитель хакима
района, который вносит данные через Pull Request.

Полная инструкция для заместителей:
- 🇷🇺 [docs/ru/instruktsiya-dlya-zamestitelej.md](../docs/ru/instruktsiya-dlya-zamestitelej.md)
- 🇺🇿 [docs/uz/orinbosarlar-uchun-qollanma.md](../docs/uz/orinbosarlar-uchun-qollanma.md)

## Список районов / Tumanlar ro'yxati

| № | Район / Tuman | Папка / Papka | Заместитель / O'rinbosar | План обновлён | Факт обновлён |
|---|---------------|---------------|--------------------------|---------------|---------------|
| 1 | Каршинский / Qarshi | [01-qarshi](01-qarshi/) | _TODO_ | _—_ | _—_ |
| 2 | Китабский / Kitob | [02-kitob](02-kitob/) | _TODO_ | _—_ | _—_ |
| 3 | Шахрисабзский / Shahrisabz | [03-shahrisabz](03-shahrisabz/) | _TODO_ | _—_ | _—_ |
| 4 | Яккабагский / Yakkabog' | [04-yakkabog](04-yakkabog/) | _TODO_ | _—_ | _—_ |
| 5 | Чиракчинский / Chiroqchi | [05-chiroqchi](05-chiroqchi/) | _TODO_ | _—_ | _—_ |
| 6 | Гузарский / G'uzor | [06-guzor](06-guzor/) | _TODO_ | _—_ | _—_ |
| 7 | Камашинский / Qamashi | [07-qamashi](07-qamashi/) | _TODO_ | _—_ | _—_ |
| 8 | Касбийский / Kasbi | [08-kasbi](08-kasbi/) | _TODO_ | _—_ | _—_ |
| 9 | Касанский / Koson | [09-koson](09-koson/) | _TODO_ | _—_ | _—_ |
| 10 | Миришкорский / Mirishkor | [10-mirishkor](10-mirishkor/) | _TODO_ | _—_ | _—_ |
| 11 | Мубарекский / Muborak | [11-muborak](11-muborak/) | _TODO_ | _—_ | _—_ |
| 12 | Нишанский / Nishon | [12-nishon](12-nishon/) | _TODO_ | _—_ | _—_ |
| 13 | Дехканабадский / Dehqonobod | [13-dehqonobod](13-dehqonobod/) | _TODO_ | _—_ | _—_ |

## Сводный план по области, 2026 / Viloyat yig'ma rejasi

<!-- Обновляется вручную или автоматически аппаратом области -->

| Показатель / Ko'rsatkich | Ед. | План области | Сумма планов районов | Расхождение |
|--------------------------|-----|--------------|----------------------|-------------|
| Объём инвестиций — всего | млн $ | _TODO_ | _TODO_ | _TODO_ |
| в т.ч. FDI | млн $ | _TODO_ | _TODO_ | _TODO_ |
| Количество проектов | шт. | _TODO_ | _TODO_ | _TODO_ |
| Рабочие места | чел. | _TODO_ | _TODO_ | _TODO_ |
| Экспорт | млн $ | _TODO_ | _TODO_ | _TODO_ |

## Сводное выполнение, 2026 / Viloyat yig'ma bajarilishi

| Показатель | План область | Факт Q1 | Факт Q2 | Факт Q3 | Факт Q4 | % вып. |
|------------|--------------|---------|---------|---------|---------|--------|
| Объём инвестиций |  |  |  |  |  |  |
| FDI |  |  |  |  |  |  |
| Проекты |  |  |  |  |  |  |
| Рабочие места |  |  |  |  |  |  |
| Экспорт |  |  |  |  |  |  |

## Шаблон для новых районов

Если район будет добавлен или реорганизован, скопируйте папку
[`_template/`](_template/) и переименуйте:

```bash
cp -r districts/_template districts/NN-district-slug
# затем вручную заменить {{DISTRICT_RU}}, {{DISTRICT_UZ}}, {{YEAR}} в файлах
```
