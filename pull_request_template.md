git switch main
git pull
git switch -c feat/booking-reserve     # новая ветка под задачу
# ...пишете код, тесты...
git add .
git commit -m "feat(booking): reserve seat with expiry"
git push -u origin feat/booking-reserve

## Что сделано
!-- 1–3 предложения --

## Связь с отчётом
- Сценарий(и) S_
- ADR (если затронут, укажите номер)

## Проверка
- [ ] Тесты добавлены или обновлены
- [ ] `pytest`, `ruff`, `mypy` проходят локально
- [ ] Нет секретов в коде
- [ ] Границы модулей не нарушены