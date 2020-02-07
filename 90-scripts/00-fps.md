# FPS
## Голова постоянно кружится.

Spin.cs

    public float speed = 3.0f;

    void Update()
    {
        transform.Rotate(0, speed, 0);
    }

* transform - класс преобразования
* Rotate - метод
* 0, speed, 0 - постоянно менять свойство `Y`
* public свойства появляются во вкладке Инспектор

## Обзор с помощью мыши

MouseLook.cs