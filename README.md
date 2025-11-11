# 🩺 Diabetes Dataset AdaBoost Classifier and Regressor Study

## 📋 Project Overview / Proje Genel Bakış

**English:** This project presents a comprehensive machine learning analysis of the diabetes dataset using AdaBoost algorithms as the primary focus. The study includes both classification and regression tasks, comparing AdaBoost performance with other popular algorithms.

**Türkçe:** Bu proje, AdaBoost algoritmalarını ana odak noktası olarak kullanarak diabetes veri seti üzerinde kapsamlı bir makine öğrenmesi analizi sunmaktadır. Çalışma hem sınıflandırma hem de regresyon görevlerini içermekte ve AdaBoost performansını diğer popüler algoritmalarla karşılaştırmaktadır.

## 🎯 Objectives / Amaçlar

### English:
- **Primary Goal:** Implement and evaluate AdaBoost Classifier for diabetes prediction
- **Secondary Goals:** 
  - Compare different data preprocessing approaches (median imputation vs. row deletion)
  - Implement AdaBoost Regressor for glucose level prediction
  - Compare AdaBoost performance with other ML algorithms
  - Analyze feature importance and model interpretability

### Türkçe:
- **Ana Hedef:** Diabetes tahmini için AdaBoost Classifier uygulama ve değerlendirme
- **İkincil Hedefler:**
  - Farklı veri ön işleme yaklaşımlarını karşılaştırma (median doldurma vs. satır silme)
  - Glucose seviyesi tahmini için AdaBoost Regressor uygulama
  - AdaBoost performansını diğer ML algoritmalarıyla karşılaştırma
  - Özellik önem derecesi ve model yorumlanabilirliği analizi

## 📊 Dataset Information / Veri Seti Bilgileri

**English:**
- **Source:** Pima Indians Diabetes Database
- **Samples:** 768 instances
- **Features:** 8 medical predictor variables
- **Target:** Binary classification (0: Non-diabetic, 1: Diabetic)
- **Challenge:** Missing values represented as zeros in medical measurements

**Türkçe:**
- **Kaynak:** Pima Indians Diabetes Veritabanı
- **Örnekler:** 768 örnek
- **Özellikler:** 8 tıbbi tahmin değişkeni
- **Hedef:** İkili sınıflandırma (0: Diyabet değil, 1: Diyabet)
- **Zorluk:** Tıbbi ölçümlerde sıfır olarak temsil edilen eksik değerler

### Features / Özellikler:
1. **Pregnancies** - Number of pregnancies / Hamilelik sayısı
2. **Glucose** - Plasma glucose concentration / Plazma glucose konsantrasyonu
3. **BloodPressure** - Diastolic blood pressure / Diyastolik kan basıncı
4. **SkinThickness** - Triceps skin fold thickness / Triceps cilt kıvrım kalınlığı
5. **Insulin** - 2-Hour serum insulin / 2 saatlik serum insulin
6. **BMI** - Body mass index / Vücut kitle indeksi
7. **DiabetesPedigreeFunction** - Diabetes pedigree function / Diabetes soy ağacı fonksiyonu
8. **Age** - Age in years / Yaş

## 🔬 Methodology / Metodoloji

### English:

#### 1. **Data Preparation**
- Exploratory Data Analysis (EDA)
- Missing value detection and analysis
- Data visualization and correlation analysis

#### 2. **Data Preprocessing Approaches**
- **Approach A:** Median imputation for zero values
- **Approach B:** Row deletion for problematic zeros
- Feature standardization using StandardScaler

#### 3. **Classification Analysis**
- AdaBoost Classifier implementation
- Comparison with: Random Forest, KNN, SVM, Decision Tree
- Performance evaluation using accuracy, precision, recall, F1-score
- Cross-validation for model stability assessment

#### 4. **Regression Analysis**
- AdaBoost Regressor for glucose prediction
- Comparison with: Random Forest, KNN, SVR, Decision Tree, Linear Regression
- Performance evaluation using MSE, RMSE, MAE, R²

#### 5. **Model Interpretation**
- Feature importance analysis
- Model performance comparison
- Results visualization and interpretation

### Türkçe:

#### 1. **Veri Hazırlama**
- Keşifsel Veri Analizi (EDA)
- Eksik değer tespiti ve analizi
- Veri görselleştirme ve korelasyon analizi

#### 2. **Veri Ön İşleme Yaklaşımları**
- **Yaklaşım A:** Sıfır değerler için median doldurma
- **Yaklaşım B:** Problemli sıfırlar için satır silme
- StandardScaler kullanarak özellik standardizasyonu

#### 3. **Sınıflandırma Analizi**
- AdaBoost Classifier uygulaması
- Karşılaştırma: Random Forest, KNN, SVM, Decision Tree
- Doğruluk, kesinlik, duyarlılık, F1-skoru ile performans değerlendirmesi
- Model kararlılığı için çapraz doğrulama

#### 4. **Regresyon Analizi**
- Glucose tahmini için AdaBoost Regressor
- Karşılaştırma: Random Forest, KNN, SVR, Decision Tree, Linear Regression
- MSE, RMSE, MAE, R² ile performans değerlendirmesi

#### 5. **Model Yorumlama**
- Özellik önem derecesi analizi
- Model performans karşılaştırması
- Sonuçların görselleştirilmesi ve yorumlanması


## 📈 Key Results / Ana Sonuçlar

### English:
- **Data Quality:** Identified significant missing values (represented as zeros) in medical measurements
- **Preprocessing Impact:** Comparison between median imputation and row deletion approaches
- **AdaBoost Performance:** Achieved competitive results in both classification and regression tasks
- **Algorithm Comparison:** Comprehensive evaluation against 5 different ML algorithms
- **Feature Importance:** Identified most influential features for diabetes prediction

### Türkçe:
- **Veri Kalitesi:** Tıbbi ölçümlerde önemli eksik değerler (sıfır olarak temsil edilen) tespit edildi
- **Ön İşleme Etkisi:** Median doldurma ve satır silme yaklaşımları arasında karşılaştırma
- **AdaBoost Performansı:** Hem sınıflandırma hem de regresyon görevlerinde rekabetçi sonuçlar elde edildi
- **Algoritma Karşılaştırması:** 5 farklı ML algoritmasına karşı kapsamlı değerlendirme
- **Özellik Önemi:** Diabetes tahmini için en etkili özellikler belirlendi

## 📊 Visualizations / Görselleştirmeler

The notebook includes comprehensive visualizations:
- Data distribution analysis
- Correlation matrices
- Performance comparison charts
- Confusion matrices
- Feature importance plots
- Regression analysis plots

Notebook kapsamlı görselleştirmeler içerir:
- Veri dağılım analizi
- Korelasyon matrisleri
- Performans karşılaştırma grafikleri
- Karışıklık matrisleri
- Özellik önem grafikleri
- Regresyon analizi grafikleri

## 🎓 Educational Value / Eğitim Değeri

### English:
This project serves as an excellent educational resource for:
- Understanding AdaBoost algorithm implementation
- Learning data preprocessing techniques
- Comparing different ML algorithms
- Model evaluation and interpretation
- Handling real-world data challenges

### Türkçe:
Bu proje şunlar için mükemmel bir eğitim kaynağı olarak hizmet eder:
- AdaBoost algoritması uygulamasını anlama
- Veri ön işleme tekniklerini öğrenme
- Farklı ML algoritmalarını karşılaştırma
- Model değerlendirme ve yorumlama
- Gerçek dünya veri zorluklarıyla başa çıkma

