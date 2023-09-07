# GÜNLÜK Uygulaması

Bu belge, GÜNLÜK adlı basit bir Python uygulamasını açıklamaktadır. Uygulama, kullanıcıların tarih seçmelerine ve bu tarihler için belgeler oluşturmalarına olanak tanır. Kullanıcılar, belirli bir tarihe ait belgeleri kaydedebilir ve daha sonra bu belgelere erişebilirler.

## Kullanıcı Doğrulama

Kullanıcılar, `users` adlı bir sözlük içinde tanımlanan kullanıcı adı ve şifrelerini kullanarak giriş yaparlar. Kullanıcı adı ve şifre doğrulaması başarılı olursa, uygulama ana pencereye geçer.

## Ana Pencere

Ana pencere, kullanıcı adı ve şifre girişi alanlarını içerir. Kullanıcı başarılı bir şekilde giriş yaparsa, bu alanlar ve giriş düğmesi gizlenir ve kullanıcıya tarih seçme ve belge oluşturma yeteneği verilir.

## Tarih Seçme

Tarih seçme işlevi, `tkcalendar` kütüphanesi kullanılarak gerçekleştirilir. Kullanıcı, takvim bileşeni aracılığıyla bir tarih seçebilir.

## Belgelerin Oluşturulması ve Açılması

Kullanıcı, belirli bir tarih seçtiğinde, uygulama bu tarihe ait bir belge oluşturur veya daha önce oluşturulmuş bir belgeyi açar. Belgeler, `docx` kütüphanesi kullanılarak oluşturulur ve belge adı tarihle ilişkilendirilir.

## Kaydedilmiş Tarihlerin Listelenmesi

Kullanıcıların daha önce kaydedilmiş tarihleri görmelerine olanak tanımak için, kaydedilmiş tarihler bir Listbox içinde görüntülenir. Kullanıcılar daha önce kaydedilen bir tarihe tıkladığında, ilgili belge açılır.



