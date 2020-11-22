# Кодовые домашние задания по курсу АНД
Домашние задания в которых что-то обучалось/писался код по курсу "Анализ неструктурированных данных" кафедры АЯ факультета ВМК МГУ https://moodle.cs.msu.ru/course/view.php?id=105

## Статистический анализатор текста

[Анализ некоторых статистических метрик с GUI в браузере](https://github.com/s1m0000n/text-stats-rus)

## Обучение классификатора разными методами

По сути получилось 2 метода решения задачи Sentiment Analysis.

Выбранный датасет - русские твиты с метками об их окрашенности: https://study.mokoron.com/

1. Эмбеддинги RuBERT + LinearSVM
2. Finetuning RuBERT + линейный слой

Подробнее и результаты см. в Classifier_Results.md  
TLDR: BERT+Linear NN > BERT + Linear SVM, но очень близко

Ноутбуки: SentimentSVM, SentimentFinetune  
[Colab SVM](https://colab.research.google.com/drive/1YNBVBHDsTRsBFqFmrBNXO7U5ui4nuCbC?usp=sharing), [Colab Finetune](https://colab.research.google.com/drive/1p8El-WsGPZ7f60Z3984u2v0QJzTSM1UT?usp=sharing)

## Кластеризация

TODO
