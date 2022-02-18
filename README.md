# Services
# Контрольные вопросы
## Когда происходит создание и удаление связанного сервиса?

Создание в функции - onCreate
Удаление в функции - onDestroy

## Какие методы жизненного цикла вызываются у сервиса и в какой последовательности?

1) onCreate()
2) onStartCommand()
3) onDestroy()

## Как соотносится ЖЦ активности и сервиса?
Так как сервисы не показываются на экране, следовательно для них отсутсвуют такие циклы как onPause, onRestart и подобные связанные с изменением актуальности активности. Соответственно остаются только onCreate(), onStartCommand(), onDestroy(), которые отоборажаю начало, конец работы.
