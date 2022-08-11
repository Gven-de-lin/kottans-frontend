## Git Bash

Продовжую своє знайомство з git, лекційний матеріал та тестові завдання на coursera це дійсно крута ідея. Маю великі надії на цей курс, далі більше.

diff - show changes between commits, commit and working tree, etc

git clone - clone a repository into a new directory

git init - create an empty Git repository or reinitialize an existing one

git add - add file contents to the index

git commit - record changes to the repository

git push - update remote refs along with associated objects

git status - show the working tree status

git log - show commit logs

git config - get and set repository or global options

git commit -a - Stages files automatically

git show - Shows various objects

git diff --staged - An alias to --cached, this will show all staged files compared to the named commit

git add -p - Allows a user to interactively review patches to add to the current commit

git mv - Similar to the Linux `mv` command, this moves a file

git rm - Similar to the Linux `rm` command, this deletes, or removes a file

## Linux CLI, and HTTP
Знайомство з  Command line Linux пройшло успішно. З Command line Linux раніше не працювала, тому більшість команд нові, але дуже схожі схожі на команди з Git Bash.(можливо це одней й те саме, але з різним інтерфейсом?) Фундаментальні знання, які допомагають працювати з проектом. Цей факт було перевірено під час створення особистого навчального проекта "NFTHERO". Він ще в процесі, тому команди використовую щоб запушити зміни.
Впевненна що ці знання допоможуть мені у найближчему майбутньому.
![image](https://user-images.githubusercontent.com/105444704/180610875-6b1869d4-4a48-4803-ad17-8138d9fc965f.png)
![image](https://user-images.githubusercontent.com/105444704/180610930-f24cf2ac-210b-4db6-a7b9-77dbac914047.png)
![image](https://user-images.githubusercontent.com/105444704/180610967-e72483eb-cccc-4069-b995-20fe50dddd91.png)
![image](https://user-images.githubusercontent.com/105444704/180611029-2402406e-9da6-45d9-9ac1-e71074e2fd97.png)

Стосовно HTTP:
1. Що було новим
    - протокол HTTP вважається протоколом без запам'ятовування стану
    - TCP/IP гарантує доставку переданих пакетів даних у потрібній послідовності, але трафік у цьому разі  може бути дуже нерівномірний, тому що пакети зазнають             усіляких затримок), проте може використовуватися будь-який інший придатний для транспортування повідомлень механізм (* наприклад, QUIC (Quick UDP Internet             Connections) –  експериментальний інтернет-протокол, розроблений Google в кінці 2012 року)
    - HTTP/1.1 тривалі з'єднання (* persistent connections; передавання в одному TCP-з'єднанні декількох об'єктів), кодування передавання даних типу  "chunked" (*           частинами) (* chunked transfer-coding; механізм передавання даних у протоколі передавання гіпертексту (HTTP), що дозволяє надійно доставляти дані від сервера           клієнту без необхідності знати точний розмір усього тіла HTTP-повідомлення заздалегідь.
    - У специфікації HTTP визначається наступна загальна структура повідомлень запиту та відповіді:
      message = <start-line>
          *(<message-header>)
          CRLF
          [<message-body>]
 
<start-line> = Request-Line | Status-Line 
<message-header> = Field-Name ':' Field-Value



