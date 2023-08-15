# Отчётные документы по итогам тестирования
### Краткое описание
Проведено тестирование веб-сервиса по покупке тура в Марракеш. Все тестовые сценарии автоматизированы. Проверены два варианта оплаты:
- по дебетовой карте (Купить)
- по кредитной карте (Купить в кредит)

Автоматизированные тесты были успешно запущены для двух СУБД:
- MySQL
- PostgreSQL
#### Количество тест-кейсов
- Всего составлено - 38 тестов
- Успешных - 26 (68.42%) тестов
- Неуспешных - 12 (31.57%) тестов.

#### Отчет по результатам тестирования Gradle:
![diplom_test-set_gradle1.png](..%2F..%2F..%2FOneDrive%2F%C4%EE%EA%F3%EC%E5%ED%F2%FB%2Fdiplom_test-set_gradle1.png)
![diplom_test-set_gradle2.png](..%2F..%2F..%2FOneDrive%2F%C4%EE%EA%F3%EC%E5%ED%F2%FB%2Fdiplom_test-set_gradle2.png)
![diplom_test-set_gradle3.png](..%2F..%2F..%2FOneDrive%2F%C4%EE%EA%F3%EC%E5%ED%F2%FB%2Fdiplom_test-set_gradle3.png)
![diplom_test-set_gradle4.png](..%2F..%2F..%2FOneDrive%2F%C4%EE%EA%F3%EC%E5%ED%F2%FB%2Fdiplom_test-set_gradle4.png)
![diplom_test-set_gradle5.png](..%2F..%2F..%2FOneDrive%2F%C4%EE%EA%F3%EC%E5%ED%F2%FB%2Fdiplom_test-set_gradle5.png)

#### Отчет по результатам тестирования Allure:
![diplom_test-set_allure1.png](..%2F..%2F..%2FOneDrive%2F%C4%EE%EA%F3%EC%E5%ED%F2%FB%2Fdiplom_test-set_allure1.png)
![diplom_test-set_allure2.png](..%2F..%2F..%2FOneDrive%2F%C4%EE%EA%F3%EC%E5%ED%F2%FB%2Fdiplom_test-set_allure2.png)
![diplom_test-set_allure3.png](..%2F..%2F..%2FOneDrive%2F%C4%EE%EA%F3%EC%E5%ED%F2%FB%2Fdiplom_test-set_allure3.png)
![diplom_test-set_allure4.png](..%2F..%2F..%2FOneDrive%2F%C4%EE%EA%F3%EC%E5%ED%F2%FB%2Fdiplom_test-set_allure4.png)

### Общие рекомендации

**Общие рекомендации**:
* Исправить найденные ошибки
* Добавить тестовые метки data-test-id для устойчивости тестов 
* Добавить более информативные сообщения об ошибках, указывающие в чем конкретно ошибка.