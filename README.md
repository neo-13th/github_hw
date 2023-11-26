# github_hw  

Что нужно сделать:

Зарегистрируйте аккаунт на GitHub.  
Создайте новый отдельный публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README».  
![g1](https://github.com/neo-13th/github_hw/assets/150372172/097e9d22-9cdf-4a7c-97ca-2b344dcc508e)  
Склонируйте репозиторий, используя https протокол git clone ....  
![g2](https://github.com/neo-13th/github_hw/assets/150372172/0136d61d-433d-4853-9c42-e30ee7d92970)
Перейдите в каталог с клоном репозитория.  
![g3](https://github.com/neo-13th/github_hw/assets/150372172/53b64b37-9b57-4260-984a-0a3b286eea6c)  
Произведите первоначальную настройку Git, указав своё настоящее имя и email: git config --global user.name и git config --global user.email johndoe@example.com.  
![g4](https://github.com/neo-13th/github_hw/assets/150372172/87c65366-b4d7-4909-a623-3c4e74263cff)  
Выполните команду git status и запомните результат.
![g5](https://github.com/neo-13th/github_hw/assets/150372172/363c44f1-4610-4be8-aff9-6e5a1b9467cd)  
Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.  
![g6](https://github.com/neo-13th/github_hw/assets/150372172/7456a43b-136a-4ab6-9140-b676b39a5673)  
Ещё раз выполните git status и продолжайте проверять вывод этой команды после каждого следующего шага.  
Посмотрите изменения в файле README.md, выполнив команды git diff и git diff --staged.  
![g7](https://github.com/neo-13th/github_hw/assets/150372172/ebb4d80e-5a4a-4cc9-b9f9-0a48ff9cc64d)  
Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой git add README.md.  
Ещё раз выполните команды git diff и git diff --staged.  
Теперь можно сделать коммит git commit -m 'First commit'.  
![g8](https://github.com/neo-13th/github_hw/assets/150372172/f7edd39f-8b78-461d-ae55-1193389d1df6)  
Сделайте git push origin master.  
![g9](https://github.com/neo-13th/github_hw/assets/150372172/048618f1-4cf3-43e9-978f-af64a785259f)  
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.  
https://github.com/neo-13th/hw8.01/commit/d9c206d744fe68d82f0208ef47a08b2e3912a118  

Задание 2  
Что нужно сделать:  
Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.  
Добавьте файл .gitignore в следующий коммит git add....  
Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.  
![g2 1](https://github.com/neo-13th/github_hw/assets/150372172/c74748b8-8177-4e80-97c7-4ef89fd20bad)
Сделайте коммит и пуш.  
![g9 2](https://github.com/neo-13th/github_hw/assets/150372172/4618802c-8579-4542-96b5-c4e076fc34a5)  
В качестве ответа добавьте ссылку на этот коммит в ваш md-файл с решением.  
https://github.com/neo-13th/hw8.01/commit/e2745b1d253eb071c09be0e5eaf0faa940dab4f7  

Задание 3  
Что нужно сделать:  

Создайте новую ветку dev и переключитесь на неё.  
Создайте в ветке dev файл test.sh с произвольным содержимым.  
Сделайте несколько коммитов и пушей в ветку dev, имитируя активную работу над файлом в процессе разработки.  
Переключитесь на основную ветку.  
Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev ветке.  
Сделайте мердж dev ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.  
Сделайте пуш в основной ветке.  
Не удаляйте ветку dev.  
![g2](https://github.com/neo-13th/github_hw/assets/150372172/f028f3c9-a803-4bc4-8ba0-2c6cd5aa512f)  
![g3](https://github.com/neo-13th/github_hw/assets/150372172/9698d656-5f06-4eab-9f68-38e0bfe08823)  
https://github.com/neo-13th/github_hw/network
