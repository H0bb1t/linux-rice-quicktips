
##### Получить mime файла

```bash
xdg-mime query filetype <filename> # 2014-02-22-my_family_video.mkv -> video/x-matroshka
```

##### Получить текущее дефолтное приложение для типа

```bash
xdg-mime query default <mime> # video/x-matroshka -> mpv.desktop
```

##### Установить дефолтное приложение для типа

```bash
xdg-mime default <app> <mime(s)> # vlc.desktop video/x-matroshka
```
