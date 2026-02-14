TR:

Düzenlileştirme Teknikleri (Ridge, Lasso & ElasticNet)
Bu proje, regresyon modellerinde aşırı öğrenmeyi (overfitting) önlemek ve modelin genelleyebilirliğini artırmak amacıyla kullanılan "Cezalandırılmış Regresyon" (Penalized Regression) yöntemlerine odaklanmaktadır.

Neler Yapıldı?

Veri Seti: Algerian Forest Fires veri seti kullanılarak gerçek dünya verileri üzerinde analiz yapıldı.

Ridge Regresyon (L2): Tüm değişkenleri modelde tutarak katsayıları sıfıra yaklaştıran ve varyansı azaltan teknik uygulandı.

Lasso Regresyon (L1): Gereksiz özniteliklerin katsayılarını tam sıfır yaparak "Öznitelik Seçimi" (Feature Selection) sağlayan yöntem incelendi.

ElasticNet: Ridge ve Lasso'nun güçlü yanlarını birleştiren hibrit yaklaşım denendi.

Model Kıyaslama: LazyRegressor kütüphanesi kullanılarak onlarca farklı regresyon modelinin performans metrikleri (R2, RMSE vb.) hızlıca karşılaştırıldı.

ENG:
Regularization Techniques (Ridge, Lasso & ElasticNet)
This project focuses on "Penalized Regression" methods used to prevent overfitting and enhance the generalizability of machine learning models.

Key Features:

Dataset: Analyzed real-world trends using the Algerian Forest Fires dataset.

Ridge Regression (L2): Implemented to reduce variance by shrinking coefficients towards zero while keeping all variables in the model.

Lasso Regression (L1): Explored for its "Feature Selection" capability by shrinking the coefficients of less important features to exactly zero.

ElasticNet: Applied a hybrid approach that combines the strengths of both Ridge and Lasso.

Model Benchmarking: Utilized the LazyRegressor library to rapidly compare performance metrics (R2, RMSE, etc.) across various regression algorithms.
