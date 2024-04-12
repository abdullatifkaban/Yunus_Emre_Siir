# Yunus Emre Şiiri Yazdırma Aracı

Bu projede Yunus Emre şiirleri kullanılarak eğitilen bir derin öğrenme modeli ile şiir yazma aracı geliştiriyoruz.
Bu model normalde sonraki kelimeyi tahmin ederek bir metin yazdırma modeli olarak kullanılmaktadır. 
Ancak bu projede sonraki kelimeyi değil önceki kelimeyi tahmin ederek şiir yazmaya çalışıyoruz. 
Çünkü şiirde satır sonlarındaki kelimelerin kafiyeli olması beklenir. 
Dolayısıyla bir kelime seçip o kelimeyi satır sonuna koyarak önceki kelimeleri tahmin edip bir şiir dizesi oluşturuyoruz. 
Bir sonraki satırda da yine kafiyeli bir kelimeden yola çıkarak öndeki kelimer sırayla tahmin edilir ve şiir tamamlanır.
<br><br>
Bu modeli eğitmek için Yunus Emre şiirleri kullanılmıştır. Şiirler başlıksız olarak alt alta eklenip bir metin dosyasına yerleştirildi.
<br>
* Jupyter notebook dosyasına <a href="https://github.com/abdullatifkaban/Yunus_Emre_Siir/blob/main/yunus_siir.ipynb">buradan</a> ulaşabilirsiniz.
* Bu model kullanılarak geliştirilen streamlit uygulamasına <a href="https://huggingface.co/spaces/abdullatifkaban/Yunus_Emre" target="_blank">buradan</a> ulaşabilirsiniz.
