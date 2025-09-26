# Принцип частотно-временной неопределённости в сейсмике

## Как запустить ноутбук

### 1. Локально с Python и venv

```bash
# Создать виртуальное окружение
python -m venv .venv

# Активировать (Linux/macOS)
source .venv/bin/activate
# Активировать (Windows)
.venv\Scripts\activate

# Установить зависимости
pip install numpy matplotlib scipy jupyter

# Запустить Jupyter
jupyter notebook
```

### 2. С помощью Google Colab

1. Откройте [colab.research.google.com](https://colab.research.google.com)
2. File → Upload notebook → выберите `01_timefreq.ipynb`
3. Добавьте ячейку в начало:
   ```python
   !pip install numpy matplotlib scipy
   ```
4. Runtime → Run all