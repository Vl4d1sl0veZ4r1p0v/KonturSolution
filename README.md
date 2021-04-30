# KonturSolution

Зарипов Владислав Радиславович

## Задача

Данная модель подразумевает решение задачи [TrueCasing](https://en.wikipedia.org/wiki/Truecasing)


## Модель
- За основу использована state-of-the-art [модель](https://github.com/raymondhs/pytorch-char-rnn-truecase), с использованием [RNN](https://en.wikipedia.org/wiki/Recurrent_neural_network) и [LSTM](https://en.wikipedia.org/wiki/Long_short-term_memory) сетей
- В подходе использован метод токенизации по отдельным символам(или n-граммам: 1-граммы)

_В отличии от метода токенизации по словам, данный больше подходит для решения задачи TrueCasing(это было описано в статьях)_

## Arknowledgements

В ходе решения были использованы следующие статьи:
- https://arxiv.org/abs/1912.07095
- https://arxiv.org/abs/2007.02025
- https://arxiv.org/pdf/2002.00738.pdf