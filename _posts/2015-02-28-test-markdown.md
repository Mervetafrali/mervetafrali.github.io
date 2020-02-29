---
layout: post
title: Bu Site Nasıl Kuruldu ?
subtitle: Github.io Nedir? 
tags: [Github]
comments: true
---

#  GitHub Pages Nedir ?

Github pages yazınca karşımıza çıkan ilk sayfada yazan[[1]][1] ilk cümle ile başlayalım,

> GitHub Sayfaları, GitHub aracılığıyla hosting edilen  ve kolayca yayınlanabilen genel web sayfalarıdır.


Kendi hakkımda bir bloğum olsun host ücreti vermiyeyim, Wordpress ile uğraşmayayım bir kaç bilgi anlatayım arada da post atarım düşüncesiyle yola çıkıp basit hızlı bir şekilde web sitesi oluşturmak istiyorsanız bunun en kolay çözümü Github Pages.

Jekyll ile hızlıca görünüm ayarlama ve  domain adı alınca da kolay ayarlama özelliklerine de sahip ayrıca.

Peki nasıl yapacağız Github Pages ile bu kendi blogunu oluşturma işlemini derseniz o iş gerçekten çok kolay.


Öncelikle bir Github hesabınızın olması gerekiyor.

*Yoksa kayıt yada oturum açma işlemi için -> https://github.com/ *

#### Web Sitesi Oluşturma

------------

Giriş yaptıktan sonra new repository oluşturmanız gerekiyor.
![repo](/img/newrepo.png)
Oluşturacağınız reponun ismine  ***kullanıcıadınız.github.io***
vermeniz gerekiyor.
Yeni reponuzu oluşturduktan sonra ayarlar kısmında aşağı inerek  **GitHub Pages** kısmına gelin ardından da **Choose a theme** butonuna basın. 
İstediğiniz temayı seçerek ilerleyin ve sitenizi oluşturun. 
Gelen sayfadaki markdown dosyasını düzenleyerek sayfanızda basit değişiklikler yapabilirsiniz. 
Yaptığınız değişiklikleri kaydetmek için **Commit changes** butonuna basınız.  
Siteinizi görmek için arama moturuna  ***kullanıcıadınız.github.io*** yazarak ulaşabilirsiniz!
:tw-1f4aa:  :rocket:
Değişiklik yapmak için* _config.yml*  uzantılı dosyayı kullanabilirsiniz.  

Daha detaylı bilgi için  -> https://guides.github.com/features/pages/

Sayfanızın daha güzel görünümü için -> https://github.com/daattali/beautiful-jekyll kullanabilirsiniz. 

**Ek Kaynak ->** https://gokhansengun.com/blogun-teknik-altyapisi/ 

####  Peki ya Domain ?

------------

Domain işlemleri bu uğraşlar arasında en kolay olanı, özellikle de öğrenci iseniz çok daha keyiflisi.

Öğrenci olarak Github hesabınızı onaylarsanız linkte [[2]][2]  size sunulan onlarca fırsat olduğunu keşfedebilirsiniz. 
![Educ](/img/educat.png)
JetBrains ürünlerinden DigitalOcean'da kullanabileceğiniz 50 $ çeke kadar onlarca fırsat var.
Domain alma da bunlardan biri. 
Ben namecheap ile bir yıllık domain ve SSL sertifikası aldım. 
Aldğım domainde github eklentisi ile A record ayarları kolaylıkla geldi, yapmak gereken tek şey repomda olan  CMAKE uzantılı dosyanın içine domain ismimi eklemek oldu.
İsim eklendikten 10 dakika sonra kullanabilir hale geldi.

Bu konuyla ilgili tüm sorunlarınızın cevaplarına kolaylıkla ulaşabilirsiniz. Bu yüzden mutlaka kendi sitenizi kurmaya çalışınız.

------------


XOXO
:tw-270c:


[1]: https://guides.github.com/features/pages/ "GitHub Pages"
[2]: https://education.github.com/pack "EducationPack"
