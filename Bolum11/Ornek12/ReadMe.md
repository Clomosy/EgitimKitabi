# 11.Bölüm 12.Örnek

### Açıklama

Örnekte, `TclForm` türünde bir form (`Form1`) oluşturulmuş ve üzerine bir buton (`Buton1`) eklenmiştir. İlk olarak, `Form1 = TclForm.Create(self)` komutuyla form oluşturuluyor. Ardından, `Buton1 = Form1.AddNewButton(Form1, 'Buton1', 'BUTON')` komutuyla buton ekleniyor ve butonun etiket metni `'BUTON'` olarak belirleniyor. Butonun genişliği, `Buton1.Width = 200` komutuyla 200 piksel olarak ayarlanıyor. Bu, butonun yatayda daha geniş görünmesini sağlayan bir işlemdir. Son olarak, `Form1.Run` komutuyla form çalıştırılıyor.

![Bolum 11-Örnek 12](Bolum11_Ornek12.png)