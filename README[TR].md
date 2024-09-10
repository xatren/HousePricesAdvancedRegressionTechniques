# Ames Housing Price Prediction

Bu proje, Kaggle'daki Ames Housing Price Prediction yarışması için bir çözümdür. Ames, Iowa'daki evlerin satış fiyatını, mülklerin çeşitli özelliklerine dayanarak tahmin etmek için machine learning teknikleri kullanır.

## Yarışma Açıklaması

Ames Housing dataset'i, Dean De Cock tarafından data science eğitiminde kullanılmak üzere derlenmiştir. Sıkça atıf yapılan Boston Housing dataset'inin modernize edilmiş ve genişletilmiş bir versiyonunu arayan data scientist'ler için muhteşem bir alternatiftir.

Ames, Iowa'daki konut evlerinin (neredeyse) her yönünü açıklayan 79 açıklayıcı değişken ile bu yarışma, sizleri her evin final fiyatını tahmin etmeye davet ediyor.

## Model Detayları

Bu çözüm, üç modelin ensemble'ını kullanır:

1. Random Forest
2. XGBoost
3. LightGBM

Preprocessing pipeline'ı eksik değerleri ele alır, sayısal özellikleri ölçeklendirir ve kategorik özellikleri one-hot encode eder.

## Değerlendirme

Yarışma, tahmin edilen değerin logaritması ile gözlemlenen satış fiyatının logaritması arasındaki Root-Mean-Squared-Error (RMSE) değerini kullanır.

## Katkıda Bulunma

Modeli veya kod yapısını geliştirmek için katkılarınızı bekliyoruz! Lütfen bir Pull Request göndermekten çekinmeyin.

## Lisans

Bu proje açık kaynaklıdır ve [MIT Lisansı](LICENSE) altında kullanılabilir.
