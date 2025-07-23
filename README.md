## Команды для работы с subtree

- Добавить ссылку на удалённый репозиторий:
```
git remote add glfw https://github.com/glfw/glfw.git
```

- Добавить subtree: 
```
git subtree add --prefix=external/glfw glfw master --squash`
```

- Обновить subtree: 
```
git subtree pull --prefix=external/glfw glfw master --squash`
```