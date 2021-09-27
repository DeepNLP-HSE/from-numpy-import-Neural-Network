# from numpy import Neural Network

В этой домашке есть две версии: простая и сложная. 
В обоих версиях вам нужно будет реализовать нейронную сеть на numpy. 
Простая версия отличается от сложной тем, что в ней нужно сделать это непосредственно в цикле обучения и для двух слоев, 
то есть нужно будет описать `forward`, `backward` и шаг оптимизации прямо в цикле. 
В сложной версии нужно будет проделать примерно тоже самое, но в классах. Эта домашка нужна для лучшего понимания, но она будет сложнее из-за использования классов и, возможно, пока непривычной форме с классами.
Абстракции в этой домашке будут очень полезны для понимания того, что происходит в торче. Эта домашка прокачает вас гораздо сильнее, но и выполнить ее будет труднее. Вам нужно будет описать несколько слоев: `Linear`, `ReLU`, `BCELoss`.  Реализация `Sigmoid` уже есть в `our_library.layers`. Реализовав слои выше вы сможете сделать n-слойную нейронную сеть с любым количеством слоев. Это получается за счет того, что вы описали всю необходимую логику:
- Как нужно обработать входные данные и передать их дальше;
- Принять градиент с последующего слоя, сделать `backward` для текущего слоя и передать градиент предыдущему слою;
- Как обновить веса, если в слоев есть обучаемые веса.

Присылайте свои недоделанные сложные домашки, пусть они не пойдут совсем в стол. Я или ассистенты посмотрят, мы обсудим и доделаем.  
Поверьте, эта домашка стоит того, чтобы ее сделать! Вы получите бОльший опыт, выполнив сложную. Но нет ничего страшного, если вы выбирите простую. 
У вас еще будет большое количество возможностей проявить себя.

# Установка сторонних библиотек
`pip install -r requirements.txt`

# Оценивание
Будет проверятся корректность логики обучения, 
будут даваться комментарии что нужно исправить, 
если домашка будет сдана вовремя. 
Грамотность и красота кода проверяться не будут.
Максимальный балл: 10.

# Дедлайн
18/10/2021  
Далее максимальный балл за работу: 7

# Важная просьба
Прежде чем отправить задание на проверку, очистите свой код от неиспользоваемого кода и неважных комментариев.
