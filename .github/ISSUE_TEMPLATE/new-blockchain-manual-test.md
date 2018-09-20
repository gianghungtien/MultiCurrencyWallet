---
name: New blockchain Manual Test
about: тесткейс который позволяет протестировать полностью работает ли обмен на новом
  блокчейне

---

**проверка создания адреса**
- [ ] при заходе на главную страницу мне виден адрес, либо кнопка для его создания
- [ ] при нажатии на кнопку, мне показывается прелоадер а затем сразу адрес
- [ ] так или иначе адрес создается и баланс показывает 0


**проверка ввода и вывода средств**
- [ ] я отправил деньги извне и они пришли на баланс
- [ ] при нажатии на send показывается форма для ввода адреса и суммы, при этом показано сколько доступно для перевода
- [ ] если ввести сумму меньшую чем минимально возможная отправка то покажется ошибка
- [ ] если ввести сумму большую чем баланс то покажется ошибка
- [ ] форма не принимает левые данные кроме числа
- [ ] при нажатии на кнопку отправки появляется прелоадер
- [ ] как только транзакция замайнится прелоадер исчезает 
- [ ] транзакция на отправку видна в истории

**создание ордера на продажу едениц криптовалюты за биткоин**
- [ ] на странице кошелька есть кнопка SWAP, которая означает что можно поменять эту крипту на другую
- [ ] заходим на в свап и виден ордербук (таблица с обьявлениями на покупку и продажу)
- [ ] видна кнопка create order при нажатии на нее появляется форма для создания ордера
- [ ] в форме виден мой доступный баланс и он корректный
- [ ] я хочу продать 10 едениц за 0.1 биткоин, ввожу данные в sell 10 , в buy 0.1 btc автоматически устанавливается курс 100 едениц / BTC 
- [ ] я хочу продать больше чем у меня есть, появляется ошибка
- [ ] если поменять курс то поменяется поле buy, а поле сколько продать (sell) остается неизменным
- [ ] при нажатии далее все данные указаны верно 
- [ ] mining fee тоже указан верно
- [ ] если зайти из другого браузера и попробовать найти этот оредр то он будет виден в корректном месте

**создание ордера на покупку едениц криптовалюты за биткоин**
- [ ] хочу купить 100 едениц криптовалюты за 0.1 BTC ввел 100 едениц в поле buy и 0.1 BTC в поле sell все верно выставилось, курс верный (показывает 1000 едениц за BTC)
- [ ] ордер создается

**пробуем свпнутся**
- [ ] получилось свопнутся из двух браузеров (обоим в итоге написало "сенкью")