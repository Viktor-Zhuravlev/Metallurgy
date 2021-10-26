# Metallurgy
Task on statistical analysis and forecast of the quality of steel after the roasting machine.
## Task 1
An employee of the product quality assessment service noticed that the number of defective steel sheets in the batch for steel grade `A` is greater than for steel grade `B`. He also drew attention to the fact that with an average rolling speed of more than 4 m/s, the number of defective sheets is greater. In accordance with these observations, it is proposed to reduce the rolling speed and introduce additional quality control measures for `A` grade steel.,
    Check:

    1) More than 3 defective sheets per batch come out significantly more often for steel grade `A` than for steel grade `B`.
    2) At rolling speeds of more than 4 m/s, more than 3 defective steel sheets per batch come out significantly more often than at lower rolling speeds.

The data required for analysis is contained in the \"Statistics for 2018\" file. The number of steel sheets in each batch is assumed to be the same.

## Task 2
You need to build a model that, based on the data received every minute, determines the quality of the products produced by the roasting machine.

The roasting machine is an aggregate consisting of 5 chambers of the same size, 3 temperature sensors are installed in each chamber. In addition, for this task, you have collected data on the height of the raw material layer and its humidity. The layer height and humidity are measured when the raw material enters the machine. The raw material passes through the roasting machine in an hour.

The quality of products is measured in the laboratory by samples that are taken every hour, data on known analyses are contained in the file Y_train.csv. The file indicates the time of sampling, the sample is taken at the exit of the firing machine. You have agreed with the customer that the evaluation of the model will be the indicator MAE, to evaluate the model, you need to generate predictions for the period specified in the file Y_submit.csv (5808 predicts).

# Металлургия
Задание на статистический анализ и прогноз качества стали производимой в обжиговой машине.
## Задание 1
Сотрудник службы оценки качества продукции заметил, что число бракованных листов стали в партии для стали марки A больше, чем для стали марки B. Также он обратил внимание, что при средней скорости прокатки более 4 м/с число бракованных листов больше. В соответствии с этими наблюдениями, предлагается снизить скорость прокатки и ввести дополнительные меры контроля качества для стали марки A.  
Обоснуйте, что:
  1)	Более 3 бракованных листов на партию выходит значимо чаще для стали марки А, чем для стали марки B.
  2)	При скоростях прокатки более 4 м/с свыше 3 бракованных листов стали на партию выходит значимо чаще, чем при меньших скоростях прокатки. 
Данные, необходимые для анализа, содержатся в файле «Статистика за 2018 год». Количество листов стали в каждой партии предполагается одинаковым. 
## Задание 2
Вам необходимо построить модель, которая на основании данных, поступающих каждую минуту, определяют качество продукции, производимое на обжиговой машине.
Обжиговая машина представляет собой агрегат, состоящий из 5 одинаковых по размеру камер, в каждой камере установлено по 3 датчика температур. Кроме этого, для данной задачи Вы собрали данные о высоте слоя сырья и его влажности. Высота слоя и влажность измеряются при входе сырья в машину. Сырье проходит через обжиговую машину за час.
Качество продукции измеряется в лаборатории по пробам, которые забираются каждый час, данные по известным анализам содержатся в файле Y_train.csv. В файле указано время забора пробы, проба забирается на выходе из обжиговой машины.
Вы договорились с заказчиком, что оценкой модели будет являться показатель MAE, для оценки модели необходимо сгенерировать предсказания за период, указанный в файле Y_submit.csv (5808 предиктов).
