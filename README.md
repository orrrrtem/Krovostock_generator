Лучшие результаты продемонстрировала модель с архитектурой LSTM, hidden size=256, chunk=200, num_layers=2.

Стоит отметить, что она лучшая несмотря на смену датасетов, и языка. Однако, у архитектуры GRU есть преимущество, она быстрее тренируется. Что при реальном использовании архитектуры может дать выбор в ее пользу.

По поводу инференса - оптимальная температура 0.6-0.9.

Сгенерированный текст с оптимальным набором параметров - почти похож на реальный текст любой песни кровостока: "Россия радость наполнила рот, вот и всё приплыли. Раздевайся иди в душ помой пизду обнови потёкшую тушь гово....".
