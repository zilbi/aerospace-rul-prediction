# Aerospace RUL Prediction

Проект с Jupyter Notebook для прогнозирования Remaining Useful Life (RUL)
авиационных двигателей на датасете NASA C-MAPSS.

## Что находится в репозитории

- `test.ipynb` - ноутбук с загрузкой данных, подготовкой признаков,
  обучением модели и оценкой качества.
- `CMAPSSData/` - файлы датасета C-MAPSS: train, test, RUL и описание данных.
- `requirements.txt` - список Python-библиотек для запуска ноутбука.

## Установка зависимостей

Сначала откройте терминал в папке проекта.

### Windows

```powershell
py -m pip install -r requirements.txt
```

Если команда `py` не работает, попробуйте:

```powershell
python -m pip install -r requirements.txt
```

### macOS

```bash
python3 -m pip install -r requirements.txt
```

Если Python запускается командой `python`, используйте:

```bash
python -m pip install -r requirements.txt
```

### Linux

```bash
python3 -m pip install -r requirements.txt
```

Если Python запускается командой `python`, используйте:

```bash
python -m pip install -r requirements.txt
```

## Запуск ноутбука

Запускайте Jupyter Notebook из корневой папки проекта, чтобы пути к
`CMAPSSData/` работали правильно.

### Windows

```powershell
py -m notebook test.ipynb
```

Если команда `py` не работает:

```powershell
python -m notebook test.ipynb
```

### macOS и Linux

```bash
python3 -m notebook test.ipynb
```

Если Python запускается командой `python`:

```bash
python -m notebook test.ipynb
```

После открытия Jupyter запустите ячейки ноутбука по порядку.
