# YDS22-ml-task
How you should not solve machine learning task in YDS entrance contest

Задача С во вступительном контесте ШАД 2022:


Исследуя руины исчезнувшей цивилизации, археолог Азат обнаружил таблички, на которых записаны тексты древних заклинаний, а также для каждого из них дано вещественное число — оценка колдовской силы. Азату стало интересно, от чего зависит колдовская сила, и он решил определить это с помощью анализа данных. Помогите ему, создав модель, предсказывающую по заклинанию его силу.

О датасете
Все данные можно скачать по этой [https://disk.yandex.ru/d/CbUbRFHXy7jHLw](ссылке).
Вам предоставляется три файла: train.txt, train_ans.txt и test.txt. В каждой строке файлов train.txt и test.txt записан набор символов — текст заклинания (одна строка — одно заклинание, пробелы также входят в заклинание). В каждой строке файла train_ans.txt записано одно вещественное число — таргет для соответствующего заклинания из обучающей выборки (в i-й строке таргет для i-го заклинания).

Что нужно сделать
Вы должны загрузить в систему файл submitted_answers.txt, в каждой строке которого записан предсказанный таргет для соответствующего заклинания из тестовой выборки. Таким образом, в файле должно быть 100 строк, в каждой из которых записано одно вещественное число.
Ваша посылка будет автоматически забракована (вы получите за неё ноль баллов), если число предсказаний в файле отлично от 100;
Ваша оценка в этой задаче будет вычисляться как
min(2, (8 - RMSE) / (1.75))
где RMSE — значение корня из среднеквадратичного отклонения предсказания от истинных таргетов на тестовой выборке.

