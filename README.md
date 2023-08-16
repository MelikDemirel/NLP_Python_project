# NLP_Python_project
Language model that detects whether the sentence entered by the user is positive or negative / kullanıcı tarafında girilen cümlenin olumlu mu olumsuz mu olduğunu tespit eden dil modeli

<p><strong>Sentiment Analysis with Language Model</strong></p>

<p>This project involves a language model that analyzes user-entered sentences to determine their positive or negative sentiment. The process includes text data cleaning and preprocessing, as well as creating and training an artificial neural network using TensorFlow and other relevant libraries.</p>

<ul>
  <li><strong>Libraries Used:</strong></li>
  <ul>
    <li><code>pandas</code>: Utilized for data processing and manipulation.</li>
    <li><code>BeautifulSoup</code>: Employed to cleanse HTML tags from text data.</li>
    <li><code>tqdm</code>: Used to generate progress bars and monitor operation progress.</li>
    <li><code>scikit-learn</code>: Used to split the dataset into training and testing data.</li>
    <li><code>TensorFlow</code>: Utilized for creating, compiling, and training the artificial neural network model.</li>
  </ul>
  
  <li><strong>Project Steps:</strong></li>
  <ol>
    <li><strong>Data Loading and Cleaning:</strong> Load the dataset from an Excel file and remove HTML tags.</li>
    <li><strong>Preprocessing:</strong> After cleaning text data, convert words into numerical representations and transform into a DataFrame.</li>
    <li><strong>Label Preparation:</strong> Organize sentence labels and convert them into numerical values for positive and negative sentiment.</li>
    <li><strong>Data Splitting:</strong> Split the dataset into training and testing data.</li>
    <li><strong>Model Creation:</strong> Construct an artificial neural network model with input, hidden, and output layers.</li>
    <li><strong>Model Compilation:</strong> Compile the model, defining optimization and loss functions for training.</li>
    <li><strong>Model Training:</strong> Train the model using the training data.</li>
    <li><strong>Prediction and Results:</strong> Take a user-input sentence, clean it, and make a prediction using the model. Determine whether the sentence is positive or negative based on the prediction.</li>
  </ol>
</ul>


<p><strong>Dil Modeli ile Duygu Analizi</strong></p>

<p>Bu proje, kullanıcı tarafından girilen cümleleri analiz ederek cümlenin pozitif veya negatif duygusunu belirleyen bir dil modelini içermektedir. Süreç, metin verilerini temizleme ve önişleme işlemlerini içermekte, aynı zamanda TensorFlow ve diğer ilgili kütüphaneleri kullanarak yapay sinir ağı modeli oluşturmayı ve eğitmeyi içermektedir.</p>

<ul>
  <li><strong>Kullanılan Kütüphaneler:</strong></li>
  <ul>
    <li><code>pandas</code>: Veri işleme ve manipülasyon için kullanılmıştır.</li>
    <li><code>BeautifulSoup</code>: Metin verilerinden HTML etiketlerini temizlemek için kullanılmıştır.</li>
    <li><code>tqdm</code>: İlerleme çubukları oluşturmak ve işlemlerin ilerleyişini takip etmek için kullanılmıştır.</li>
    <li><code>scikit-learn</code>: Veri setini eğitim ve test verilerine ayırmak için kullanılmıştır.</li>
    <li><code>TensorFlow</code>: Yapay sinir ağı modeli oluşturmak, derlemek ve eğitmek için kullanılmıştır.</li>
  </ul>
  
  <li><strong>Proje Adımları:</strong></li>
  <ol>
    <li><strong>Veri Yükleme ve Temizleme:</strong> Veri kümesini bir Excel dosyasından yükleyin ve HTML etiketlerini kaldırın.</li>
    <li><strong>Önişleme:</strong> Metin verilerini temizledikten sonra kelimeleri sayısal temsillere dönüştürün ve bir DataFrame'e aktarın.</li>
    <li><strong>Etiket Hazırlama:</strong> Cümle etiketlerini düzenleyin ve pozitif ve negatif duygular için sayısal değerlere dönüştürün.</li>
    <li><strong>Veri Ayırma:</strong> Veri kümesini eğitim ve test verilerine bölin.</li>
    <li><strong>Model Oluşturma:</strong> Girdi, gizli ve çıktı katmanlarından oluşan bir yapay sinir ağı modeli oluşturun.</li>
    <li><strong>Model Derleme:</strong> Modeli derleyin, eğitim için optimizasyon ve kayıp fonksiyonlarını tanımlayın.</li>
    <li><strong>Model Eğitimi:</strong> Modeli eğitim verileri kullanarak eğitin.</li>
    <li><strong>Tahmin ve Sonuç:</strong> Kullanıcıdan bir cümle alın, temizleyin ve modeli kullanarak bir tahmin yapın. Tahmine dayanarak cümlenin pozitif veya negatif olup olmadığını belirleyin.</li>
  </ol>
</ul>
