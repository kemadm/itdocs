---
title: Разрешение на монтирование без root
layout: default
parent: Astra Linux
grand_parent: Домашняя страница
---

# Добавление в группы

Для того чтобы разрешить пользователю без root прав монтировать DVD и USB накопители, необходимо добавить его в соответствующие группы:

1. `usermod -aG floppy <имя_пользователя>`
2. `usermod -aG cdrom <имя_пользователя>`
