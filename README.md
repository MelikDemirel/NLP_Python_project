# NLP_Python_project
Language model that detects whether the sentence entered by the user is positive or negative / kullanıcı tarafında girilen cümlenin olumlu mu olumsuz mu olduğunu tespit eden dil modeli

<html>
<head>
    <title>Sentiment Analysis with Language Model</title>
</head>
<body>
    <h1>Sentiment Analysis with Language Model</h1>
    <p>This project includes a language model that analyzes sentences entered by the user to determine whether the sentence is positive or negative. The model involves cleaning and preprocessing text data, creating and training an artificial neural network using TensorFlow and other relevant libraries.</p>
    
    <h2>Used Libraries</h2>
        <li>pandas: Used for data processing and manipulation.</li>
        <li>BeautifulSoup: Used to clean HTML tags from text data.</li>
        <li>tqdm: Used to create progress bars and track the progress of operations.</li>
        <li>scikit-learn: Used to split the dataset into training and testing data.</li>
        <li>TensorFlow: Used to create, compile, and train the artificial neural network model.</li>

    <h2>Project Steps</h2>
        <li><strong>Data Loading and Cleaning:</strong> The dataset is loaded from an Excel file, and HTML tags are removed.</li>
        <li><strong>Preprocessing:</strong> After cleaning the text data, words are represented numerically and transformed into a DataFrame.</li>
        <li><strong>Label Preparation:</strong> Sentence labels are organized and transformed into numerical values for positive and negative sentiment.</li>
        <li><strong>Data Splitting:</strong> The dataset is split into training and testing data.</li>
        <li><strong>Model Creation:</strong> An artificial neural network model is constructed, comprising an input layer, hidden layers, and an output layer.</li>
        <li><strong>Model Compilation:</strong> The model is compiled, and optimization and loss functions are defined for the training process.</li>
        <li><strong>Model Training:</strong> The model is trained using the training data.</li>
        <li><strong>Prediction and Results:</strong> A sentence is taken from the user, cleaned, and a prediction is made using the model. Based on the prediction, it is determined whether the sentence is positive or negative.</li>
    
    <p>For more information about the project, please refer to the code file and comments. Enjoy exploring the project!</p>
</body>

<head>
    <title>Dil Modeli ile Duygu Analizi</title>
</head>
<body>
    <h1>Dil Modeli ile Duygu Analizi</h1>
    <p>Bu proje, kullanıcı tarafından girilen cümleleri analiz ederek cümlenin olumlu mu yoksa olumsuz mu olduğunu belirleyen bir dil modelini içermektedir. Model, metin verilerini temizleme ve önişleme işlemleri yapmak, TensorFlow ve diğer ilgili kütüphaneler kullanarak yapay sinir ağı modeli oluşturma ve eğitme işlemlerini içermektedir.</p>
    
    <h2>Kullanılan Kütüphaneler</h2>
    <ul>
        <li>pandas: Veri işleme ve manipülasyonu için kullanılmıştır.</li>
        <li>BeautifulSoup: Metin verilerinden HTML etiketlerini temizlemek için kullanılmıştır.</li>
        <li>tqdm: İlerleme çubukları oluşturmak ve işlemlerin ilerleyişini takip etmek için kullanılmıştır.</li>
        <li>scikit-learn: Veri setini eğitim ve test verilerine ayırmak için kullanılmıştır.</li>
        <li>TensorFlow: Yapay sinir ağı modeli oluşturmak, derlemek ve eğitmek için kullanılmıştır.</li>
    </ul>

    <h2>Proje Adımları</h2>
    <ol>
        <li><strong>Veri Yükleme ve Temizleme:</strong> İlk olarak, veri kümesi bir Excel dosyasından yüklenir ve HTML etiketleri temizlenir.</li>
        <li><strong>Önişleme:</strong> Metin verileri temizlendikten sonra, kelimeler sayısal olarak temsil edilir ve bir DataFrame'e dönüştürülür.</li>
        <li><strong>Etiket Hazırlama:</strong> Cümle etiketleri düzenlenir ve olumlu/negatif etiketler sayısal değerlere dönüştürülür.</li>
        <li><strong>Veri Ayırma:</strong> Veri kümesi eğitim ve test verilerine ayrılır.</li>
        <li><strong>Model Oluşturma:</strong> Bir yapay sinir ağı modeli oluşturulur. Girdi katmanı, gizli katmanlar ve çıktı katmanı içerir.</li>
        <li><strong>Model Derleme:</strong> Model derlenir ve eğitim süreci için optimizasyon fonksiyonu ve kayıp fonksiyonu belirlenir.</li>
        <li><strong>Model Eğitimi:</strong> Model eğitim verileri kullanılarak eğitilir.</li>
        <li><strong>Tahmin ve Sonuç:</strong> Kullanıcıdan bir cümle alınır, bu cümle temizlenir ve model üzerinde tahmin yapılır. Elde edilen tahmin sonucuna göre cümlenin olumlu mu yoksa olumsuz mu olduğu belirlenir.</li>
    </ol>
    
    <p>Projeye dair daha fazla bilgi için lütfen kod dosyasına ve yorum satırlarına başvurun. Projeyi keşfetmeye hoş geldiniz!</p>
</body>
</html>
