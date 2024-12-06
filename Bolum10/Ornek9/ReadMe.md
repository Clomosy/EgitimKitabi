# 10.Bölüm 9.Örnek

### Açıklama

Örnekte, `TclForm` nesnesi kullanılarak bir form oluşturulmuş ve formun pencere durumu `clSetWindowState(fwsMaximized)` ile tam ekran (maksimum) olarak ayarlanmıştır. `AnaForm=TclForm.Create(Self)` ile form nesnesi oluşturulur, ardından `AnaForm.clSetWindowState(fwsMaximized)` komutu, formun başlangıçta tam ekran olmasını sağlar. Son olarak, `AnaForm.Run` komutu ile form çalıştırılır.