# Final-Project-Byte-Blazers - Stage 3
Final Project Kelompok 4

Stage - 3
**Summary**
Analisis dan kesimpulan hasil evaluasi metrics recall Model:

Random Forest:
● Recall : 0.52
● Dengan penanganan class imbalance, terjadi peningkatan
signifikan pada recall dari model ini. Penanganan class
imbalance dapat membantu model untuk lebih baik dalam
mengidentifikasi kasus positif.

Logistic Regression:
● Recall: 0.38
● Model ini menunjukkan bahwa penanganan class imbalance
tidak memberikan dampak yang signifikan pada kemampuan
model untuk mengidentifikasi kasus positif.

Decision Tree:
● Recall: 0.41
● Penanganan class imbalance tidak menghasilkan perubahan
yang signifikan dalam recall model Decision Tree.

Gradient Boosting:
● Recall: 0.49
● Model ini menunjukkan hasil yang stabil, tanpa perubahan
yang signifikan setelah penanganan class imbalance. Recall
yang relatif tinggi menunjukkan bahwa model ini mungkin
sudah cukup baik dalam mengidentifikasi kasus positif.

Kesimpulan: Penanganan class imbalance membantu meningkatkan recall pada
beberapa model seperti Random Forest, tetapi tidak memberikan perubahan yang
signifikan pada model lainnya seperti Logistic Regression dan Decision Tree. Model Gradient
Boosting menunjukkan kinerja yang stabil tanpa banyak perubahan setelah penanganan
class imbalance.

Dari hyperparameter tuning yang telah dilakukan, didapatkan hasil:
>- Random Forest menunjukkan
peningkatan dalam beberapa metrics
evaluasi, termasuk akurasi (0.7640),
presisi (0.8475), dan F1-Score (0.6289),
dan recall (0.5000)

>- Setelah tuning, model Random Forest
menunjukkan peningkatan dalam
beberapa metrik evaluasi, termasuk
akurasi (0.7640), presisi (0.8475),
F1-score (0.6289), dan recall (0.5000).

>- Hasil ini menunjukkan bahwa
penanganan hyperparameter berhasil
meningkatkan kinerja model Random
Forest secara signifikan, terutama
dalam hal mengidentifikasi kasus
positif.

Learning Curve:
Dilakukan learning curve untuk mengetahui nilai optimal dari fungsi model yang telah dibuat

● Akurasi training data meningkat drastis pada titik awal,
walaupun berkurang sedikit sehingga stabil pada titik sekitar
0,90 hal ini menunjukkan bahwa model dapat mengambil
konsisten dari data train.

● Sedangkan akurasi test data meningkat secara perlahan
seiring dengan peningkatan akurasi training data, tetapi
kemudian stabil pada titik sekitar 0,85. Hal ini menunjukkan
bahwa model memiliki performa yang baik pada data uji, tetapi
dapat menunjukkan tanda overfitting pada titik lebih tinggi.

● Selisih antara akurasi training data dan test data menunjukkan
bahwa model memiliki sedikit overfitting pada titik lebih tinggi.
Namun, selisih tersebut tidak terlalu besar, sehingga model
masih memiliki performa yang baik pada data uji.
