# Time_series
<h3 class="markdown-body">Предсказание объёма и температуры на 7 дней вперёд по ретроспективным данным объёма и температуры и по дате.</h3>


<h2 class="markdown-body">Исходные данные</h2>
Для решения задачи у нас есть данные с тремя столбцами: дата, объем и температура.

<h2 class="markdown-body">Шаги решения</h2>
<p class="markdown-body"><strong><em>Наша задача разбивается на следующие этапы:</em></strong></p>

1. Подготовка данных. Данные необходимо подготовить для обучения моделей. Это включает в себя разделение данных на тренировочный и тестовый наборы.

2. Моделирование. Мы рассматриваем различные методы прогнозирования, включая классические модели и нейронные сети. Важным аспектом является учет исторических данных о температуре и объеме.

3. Оценка и выбор модели. Мы оцениваем производительность каждой модели на тестовом наборе данных и выбираем наилучшую модель.

4. Прогнозирование. Наилучшая модель используется для прогнозирования объема на 7-й день при известной температуре.

<h2 class="markdown-body">Методы</h2>
В данном проекте использованы различные методы, включая классические модели и методы машинного обучения, такие как метод случайного леса. Кроме того, также исследованы нейронные сети.

<h2 class="markdown-body">Зависимости</h2>
Для воспроизведения результатов и выполнения задачи вам потребуется следующее программное обеспечение:

1. Python (версия 3.x)
   
2. Библиотеки Python, такие как NumPy, Pandas, scikit-learn, TensorFlow (для нейронных сетей) и другие, установленные с помощью pip install.

<h2 class="markdown-body">Инструкции по использованию</h2>
1. Клонируйте репозиторий на свой компьютер.

2. Запустите Jupyter Notebook или скрипты Python для выполнения анализа и обучения моделей.
