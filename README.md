CPanel Checker
Bu basit araç, bir liste içindeki alan adları için CPanel erişimini kontrol eder. CPanel'e başarılı bir şekilde erişilebilen alan adları bir dosyaya kaydedilir.

Kullanım
Python'u Yükleyin: Öncelikle, Python'un bilgisayarınızda yüklü olduğundan emin olun. Eğer yüklü değilse, Python'un resmi web sitesinden indirip yükleyebilirsiniz.

Gerekli Kütüphaneleri Yükleyin: İhtiyacınız olan kütüphaneleri yüklemek için terminal veya komut istemcisinde aşağıdaki komutu çalıştırın:

Copy code
pip install requests
Çalıştırın: cpanel_checker.py dosyasını bir metin düzenleyicisinde açın ve domain_list değişkenine kontrol etmek istediğiniz alan adlarını ekleyin. Daha sonra terminalde veya komut istemcisinde aşağıdaki komutu çalıştırın:

Copy code
python cpanel_checker.py
Sonuçları Görüntüleyin: Başarılı bir şekilde CPanel'e erişilebilen alan adları cpanel_domains.txt dosyasına kaydedilecektir. Bu dosyayı açarak sonuçları görebilirsiniz.

Notlar
Bu araç sadece CPanel'e erişilebilirlik kontrolü yapar. Güvenlik açısından başka kontroller yapmayı unutmayın.
Bu araç, sadece eğitim ve test amaçlıdır. Kötü niyetli kullanım için kullanmayın.
