# acikseminer2020
Türkiye Açık Kaynak Platformunun organizasyonluğunda düzenlenen Açık Seminer (https://www.acikseminer.com/) serisinin Doğal Dil İşleme haftasında [Açık Seminer 14. Gün: NLP 101: Doğal Dil İşlemeye Giriş](https://www.acikseminer.com/seminerler/acik-seminer-14-gun-nlp-101-dogal-dil-islemeye-giris-7194f676) konulu sunuma ait kaynaklar.

<p align="center">
  <img src="https://www.acikseminer.com/wp-content/uploads/2020/04/acil-seminer-logo.svg" />
</p>

<p align="center">
  <img src="https://media.kommunity.com/communities/tracikkaynak/events/acikseminer-3-gun-acik-kaynak-isletim-sistemleri-b7378831/18818/acikseminer.jpeg" width="335" />
</p>

## Açık Seminer 14. Gün: NLP 101: Doğal Dil İşlemeye Giriş

14:00 - 15:50 - **NLP 101: Doğal Dil İşlemeye Giriş** - *Başak Buluz (Gebze Teknik Üniversitesi), Yavuz Kömeçoğlu (Kodiks Bilişim)*

:paperclip: Sunum dosyasına [buradan](https://github.com/basakbuluz/acikseminer2020/blob/master/NLP101-A%C3%A7%C4%B1k%20Seminer.pptx) erişebilirsiniz.

Sunum içerisinde bir çok kaynağa yönlendirme linkleri mevcuttur. 

## Örnekler

### Metin Ön İşlemleri
* Zemberek'in Python entegrasyonu olan [pyZemberek](https://github.com/kodiks/pyzemberek)'den yararlanılmıştır.


### Metin Öznitelikleri Çıkartma
#### TF-IDF ve CountVector Örneği
* [Dr. Deniz Kılınç](https://github.com/denopas) hocanın ön işlem örneklerinden yararlanılarak oluşturulan çalışma dosyası

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/basakbuluz/acikseminer2020/blob/master/TextProcessingPart1.ipynb)

#### Word2vec Örneği
* Önceden eğitilmiş Türkçe word2vec modelinin kullanımı ve modelin yapısını anlamak için kelime vektörleri örneklerini içeren çalışma dosyası

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/basakbuluz/acikseminer2020/blob/master/word2vec_tr_analysis.ipynb)

**NOT:** Word2vec çalışma dosyasını başlatmadan önce 2019.03.20 tarihli Türkçe Wikipedia korpusu ile eğitilmiş [word2vec model dosyasını](https://dumps.wikimedia.org/trwiki/) indirerek `models/tr_word2vec` klasörü altına yükleyiniz.