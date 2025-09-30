# Ноутбуки для канала https://t.me/twowaytime

```01_freq_time_uncertainty_bpf.ipynb``` Принцип частотно-временной неопределённости сигналов.
```02_ormsby_filter_wavelet.ipynb``` Ormsby Bandpass: Ракетный фильтр на службе геофизика.
```03_pef_deconvolution.ipybv``` Prediction Error Filter (PEF) в сейсморазведке: Деконволюция
...

## Как запустить ноутбук

### 0. Клонирование репозитория

```bash
git clone https://github.com/sergeevsn/twt_notebooks.git
cd twt_notebooks
```

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

#### Вариант A: Открыть прямо с GitHub
1. Откройте [colab.research.google.com](https://colab.research.google.com)
2. File → Open notebook → GitHub
3. Введите URL: `https://github.com/sergeevsn/twt_notebooks`
4. Выберите файл `01_freq_time_uncertainty_bpf.ipynb`
5. Runtime → Run all

#### Вариант B: Загрузить файл
1. Откройте [colab.research.google.com](https://colab.research.google.com)
2. File → Upload notebook → выберите `01_freq_time_uncertainty_bpf.ipynb`
3. Runtime → Run all