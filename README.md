# Коллекции в Postman, созданные для тестирования API

## Приложение Яндекс Прилавок   
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/db46c0f32c79bd512bcd?action=collection%2Fimport)
#### `REST` `SOAP`   
#### Тестирование новых ручек с методами `GET`, `POST`, `PUT`, `DELETE`   
#### [Требования](https://drive.google.com/file/d/1PLZ114aKaqZ8hk4LLmMXmdrhVh6fMUXy/view?usp=share_link) и [Чек-лист](https://docs.google.com/spreadsheets/d/12B0Qc15lam_QjZVf8aphwRNwUIL_RkmVPAS90Vap-qY/edit#gid=1059464317)   
<details> 
  <summary>Список тестируемых функциональностей и ручек</summary>   
  Работа с наборами:   
  
  - возможность добавлять продукты в набор. Ручка POST /api/v1/kits/:id/products
  
  Работа с курьерами:   
  
  - возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит. Ручка POST /fast-delivery/v3.1.1/calculate-delivery.xml
  
  Работа с корзиной:   

- возможность получить список продуктов, которые добавили в корзину. Ручка GET /api/v1/orders/:id
- возможность добавлять продукты в корзину. Ручка PUT /api/v1/orders/:id
- возможность удалять корзину. Ручка DELETE /api/v1/orders/:id
  </details> 

## Приложение Яндекс Самокат
[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/9fa6661f28feb8db9fcb?action=collection%2Fimport)   
#### `REST`   
#### Тестирование новых ручек с методами `GET`, `POST`, `DELETE`   
#### [Требования](https://drive.google.com/file/d/1mtKfNo2nBDrGdjY_rRAOifNdXfkySn35/view?usp=share_link) и [Чек-лист](https://docs.google.com/spreadsheets/d/12B0Qc15lam_QjZVf8aphwRNwUIL_RkmVPAS90Vap-qY/edit#gid=1468423848)
<details> 
  <summary>Список тестируемых функциональностей и ручек</summary>
Протестировать функциональность, выделенную в требованиях жирным шрифтом. 
  
Работа с курьерами:   
  
  - возможность создать курьера. Ручка POST /api/v1/courier/login   
  - возможность удалить курьера. Ручка DELETE /api/v1/courier/:id
  
Работа с заказами:   
  
  - возможность получить данные о заказе по его номеру. Ручка GET /api/v1/orders/track
  </details> 
