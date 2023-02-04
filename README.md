dogtail is a GUI test tool and automation framework written in Python. It uses Accessibility (a11y) technologies to communicate with desktop applications. dogtail scripts are written in Python and executed like any other Python program.

Исходник: https://gitlab.com/dogtail/dogtail \
Взята версия 0.9.11.

Добавлена возможность узнать наименование объектов и окон стиля ldtp. Для работы требует модернизированный ldtp: https://github.com/10Legend01/ldtp3

Рекомендуется устанавливать следующим способом:
```
sudo python3 setup.py build
sudo python3 setup.py install
```

Или: \
`sudo easy_install3 dogtail==0.9.11`

Чтобы запустить приложение, необходимо ввести в терминале: \
`sniff`
