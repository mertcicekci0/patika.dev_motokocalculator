
Motoko Hesap Makinesi

Bu proje, Motoko programlama dilinde geliştirilmiş basit bir hesap makinesi uygulamasıdır. Kullanıcıların toplama, çıkarma, çarpma ve bölme işlemlerini yapabilmesini sağlar.

Özellikler
	•	Toplama
	•	Çıkarma
	•	Çarpma
	•	Bölme
	•	Kullanıcı dostu arayüz

Gereksinimler
	•	Motoko SDK yüklü olmalıdır.
	•	Bir Internet Computer ortamına erişim sağlanmış olmalıdır (örneğin, bir canister oluşturulmuş ve dağıtım yapılmış olmalıdır).

Kurulum
	1.	Motoko SDK’yı yükleyin:
Eğer henüz yüklü değilse, Motoko SDK dökümantasyonunu takip ederek kurulum işlemini gerçekleştirebilirsiniz.
	2.	Proje dosyalarını indirin:


	3.	Projeyi derleyin:
Proje dosyalarını derlemek için aşağıdaki komutu kullanın:

dfx deploy


	4.	Canister’ı başlatın:
Hesap makinesini kullanmak için:

dfx canister call hesap_makinesi hesap (parametreler)



Kullanım
	1.	Toplama:
İki sayıyı toplamak için aşağıdaki komutu kullanabilirsiniz:

dfx canister call hesap_makinesi toplama '(5, 3)'


	2.	Çıkarma:
İki sayıyı çıkarmak için aşağıdaki komutu kullanabilirsiniz:

dfx canister call hesap_makinesi cikarma '(8, 4)'


	3.	Çarpma:
İki sayıyı çarpmak için aşağıdaki komutu kullanabilirsiniz:

dfx canister call hesap_makinesi carpma '(7, 2)'


	4.	Bölme:
İki sayıyı bölmek için aşağıdaki komutu kullanabilirsiniz:

dfx canister call hesap_makinesi bolme '(10, 2)'
