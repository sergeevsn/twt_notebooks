# Ноутбуки для канала https://t.me/twowaytime

```01_freq_time_uncertainty_bpf.ipynb``` Принцип частотно-временной неопределённости сигналов.
```02_ormsby_filter_wavelet.ipynb``` Ormsby Bandpass: Ракетный фильтр на службе геофизика.
```03_pef_deconvolution.ipybb``` Prediction Error Filter (PEF) в сейсморазведке: Деконволюция
```04_acoustic_modelling.ipynb``` 2D FD моделирования волнового поля в акустическом приближении
```05_pylops_kirchhoff.ipynb``` Kirchhoff моделирование/миграция с помощью библиотеки PyLops
```06_rtm.ipynb``` Reverse Time Migration (RTM) 
```07_pylops_lsm.ipynb``` Least Squares Migration (LSM) с помощью библиотеки PyLops
```08_time_depth_kirchhoff.ipynb``` Временная миграция VS Глубинная: сравнение на примере миграции Кирхгофа
```09_one_way_wem_poststack.ipynb``` One-Way Wave Equation Migration (миграция на основе одностороннего волнового уравнения)
```10_vsp_polarization_prt.ipynb``` 3C ВСП: Поляризационный анализ и трансформация 3C-данных
```11_tuning_1d.ipynb``` Изучение тюнинг-эффекта с помощью 1D FD-моделирования
```12_shponge_pml.ipynb``` Борьба с отражениями на границах модели: Shponge Layer vs PML

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