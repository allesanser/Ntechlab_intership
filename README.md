# Ntechlab_intership
Task from the qualifying stage to the internship

* max_sub.py - скрипт содержащий функцию с решением алгоритмической задачи  
возвращает подмассив с максимальной суммой.

* gender.py - скрипт, предсказывающий пол для картинок, которые передаются  
ему. Параметром получает адрес директории с картинками. В самом скрипте,  
в строке model = torch.load('entire_model.pt',DEVICE) необходимо указать  
название/путь к файлу с весами. Возвращает json файл с предсказаниями в   
формате: {'img0001.jpg': "female", ....}  
Чтобы его запустить необходимо прописать команду python gender.py /название  
директории, в которой хранятся картинки

* process_results.json - пример выходного файла

* Ntechlab.ipynb - ноутбук с обучением модели. В ноутбуке необходимо указать  
путь к зархивированному файлу. [Здесь](https://drive.google.com/drive/folders/1oWKDN3bh5ryfItMW1EmtkhQ7r_YfiCSN?usp=sharing) лежат предобученные модели.  
entire_model_152.pt - Предобученный ResNet152 с добавочными слоями, entire_model_50.pt - ResNet50  
simple_model.pt - нейросеть собственной сборки.


