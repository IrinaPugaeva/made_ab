## hw 1
<blockquote>
  <p align="justify">В этом задании вам необходимо составить свой дизайн A/B-теста. Для этого вам нужно выбрать произвольный продукт (например - это маркет-плейс, сервис рекомендации видео, социальная сеть, мобильное приложение или проект, над которым работаете), дать его краткое описание (основная функция продукта и его цель). Далее к этому продукту необходимо сформулировать дизайн A/B-теста, то есть определить следующие пункты:</p>
</blockquote>
    
    1. Изменение - она же гипотеза, которая сделает продукт лучше.
    
    2. Метрики, по которым будет определяться, что продукт стал лучше.
    
    3. Аудитория - на ком должна быть протестирована гипотеза.
    
    4. Инфраструктура - как будут доставляться изменения и как будет деление аудитории происходить. (Описать примерно)
    
    5. Длительность проведения теста. (Пока не умеем ее рассчитывать, поэтому указать исходя из логических соображение)
    
    6. Ожидаемый эффект - на сколько должны вырасти ключевые метрики.

## hw 2
<blockquote>
  <p align="justify">В этом задании вам необходимо:</p>
</blockquote>
    
    1. Реализовать t-критерий Стьюдента для 2 независимых выборок при условии неизвестной дисперсии. 
    Необходимо считать значение статистики и p_value для разных видов гипотез (двусторонняя, односторонние), 
    а также результат (отвергается нулевая гипотеза или нет). Сравнить результаты с реализацией в scipy.stats.ttest_ind.
    
    2. Реализовать bootstrap для оценки (через доверительные интервалы) медианных и средних значений распределений. 
    Рассчитать для распределений: нормальное, экспоненциальное, смесь нормальных
    
    3. Рассчитать мощность критерия для t-критерия и критерия Манна-Уитни для разных распределений и разном эффекте. 
    Отдельно изучить случай, когда средние равны, а дисперсии сильно отличаются.
    
    4. Оценить корректность t-критерия и критерия Манна-Уитни на разных распределениях.
    
    5. Задание принимается в jupyter notebook

## hw 3
<blockquote>
  <p align="justify">В этом задании вам необходимо будет:</p>
</blockquote>

    1. Реализовать формулу подсчета длительности теста, сравнить ее с онлайн калькуляторами (например https://mindbox.ru/tools/ab-test-calculator/ ). 
    При сравнении оценить мощность критерия при указанном изменении и рассчитанном количестве наблюдений в выборке. 
    
    2. Реализовать метод линеаризации. Проверить для него корректность и мощность. 
    Мощность должна быть больше, чем просто на обычных значениях конверсии пользователей.
    
    3.Реализовать метод CUPED. Проверить для него корректность и мощность. 
    Данные на этапе до A/B тесте необходимо сгенерировать один раз, 
    далее синтетически генерировать только часть, связанную с проведением A/B-теста.
