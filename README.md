# autobr_femcorpus

Это корпус феминистских постов в VK из двух пабликов (https://vk.com/socfem - Soc-Fem, https://vk.com/radfemtranslations - radfem translations).

Общий объём - ... слов.

Файл со всей программой - NLP_project.

Чтобы вам не пришлось ждать, пока загрузятся посты из vk, произойдёт морфологический анализ и соберутся все необходимые датасеты, вы можте сразу воспользоваться таблицами из файлов sentenses.tsv, uni_df.tsv, bi_df.tsv, tri_df.tsv.




Как проводить поиск? 

- “слово” - поиск по словоформе

- слово - поиск по всем формам слова

- тег - поиск по тегу - части речи (см. POSтеги pymorphy https://pymorphy2.readthedocs.io/en/stable/user/grammemes.html)

- “слово”+тег - поиск по словоформе с этим тегом

- слово+тег - поиск по всем формам слова с этим тегом


Также можно искать биграммы и триграммы.

Для каждого из слов доступны все пять вариантов (между словами пробел).
