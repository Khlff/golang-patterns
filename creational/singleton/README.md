## Одиночка (Singleton)

Паттерн контролирует создание единственного экземпляра некоторого класса и предоставляет доступ к нему.  
Другими словами, Singleton гарантирует, что у класса будет только один экземпляр и предоставляет к нему точку доступа, через фабричный метод.  
  
Требуется для реализации:

1. Функция GetInstance, создающая экземпляр класса Singleton только один раз. Если до этого экземпляр уже был создан, то просто возвращает этот экземпляр.
