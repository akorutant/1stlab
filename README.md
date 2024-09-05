# Лабораторная работа №1

## 1. Создание файлов двумя способами:
```bash
    echo Hello World! > helloworld.txt
    type nul > helloworld1.txt
```

## 2. Теперь скопируем файлы четыремя способами:
```bash
    copy C:\Users\student\Documents\helloworld.txt C:\Users\student\Desktop\

    xcopy C:\Users\student\Documents\helloworld1.txt C:\Users\student\Desktop\ /Y

    robocopy . helloworddir helloworldnew.txt

    type helloworld.txt > helloworldagain.txt
```

## 3. Сейчас мы переименуем файлы двумя способами:
```bash
    ren helloworld.txt nohello.txt
    
    move helloworldnew.txt helloworldovernew.txt
```

## 4. Переместим файлы двумя способами:
```bash
    move helloworldagain.txt C:\Users\student\Desktop\helloworddir

    robocopy . C:\Users\student\Desktop\helloworddir helloworlddesk.txt /MOV
```

## 5. Удаляем файлы 3 способами:
```bash
    del helloworld.txt

    erase helloworldovernew.txt

    rmdir /s /q helloworddir
```


    
