# crypto-predictor

## Прогнозирование цены криптовалюты на основе временных рядов
## Описание

Данный проект содержит код на языке Python, который позволяет получать и анализировать исторические данные цен криптовалюты и строить прогнозы цен на основе временных рядов. Прогнозы основаны на нейронных сетях, использующих библиотеку Keras.
Запуск

Для запуска проекта необходимо:

    # [Необязательно] Cоздай дополнительную папку
    mkdir git
    # Скачай все файлы из репозитория в локальную папку
    git clone https://github.com/bkamuz/crypto-predictor.git
    # Установи необходимые библиотеки, указанные в файле первом блоке ноутбука или запусти команды в терминале
    # Если pip не наден, попробуй использовать pip3
    pip install nbformat
    pip install requests
    pip install pandas
    pip install numpy
    pip install keras
    pip install tensorflow
    pip install plotly
    # Запустить ноутбук используя к примеру vscode или любую другую IDE поддерживающие ноутбуки

Используемые библиотеки

    os
    re
    math
    csv
    requests
    datetime
    pandas
    numpy
    keras
    tensorflow
    plotly

Сохраненная модель в папке models/ - это модель для масштабированных данных.

Для быстрого просмотра ноутбука с графиками можно воспользоватсья сервисом nbviewer:

[открыть crypto-predictor в nbviewer](https://nbviewer.org/github/bkamuz/crypto-predictor/blob/main/crypto-predictor.ipynb)

[открыть crypto-predictor(no_scale) в nbviewer](https://nbviewer.org/github/bkamuz/crypto-predictor/blob/main/crypto-predictor(no_scale).ipynb)

Либо установить расширения "Plotly renderer for GitHub" или "GitHub + nbviewer". Они позволяют просматривать ноутбуки Jupyter, содержащие графики Plotly, непосредственно на страницах GitHub.
