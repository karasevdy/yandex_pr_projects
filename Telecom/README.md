# Прогнозирование оттока клиента телеком компании 
## Описание проекта
Оператору мобильной связи необходимо спрогнозировать отток клиентов. 
Если модель сочтет, что пользователь склонен уйти, ему будут предложены промокоды и специальные условия. 
Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах. <br><br>
Основная метрика качества модели: ROC-AUC (>= 0.85) <br>
Дополнительная метрика: accuracy
## Описание данных

- информация о договоре (дата заключения и расторжения, тип и способ оплаты, ежемесячные и общие расходы);
- персональные данные клиента (соц-дем);
- информация об услугах телефонии (использовалась ли услуга параллельных линий);
- информация об интернет-услугах (тип подключения и дополнительные услуги).

## Используемые библиотеки

*pandas, numpy, matplotlib, seaborn, sklearn, phik, catboost*

## Выводы
