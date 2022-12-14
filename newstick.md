## GIT. Создание новой ветки
---

### ***Ветвление***
Во время разработки новой функциональности считается хорошей
практикой работать с копией оригинального проекта, которую называют
веткой. Ветви имеют свою собственную историю и изолированные друг 
от друга изменения до тех пор, пока вы не решаете слить изменения 
вместе. Это происходит по набору причин:

* Уже рабочая, стабильная версия кода сохраняется.
* Различные новые функции могут разрабатываться параллельно разными 
программистами.
* Разработчики могут работать с собственными ветками без риска, что 
кодовая база поменяется из-за чужих изменений.
* В случае сомнений, различные реализации одной и той же идеи могут 
быть разработаны в разных ветках и затем сравниваться.

### ***Создание новой ветки***

Основная ветка в каждом репозитории называется *master*. Чтобы создать еще одну ветку, используем команду *branch*

```
$ git branch amazing_new_feature
```

Это создаст новую ветку, пока что точную копию ветки master.


---
### **Ваш прогресс по модулю " Инструкция по работе с GIT "**

![](./green_93DB70/80perc.png)

---
>[<<Назад](./startmenu5.md) [Далее>>](./switchsticl.md)   
