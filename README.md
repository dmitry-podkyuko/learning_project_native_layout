# Практическое задание (Native Layout)

## Описание:

Задание направлено на прорабоотку perfect pixel, адаптивной и резиновой верстки.

## Стек:

- HTML
- CSS
- Расширение perfect pixel

## Требования к проекту:

- При ширине экрана `1920px` и `320px` верстка должна соответствовать стандарту `perfect pixel`
- При увеличении ширины экрана более `1920px` контент должен оставаться сгрупированным (не должен разъезжаться) и отцентрированным
- При изменении размера от `1920px` до `320px` контент не должен ломаться, у пользователя должна быть возможность видеть все содержимое
- При определении названий `class`-ов используется методология `БЭМ` по всем правилам

## Чек лист для сдачи проекта:

- [ ] Git Flow соблюдается, ветки и коммиты соответствуют всем правилам
- [ ] Создана пустая ветка `main`
- [ ] Создана пустая ветка `develop` которая базируется от `main`, и содержит initial коммит, в которой находится копия текущего репозитория

---

- [ ] Верстка макета в `perfect pixel` на ширине `1920px` выполнена в ветке `feat/layout_desktop` которая базируется от `develop` и создан PR на слияние с веткой `develop`
- [ ] Code Review созданного PR проведено разработчиком лично
- [ ] Code Review созданного PR проведено куратором (выделяется техническим лидером)

---

- [ ] Верстка макета в `perfect pixel` на ширине `320px` выполнена в ветке `feat/layout_mobile` которая базируется от `develop` после слияния с веткой `feat/layout_desktop` и создан PR на слияние с веткой `develop`
- [ ] Code Review созданного PR проведено разработчиком лично
- [ ] Code Review созданного PR проведено куратором (выделяется техническим лидером)

---

- [ ] После выполнения всех вышеописанных пунктов, создан PR из `develop` в `main`
- [ ] Code Review проведено разработчиком лично
- [ ] Code Review проведено куратором (выделяется техническим лидером)
- [ ] Code Review проведено техническим лидером

## Полезные ссылки:

- <a href="https://www.figma.com/design/MYbKS9HjOND4uDWFmPx60R/%D0%A1%D0%B8%D1%82%D0%B8%D0%9F%D1%80%D0%BE-(Copy)?node-id=0-1&t=9ILaf0fTvUerw9ms-1"> _Link to Designe_ </a>
- <a href="https://gist.github.com/dmitry-podkyuko/dcea9e5a22796af7ec910b14c2a84629"> Check List для Code Review (верстка) </a>
