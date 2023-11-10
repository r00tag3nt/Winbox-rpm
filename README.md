# Winbox-rpm

**Файл spec для створення RPM та встановлення winbox на Fedora через WINE**

Встановіть інструменти fedora-packager і fedora-review:

`# dnf install fedora-packager fedora-review`

Додайте себе до групи mock:

`# usermod -a -G mock $USER`

Виконайте команду git clone

`git clone https://github.com/r00tag3nt/Winbox-rpm.git && cd Winbox-rpm`

Запустіть збірку, введіть таку команду:

`fedpkg --release f39 local`
