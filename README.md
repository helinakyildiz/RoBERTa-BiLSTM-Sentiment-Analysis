# RoBERTa-BiLSTM-Sentiment-Analysis
RoBERTa-BiLSTM ile Twitter, IMDb ve Sentiment140 duygu analizi

RoBERTa tabanlı transformer ile BiLSTM katmanını birleştiren hibrit bir duygu analizi modeli.

## Veri Setleri
| Veri Seti | Boyut | Sınıf |
|---|---|---|
| Twitter US Airline | 14.640 tweet | Negatif / Nötr / Pozitif |
| IMDb | 50.000 yorum | Negatif / Pozitif |
| Sentiment140 | 1.6M tweet | Negatif / Pozitif |

## Sonuçlar
| Model | Doğruluk | F1 |
|---|---|---|
| Twitter Airline | ~%85 | ~%85 |
| IMDb | ~%92.36 | ~%92.35 |
| Sentiment140 | ~%82.25 | ~%82.25 |

## Kurulum
```bash
pip install transformers datasets torch scikit-learn pandas numpy matplotlib seaborn nlpaug
```

## Kullanım
Kaggle API key'ini ayarladıktan sonra Google Colab'da çalıştırın.
