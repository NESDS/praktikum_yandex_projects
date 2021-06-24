## Прогноз оттока клиентов в сети фитнес-центров

[ссылка на просмотр проекта в nbviewer](https://nbviewer.jupyter.org/github/NESDS/praktikum_yandex_projects/blob/main/2021_05_10_outflow_fitness_clients/2021_05_10_outflow_fitness_clients.ipynb)

---
### Данные 📁
 Есть данные, которые содержат данные на месяц до оттока и факт оттока на определённый месяц, в том числе информация на основе журнала посещений, покупок и информация о текущем статусе абонемента клиента.

---
### Задача 📝
Необходимо провести анализ и подготовить план действий по удержанию клиентов фитнес-центра.

---
### Краткий вывод 💡
Высокая вероятность оттока клиентов, у которых:  
сontract_period = 1;  
age < 28;  
month_to_end_contract = 1;  
group_visits = 0;  
avg_class_frequency_current_month < 1,5;  
lifetime < 2.</font>  

---
### Используемые библиотеки 🛠️
``` pandas, seaborn, matplotlib, plotly, numpy, sklearn, tqdm, scipy ```
