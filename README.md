# test-libft #

#### К сожалению, тест нормально работает только на маке ####

```
git clone https://github.com/saugustu42/test-libft.git
```
```
cd test-libft
```
склонируйте свой репозиторий, вызвав мой скрипт с аргументом ссылки на ваш репозиторий:
```
./clone.sh YOUR-GIT-REPO
```
теперь вы можете юзать команды мейка



### Помните, что тесты, написанные другими пирами, носят рекомендательный характер и не идеальны ###
_______________________________________________________________
ответственность за код ревью пира лежит на вас и только на вас
_______________________________________________________________

прогон нормы:
```
make norm
```
компилит вашу либу и запускает на ней мои тестовые кейсы:
```
make run-my-test
```
клонит либфтест, подменяет в нем grademe.sh и прогоняет тест:
```
make run-libftest
```
клонит юнит тест, подменяет в нем мейфайл на нужный и прогоняет тест:
```
make run-unit
```
ищет в коде либы забытые принтфы. (если греп вернет error 1, значит всё чисто)
```
make grep-printf
```
ищет в коде маллоки (в выдаче есть названия файлов, соответственно, можно проверить, не юзает ли пир маллок там где он запрещен)
```
make grep-malloc
```
