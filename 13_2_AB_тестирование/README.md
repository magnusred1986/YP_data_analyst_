# [Проект по А/B-тестированию](https://github.com/magnusred1986/YP_data_analyst_/blob/main/13_2_AB_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5/13_AB_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.ipynb)  
[доп.ссылка](https://nbviewer.org/github/magnusred1986/YP_data_analyst_/blob/main/13_2_AB_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5/13_AB_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.ipynb)  

## провести оценку результатов A/B-теста
## Оценить корректность проведения теста. Проанализируйте результаты теста.

**Техническое задание:**  

* Название теста: recommender_system_test;  
* Группы: А (контрольная), B (новая платёжная воронка);  
* Дата запуска: 2020-12-07;  
* Дата остановки набора новых пользователей: 2020-12-21;  
* Дата остановки: 2021-01-04;  
* Аудитория: 15% новых пользователей из региона EU;  
* Назначение теста: тестирование изменений, связанных с внедрением улучшенной рекомендательной системы;
* Ожидаемое количество участников теста: 6000.  
* Ожидаемый эффект: за 14 дней с момента регистрации в системе пользователи покажут улучшение каждой метрики не менее, чем на 10%:
 * конверсии в просмотр карточек товаров — событие product_page
 * просмотры корзины — product_cart
 * покупки — purchase

## Инструменты
* pandas
* matplotlib
* plotly.graph_objects
* math
* scipy
 
