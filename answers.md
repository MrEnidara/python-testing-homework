1. Разница между unittest и pytest:
unittest — стандартная библиотека, основана на классах, требует больше шаблонного кода.
pytest — более гибкий и удобный, поддерживает функции, параметризацию и меньше кода.

2. Зачем нужны автоматические тесты:
Чтобы находить ошибки, не ломать старый код при изменениях и уверенно развивать проект.

3. Виды ассертов:
В unittest: assertEqual, assertTrue, assertRaises, и т.д.
В pytest: просто assert, плюс with pytest.raises() для ошибок.

4. Что делает @pytest.mark.parametrize:
Позволяет запускать один и тот же тест с разными входными данными.

5. Когда лучше использовать pytest:
Когда нужен простой, гибкий и мощный инструмент с хорошей читаемостью и поддержкой плагинов.