# Association Rule Based Recommender System

## Project Summary

Business Problem:
Armut, Turkey's largest online service platform, connects service providers with individuals seeking services. It allows easy access to services such as cleaning, renovation, and transportation with just a few taps on a computer or smartphone. By using the dataset containing information about service recipients and the services they have received, including their categories, the aim is to create a product recommendation system using Association Rule Learning.

Dataset Story:
The dataset consists of the services received by customers and their corresponding categories. It also includes the date and time information for each service. 
The dataset has 4 variables, 162,523 observations, and a size of 5 MB.

Variables:
- UserId: Customer number
- ServiceId: Anonymized services belonging to each category (Example: Carpet cleaning service under the Cleaning category). A ServiceId can be found under different categories and represents different services under different categories (Example: ServiceId 4 under CategoryId 7 represents radiator cleaning, while ServiceId 4 under CategoryId 2 represents furniture assembly).
- CategoryId: Anonymized categories (Example: Cleaning, transportation, renovation)
- CreateDate: Date of service purchase

## Installation

1. Clone this project: `git clone https://github.com/YOUR_USERNAME/Association-Rule-Based-Recommender-System.git`
2. Navigate to the project folder: `cd Association-Rule-Based-Recommender-System`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the project: `python main.py`

## Usage

1. Add the dataset to the "data" folder.
2. Run the project.
3. Apply Association Rule Learning to generate product recommendations based on the services received by customers and their categories.
4. Analyze the results and utilize the recommender system to provide personalized service recommendations for users on the Armut platform.

## Contributing

1. Fork this project.
2. Create a new branch: `git checkout -b feature/NewFeature`
3. Make your changes and commit them: `git commit -am 'Added a new feature'`
4. Push your branch to the forked repository: `git push origin feature/NewFeature`
5. Create a pull request.
-----------------------------------
# Association Rule Based Recommender System

## Proje Özeti

İş Problemi:
Armut, Türkiye'nin en büyük online hizmet platformudur ve hizmet sağlayıcıları ile hizmet almak isteyenleri bir araya getirir. Temizlik, tadilat, nakliyat gibi hizmetlere kolay erişim sağlamak için bilgisayar veya akıllı telefon üzerinden birkaç dokunuşla hizmet alınmasını sağlar. Hizmet alan kullanıcılar ve bu kullanıcıların aldıkları hizmetler ve kategorileri içeren veri setini kullanarak, Association Rule Learning yöntemiyle bir ürün öneri sistemi oluşturulması hedeflenmektedir.

Veri Seti Hikayesi:
Veri seti, müşterilerin aldığı hizmetler ve ilgili kategorilerden oluşmaktadır. Her hizmetin tarih ve saat bilgilerini içermektedir.
Veri seti 4 değişken, 162.523 gözlem ve 5 MB boyutundadır.

Değişkenler:
- UserId: Müşteri numarası
- ServiceId: Her kategoriye ait anonimleştirilmiş hizmetlerdir (Örnek: Temizlik kategorisi altında koltuk yıkama hizmeti). Bir ServiceId farklı kategoriler altında bulunabilir ve farklı kategoriler altında farklı hizmetleri ifade eder (Örnek: CategoryId'si 7 olan ServiceId'si 4 olan hizmet petek temizliğini temsil ederken, CategoryId'si 2 olan ServiceId'si 4 olan hizmet mobilya montajını temsil eder).
- CategoryId: Anonimleştirilmiş kategoriler (Örnek: Temizlik, nakliyat, tadilat)
- CreateDate: Hizmetin satın alındığı tarih

## Kurulum

1. Bu projeyi klonlayın: `git clone https://github.com/YOUR_USERNAME/Association-Rule-Based-Recommender-System.git`
2. Proje klasörüne gidin: `cd Association-Rule-Based-Recommender-System`
3. Gerekli bağımlılıkları yükleyin: `pip install -r requirements.txt`
4. Projeyi çalıştırın: `python main.py`

## Kullanım

1. Veri setini "data" klasörüne ekleyin.
2. Projeyi çalıştırın.
3. Association Rule Learning yöntemini uygulayarak, müşterilerin aldığı hizmetler ve kategorilerine dayalı ürün önerileri oluşturun.
4. Sonuçları analiz edin ve Armut platformunda kullanıcılara kişiselleştirilmiş hizmet önerileri sunmak için öneri sisteminizi kullanın.

## Katkıda Bulunma

1. Bu projeyi fork edin.
2. Yeni bir dal oluşturun: `git checkout -b feature/YeniOzellik`
3. Değişikliklerinizi yapın ve bunları kaydedin: `git commit -am '

Yeni bir özellik eklendi'`
4. Dalınızı forked repository'e gönderin: `git push origin feature/YeniOzellik`
5. Bir pull isteği oluşturun.
