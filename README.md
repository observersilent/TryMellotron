![Mellotron](mellotron_logo.png "Mellotron")

### Я менял данные только в
1) text/cmudict.py сдесь я заменил valid_symbols на те что используются в russian_g2p
2) text/symbols.py поменял _letters на русские буквы
3) еще немного поменял hparams.py. Выставил cmudict_path=None т.к. у нас уже фонемы используются. Поставил text_cleaners=['basic_cleaners'] вместо english_cleaners.
поменял sampling_rate=22050, n_speakers=1 т.к. у нас один спикер в руслане, снизил batch_size=12 с 48. Больше ничего не менял.
 
