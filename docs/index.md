## Виджет проверки и оплаты штрафов ГИБДД

Виджет позволяет искать и оплачивать неоплаченные штрафы в базе ГИБДД.

Заработок на виджете штрафов ГИБДД Вы заработаете 3% от суммы штрафа, который оплатил посетитель - 30 рублей с оплаты штрафа на сумму 1000 рублей

Вы будите получать вознаграждение от оплаты каждого нового пользователя который зарегистрируется через виджет на вашем сайте

Мы сами будем отправлять пользователям оповещения о новых штрафах, а вы будите получать 3% от каждой оплаты.

Код для установки виджета

```markdown

<script>
    var driverHelperFineWidget = {
        partnerId: 1
        ,contaiter: 'driverHelperFineWidget'
        ,width: '100%'
        ,height: '600px'
    };
    (function(w, d, st) {
        w.st = st;
        var script = document.createElement('script');
        script.src = 'https://www.driver-helper.ru/shtrafy-gibdd/widget/inline.js';
        document.getElementsByTagName("body")[0].appendChild(script);
    }(window, document, driverHelperFineWidget));
</script>
<div id="driverHelperFineWidget"></div>

```

Сервис [проверки и оплаты штрафов ГИБДД](https://www.driver-helper.ru/shtrafy-gibdd/proverit).
