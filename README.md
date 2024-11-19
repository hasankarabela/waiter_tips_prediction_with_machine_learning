# waiter_tips_prediction_with_machine_learning
Libraries Used:

pandas: For data manipulation and analysis.
plotly: For data visualization.
scikit-learn: For machine learning models and data preprocessing.
numpy: For mathematical operations and array manipulation.
Steps:

Loading and Displaying Data: Data is loaded from the restaurant_data.csv file. The first few rows of the dataset are displayed.

Data Visualization:

A scatter plot is created to show the relationship between total_bill and tip. Different colors represent different days of the week.
Pie charts are created to show the distribution of tips by categories like sex, smoker status, and meal time (Lunch/Dinner).
Data Preprocessing:

Categorical variables like sex, smoker, day, and time are converted into numerical values.
Model Training and Prediction:

A linear regression model (LinearRegression) is trained using features like total_bill, sex, smoker, day, time, and size.
The model is then used to predict the tip amount based on the provided features.

Türkçe Açıklama:
Kullanılan Kütüphaneler:

pandas: Veri manipülasyonu ve analizi için kullanılır.
plotly: Verilerin görselleştirilmesi için kullanılır.
scikit-learn: Makine öğrenmesi modelleri ve veri ön işleme adımları için kullanılır.
numpy: Matematiksel işlemler ve dizi manipülasyonu için kullanılır.
Adımlar:

Veri Yükleme ve Görüntüleme: Veriler, restaurant_data.csv dosyasından yüklenir. İlk başta veri setinin ilk birkaç satırı görüntülenir.

Veri Görselleştirme:

total_bill (toplam hesap) ve tip (bahşiş) arasındaki ilişkiyi gösteren bir scatter plot (dağılım grafiği) çizilir. Farklı günler için renkler farklıdır.
Bahşişin, cinsiyet, sigara içme durumu ve yemek saati (Öğle/Dinlenme) gibi kategorilere göre dağılımını gösteren pasta grafikler oluşturulur.
Veri Ön İşleme:

sex (cinsiyet), smoker (sigara içme durumu), day (gün) ve time (yemek saati) gibi kategorik değişkenler sayısal verilere dönüştürülür.
Model Eğitimi ve Tahmin:

total_bill, sex, smoker, day, time ve size gibi özellikleri kullanarak bir doğrusal regresyon modeli (LinearRegression) eğitilir.
Model, verilen özelliklerle bir bahşiş tahmini yapar.
