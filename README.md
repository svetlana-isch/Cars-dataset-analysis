# Cars dataset analysis
Технологический практикум (практикум на ЭВМ)

Все задания ниже реализовать для собственных данных с использованием языков программирования R и Python. Снабдить программный код необходимыми комментариями. При выполнении заданий проверять
применимость методов для выбранных данных.
Первый этап:

1. Выбрать уникальные для каждого студента в группе датасеты для выполнения заданий практикума. Подготовить их описание, краткие характеристики (максимумы-минимумы, средние значения, пропуски и т.п.)
2. Реализовать аппроксимацию распределений данных с помощью ядерных оценок.
3. Реализовать анализ данных с помощью cdplot, dotchart, boxplot и stripchart.
4. Проверить, являются ли наблюдения выбросами с точки зрения формальных статистических критериев Граббса и Q-теста Диксона. Визуализировать результаты.
5. Воспользоваться инструментами для заполнения пропусков в данных. Пропуски внести вручную и сравнить результаты заполнения с истинными значениями.
6. Сгенерировать данные из нормального распределения с различными параметрами и провести анализ с помощью графиков эмпирических функций распределений, квантилей, метода огибающих, а также стандартных процедур проверки гипотез о нормальности (критерии Колмогорова-Смирнова, ШапироУилка, Андерсона-Дарлинга, Крамера фон Мизеса, Колмогорова-Смирнова в модификации Лиллиефорса и Шапиро-Франсия). Рассмотреть выборки малого (не более 50-100 элементов) и умеренного (1000-5000 наблюдений) объемов.
7. Продемонстрировать пример анализа данных с помощью графиков квантилей, метода огибающих, а также стандартных процедур проверки гипотез о нормальности. Рассмотреть выборки малого и умеренного объемов.
Второй этап:
1. Продемонстрировать применение для проверки различных гипотез и различных доверительных уровней (0.9, 0.95, 0.99) следующих критериев:
a. Стьюдента, включая односторонние варианты, когда
проверяемая нулевая гипотеза заключается в том, что одно из сравниваемых  средних значений больше (или меньше) другого. Реализовать оценку мощности критериев при заданном объеме выборки или определения объема выборки для достижения заданной мощности;
b. Уилкоксона-Манна-Уитни (ранговые);
c. Фишера, Левене, Бартлетта, Флигнера-Килина (проверка гипотез об однородности дисперсий).
2. Исследовать корреляционные взаимосвязи в данных с помощью коэффициентов корреляции Пирсона, Спирмена и Кендалла.
3. Продемонстрировать использование методов хи-квадрат, точного теста Фишера, теста МакНемара, Кохрана-Мантеля-Хензеля.
4. Проверить наличие мультиколлинеарности в данных с помощью корреляционной матрицы и фактора инфляции дисперсии.
5. Исследовать зависимости в данных с помощью дисперсионного анализа.
6. Подогнать регрессионные модели (в том числе, нелинейные) к данным, а также оценить качество подобной аппроксимации.
