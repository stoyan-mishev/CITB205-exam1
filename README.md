# CITB205-exam1

Да се състави абстрактен базов клас Part с дефиниран оператор ``+`` и функция ``void read(ifstream& in_data)``.

Класовете ``Wheel(type, make)``, ``Engine(hp, make)``, ``Light(lm, make)``, ``Chassis(make)`` са наследници на ``Part``.

Задача 1. Да се направи клас ``Undercarriage``, наследник на ``Part``, който се състои 4 ``Wheel`` обекта и един ``Chassis`` обект.

Задача 2. Да се направи клас ``Vehicle``, наследник на ``std::vector``, който представлява полиморфен списък от един ``Undercarriage``, един ``Engine`` и 10 ``Lights``. Да се създадат два автомобила - един с двигател 100 к.с. със зимни гуми и един с 200 к.с. със шаси от Лада.

Задача 3. Спецификацията на отделните части да се прочете от следния файл:

```
W winter, michelin
E 100, renaut
L 2, philips
C honda
W summer, bridgestone
E 200, volvo
L 2, osram
C lada
```
