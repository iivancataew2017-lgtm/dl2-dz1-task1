# Инсрукция по установке и проверке

В работе выполненны модули module-0 и module-1.

Проверялось на версии питона Python 3.10.21.

После перехода в видректорю репы, нужно сделать установку библиотек, после проверьте по интсукции снизу:

```bash
python3 -m pip install -r requirements.txt
pytest tests/test_{operators,module,scalar,autodiff}.py -v
```
