## Инструкция по работе с удалённым репозиторием

### Шаг №1

* Первое, что вам нужно сделать - это [скачать и установить Git](https://git-scm.com/downloads) на ваш компьютер.
* Зарегистрироваться на сайте [Github.com](https://github.com/)

> Далее мы рассмотрим несколько вариантов работы с удалёнными репозиториями

Изначально посмотрим, как же нам создать свой репозиторий на Гитхаб, с которым мы сможем работать самостоятельно и также выбирать, сможет ли кто-то другой работать с ним или же это будет ваш личный проект.

Для того, чтобы создать новый репозиторий, зайдите в ваш профиль на Гитхаб, выберите владку <span style ='color: yellow;'>*Repositories*</span> и нажмите на зелёную кнопку <span style='color:green;'>NEW</span>

В открышвемся окне перед вами будет форма, которую нужно будет заполнить. Написать название вашего репозитория, выбрать доступ: <span style =color:green;>Public</span>, если вы хотите, чтобы вашу работу могли посмотреть все или <span style = color:red>Private</span>, если вы работаете над ним один. После этго жмём кнопку <span style = color:green>Create repository </span>

Перед вами откроется новое окно, в котором будет два выбора:
1. Комманда ввода в терминале для создание нового репозитория
2. И комманда для загрузки уже существующего у вас на компьютере локального репозитория

````
…or create a new repository on the command line
echo "# Home-work-test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/profileName/<name>.git
git push -u origin main
````
````
…or push an existing repository from the command line
git remote add origin https://github.com/profileName/<name>.git
git branch -M main
git push -u origin main
````
Выбираем то, что для нас подхоит больше и вставляем этот код в наше терминал. Готово!



 > <span style=color:green;>Поздравляю, вы создали свой первый удалённый репозиторий! 
````java
Class Red {
    int x = 12;
string word = "It's cool";
}
````
| 1 | 2 |    3    |
|---|---|:-------:|
|One|Two|  Three  |



