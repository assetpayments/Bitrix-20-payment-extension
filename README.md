## Модуль оплаты Битрикс 18

### Установка

* Загрузите содержимое директории upload/ в корень сайта по фтп
* Добавьте модуль в меню Магазин -> Настройки -> Платежные системы -> Добавить платежную систему
* Настройки:
 * Обработчик - Пользовательские - AssetPayments
 * Заголовок - Онлайн платежи AssetPayments
 * Название - Оплатить картой Visa/MasterCard (AssetPayments)
 * Активность - да
 * Сортировка - 100
 * Описание - Облачная платформа процессинга онлайн платежей AssetPayments
 * Логотип - указать путь к файлу asset_logo.png в папке upload
 * Открывать в новом окне - нет
 * Тип оплаты - Эквайринговая операция, или безналичный
 * Разрешить автопересчет оплаты - да
 * Разрешить печать чеков - нет
 * Кодировка - UTF-8 или Win-1251
 * Код - пусто
 ----------------------------------------------------------------
 * ID Шаблона - 19
 * Секретный ключ - уточните в службе поддержки AssetPayments
 * ID магазина - уточните в службе поддержки AssetPayments
 * Сохранить

### Примечания
Протестировано с Bitrix 18.1.5 Управление сайтом (Дистрибутивы Малый бизнес и Бизнес) 


## Bitrix 18 payment module

### Installation

* Upload the [upload] directory content to root directory of your website via ftp
* Add new module in Shop ->Settings->Payment methods->Add payment method
* Settings:
  * Processor - AssetPayments 
  * Title - Online payments AssetPayments
  * Name - Pay by card Visa/MasterCard (AssetPayments)
  * Active - yes
  * Sorting - 100
  * Description - Cloud-based online payments processing AssetPayments
  * Logo - set path to asset_logo.png inside upload folder
  * Open in new window - no
  * Payment type - acquiring
  * Allow recalculation - yes
  * Allow to print chaques - yes
  * Encoding - UTF-8
  * Code - empty
  ----------------------------------------------------------------
 * Template ID - 19
 * Secret key - request at AssetPayments support departament
 * Shop ID - request at AssetPayments support departament
 * Press Save settings.
  
### Notes
Tested with Bitrix 18.1.5 Site management (Small business & Business editions) 

