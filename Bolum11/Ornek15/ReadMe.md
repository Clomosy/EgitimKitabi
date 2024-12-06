# 11.Bölüm 15.Örnek

### Açıklama

Örnekte, bir form (`Form1`) ve bu forma serbest pozisyonda yerleştirilmiş bir buton (`Buton1`) oluşturulmaktadır. İlk olarak `Form1 = TclForm.Create(self)` ile form oluşturulur ve `Buton1 = Form1.AddNewButton(Form1, 'Buton1', 'BUTON')` komutuyla form üzerine bir buton eklenir. Butonun hizalaması `Buton1.Align = alNone` olarak ayarlanır, böylece herhangi bir otomatik hizalama uygulanmaz ve serbest pozisyonda yerleştirme yapılabilir. 

Sonrasında, `Buton1.Position.X = 50` ile buton formun sol kenarından 50 piksel uzaklıkta, `Buton1.Position.Y = 100` ile üst kenardan 100 piksel uzaklıkta olacak şekilde konumlandırılır. Bu örnek, bir bileşenin hizalamadan bağımsız olarak kesin koordinatlarla nasıl konumlandırılabileceğini göstermektedir. Form, `Form1.Run` komutuyla çalıştırılarak bu yapılandırma kullanıcıya sunulur.

![Bolum 11-Örnek 15](Bolum11_Ornek15.png)