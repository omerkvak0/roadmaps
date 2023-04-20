# **Front End Yol Haritası**
Merhaba. Bu yazımda Back End Developer yol haritası hakkında bahsettim. Araştırıp öğrendiğim konuları ele aldım. Bu alanda ilerlemek isteyen ve ilerlemiş olan herkese başarılar dilerim.

## **1. Adım: Programlama Dilleri** 
* Back-end geliştirme için en yaygın kullanılan programlama dilleri arasında [Python](https://www.freecodecamp.org/news/how-to-learn-python/), [PHP](https://www.w3schools.com/php/), [Ruby](https://www.codecademy.com/learn/learn-ruby), [Java](https://www.codecademy.com/learn/learn-java), [C#](https://learn.microsoft.com/en-us/training/paths/get-started-c-sharp-part-1/?WT.mc_id=dotnet-35129-website) ve [Node.js](https://www.w3schools.com/nodejs/) yer almaktadır. 
* Bir dil seçmek, ihtiyaçlarınıza ve hedeflerinize göre değişebilir. Örneğin, veri yoğun uygulamalar geliştiriyorsanız, Python ve Ruby gibi diller daha uygun olabilir.

## **2. Adım: Web Çerçeveleri** 
* Back-end geliştirme için kullanabileceğiniz birçok web çerçevesi vardır. Bunlar arasında [Django](https://www.w3schools.com/django/), [Flask](https://www.tutorialspoint.com/flask/index.htm), [Ruby on Rails](https://www.jetbrains.com/ruby/promo/?source=google&medium=cpc&campaign=18219527220&term=ruby%20on%20rails%20programming&content=619457263645&gad=1&gclid=Cj0KCQjwxYOiBhC9ARIsANiEIfatgVLEZk0DFR3yE1yA6FeZUSDo_7sMM8h3fS2xd4lU--oGK-cL8awaAuwuEALw_wcB), [Express.js](https://www.javatpoint.com/expressjs-tutorial) ve [Spring Framework](https://www.tutorialspoint.com/spring/index.htm) gibi popüler çerçeveler yer alır. 
* Web çerçeveleri, temel özellikleri ve araçları sağlar, böylece uygulama geliştirmenizi daha kolay hale getirirler.

## **3. Adım: Veritabanı Yönetimi**
* Veritabanı yönetimi back-end geliştirme sürecinin önemli bir parçasıdır. 
* SQL ve NoSQL veritabanları arasında seçim yapabilirsiniz. 
* SQL veritabanları arasında [MySQL](https://www.w3schools.com/mySQl/default.asp), [PostgreSQL](https://www.postgresqltutorial.com/) ve [Oracle](https://www.oracle.com/database/) bulunurken, NoSQL veritabanları arasında [MongoDB](https://www.mongodb.com/docs/) ve [Cassandra](https://cassandra.apache.org/_/index.html) gibi popüler seçenekler vardır.
* Veritabanı yönetimi, verilerinizi saklamak, yönetmek ve güncellemek için gereklidir.

## **4. Adım: API Geliştirme**
* Back-end geliştiricileri, [API'ler](https://aws.amazon.com/tr/what-is/api/) (Application Programming Interface) oluşturarak farklı uygulamalar arasında veri paylaşımı yapabilirler. 
* API'ler, uygulamanızın özelliklerine ve amaçlarına göre tasarlanır.
* [RESTful](https://restfulapi.net/) API'ler, [SOAP](https://www.tutorialspoint.com/soap/index.htm) API'ler ve [GraphQL](https://graphql.org/) gibi birçok API türü bulunmaktadır.


## **5. Adım: Caching**
* Sık kullanılan verileri veya bilgileri belirli bir süre boyunca yerel bir bellekte depolama tekniğidir.
* [Client Side](https://www.youtube.com/watch?v=HiBDZgTNpXY):İstemci tarafı önbelleğe alma, ağ verilerinin gelecekte yeniden kullanım için yerel bir önbelleğe depolanmasıdır. Bir uygulama ağ verilerini getirdikten sonra, bu kaynağı yerel bir önbellekte depolar.
* [CDN](https://www.cloudflare.com/en-ca/learning/cdn/what-is-a-cdn/): ir İçerik Dağıtım Ağı (CDN) hizmeti, web sitelerinin yüksek kullanılabilirliğini ve performans iyileştirmelerini sağlamayı amaçlar. Bu, web sitesi varlıklarının ve içeriğinin tipik olarak müşteri isteklerine coğrafi olarak daha yakın uç noktalar aracılığıyla hızlı bir şekilde teslim edilmesiyle elde edilir.

## **6. Adım: Testing**
* [Integration Testing](https://www.guru99.com/integration-testing.html): Entegrasyon testi, birden çok yazılım modülünün entegre edildiği ve bir grup olarak test edildiği geniş bir test kategorisidir . Birden çok hizmet, kaynak veya modül arasındaki etkileşimi test etmek içindir . Örneğin, bir API'nin bir arka uç hizmetiyle veya bir veritabanıyla bir hizmetle etkileşimi.
* [Unit Testing](https://www.guru99.com/unit-testing-guide.html): Birim testi, yazılımın bireysel birimlerinin (modüller, işlevler/yöntemler, rutinler, vb.) doğruluğunu sağlamak için test edildiği yerdir . Bu düşük seviyeli test, daha yüksek seviyeli testlerin yükünü hafifletirken daha küçük bileşenlerin işlevsel olarak sağlam olmasını sağlar.
* [Functional Testing](https://www.guru99.com/functional-testing.html): İşlevsel test, işlevsel gereksinimlerin karşılandığından emin olmak için yazılımın test edildiği yerdir. Genellikle, test eden kişinin kaynak kodu anlamadığı bir tür kara kutu testidir; test, girdi sağlayarak ve beklenen/gerçek çıktıyı karşılaştırarak gerçekleştirilir.

## **7. Adım: Sürekli Entegrasyon ve Sürekli Dağıtım:**
* Sürekli entegrasyon ve sürekli dağıtım ([CI/CD](https://talentgrid.io/tr/ci-cd-nedir-en-iyi-ci-cd-araclari/)), back-end geliştirme sürecinin önemli bir parçasıdır.
* CI/CD, yazılımın sürekli test edilmesi, entegre edilmesi ve dağıtılması için bir dizi otomatik süreçtir. Bu, yazılımın kalitesini artırır, hataları hızlıca tespit eder ve kodu daha hızlı ve verimli bir şekilde dağıtmanıza olanak tanır.

## **8. Adım: Architectural Patterns:**
* Mimari model, belirli bir bağlamda yazılım mimarisinde yaygın olarak ortaya çıkan bir soruna yönelik genel, yeniden kullanılabilir bir çözümdür.
* [SOA](http://docs.oasis-open.org/soa-rm/soa-ra/v1.0/soa-ra.html): SOA veya hizmet odaklı mimari, yazılım bileşenlerini hizmet arabirimleri aracılığıyla yeniden kullanılabilir hale getirmenin bir yolunu tanımlar. Bu arabirimler, her seferinde derinlemesine entegrasyon gerçekleştirmek zorunda kalmadan yeni uygulamalara hızla dahil edilebilecek şekilde ortak iletişim standartlarını kullanır.
* [Serverless](https://www.ibm.com/topics/serverless): Geliştiricinin sunucuları tedarik etmeden veya yönetmeden uygulamalar oluşturduğu ve çalıştırdığı bir mimaridir.

## **9. Adım: ElasticSearch**
* Özünde belge yönelimli bir arama motorudur. Kaydedilen kayıtlar üzerinde INSERT, DELETE, RETRIEVE ve hatta analiz yapmanıza izin veren belge tabanlı bir veritabanıdır. [Link.](https://www.elastic.co/elasticsearch/)

## **10. Adım: Message Brokers**
* Bulutta yerel, mikro hizmet tabanlı, sunucusuz ve hibrit bulut mimarilerini desteklemek için ortak bir entegrasyon mekanizması oluşturmaya yardımcı olan bir uygulamalar arası iletişim teknolojisidir.
* [RabbitMQ](https://www.rabbitmq.com/getstarted.html): On binlerce kullanıcısı olan RabbitMQ, en popüler açık kaynaklı mesaj aracılarından biridir. RabbitMQ hafiftir ve şirket içinde ve bulutta devreye alınması kolaydır. Birden fazla mesajlaşma protokolünü destekler.

## **11. Adım: Konteynerleştirme ve Sanallaştırma**
* Kapsayıcılar ve sanal makineler, kuruluşunuz için bir yazılım altyapısı oluşturmaya yönelik en popüler iki yaklaşımdır.
* [Kubernetes](https://kubernetes.io/docs/home/):Kubernetes, [açık kaynaklı](https://github.com/kubernetes/kubernetes) bir konteyner yönetim platformudur ve bu alandaki baskın üründür. Ekipler, Kubernet'leri kullanarak görüntüleri birden çok temel ana bilgisayarda dağıtabilir ve YAML'de istedikleri kullanılabilirliği, dağıtım mantığını ve ölçeklendirme mantığını tanımlayabilir.

## **12. Adım: Web Sockets**
* Web soketleri, sunucular ve istemciler arasında iki yönlü bir iletişim olarak tanımlanır, yani her iki taraf da aynı anda iletişim kurar ve veri alışverişi yapar. Bu protokol sıfırdan tam çift yönlü bir iletişimi tanımlar. [Link](https://www.youtube.com/watch?v=8ARodQ4Wlf4).

## **13. Adım: Server Sent Events**
* Sunucu Tarafından Gönderilen Olaylar ([SSE](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events)), bir web sunucusunun verileri bir istemciye gerçek zamanlı olarak iletmesine izin veren bir teknolojidir. Sunucudan istemciye bir veri akışı göndermek için bir HTTP bağlantısı kullanır ve istemci bu olayları dinleyebilir ve alındığında harekete geçebilir.
* SSE, sohbet sistemleri, hisse senetleri ve sosyal medya beslemeleri gibi gerçek zamanlı güncellemeler gerektiren uygulamalar için kullanışlıdır. Bir istemci ile sunucu arasında uzun ömürlü bir bağlantı kurmanın basit ve verimli bir yoludur ve çoğu modern web tarayıcısı tarafından desteklenir.
* SSE'yi kullanmak için istemcinin bir EventSource nesnesi oluşturması ve olayları gönderecek sunucu tarafı komut dosyasının URL'sini belirtmesi gerekir. Sunucu daha sonra olayları uygun biçimlendirme ile yanıt akışına yazarak gönderebilir.

## **14. Adım: Web Servers**
> * Donanım Tarafı: Donanım web sunucusu, web sunucusu yazılımını ve bir web sitesini oluşturan dosyaları (örneğin, HTML belgeleri, resimler, CSS stil sayfaları ve JavaScript dosyaları) barındıran bir bilgisayardır. Bir web sunucusu, İnternet ile bağlantı kurar ve diğer web bağlantılı cihazlarla fiziksel veri alışverişini kolaylaştırır.
> * Yazılım tarafı: Bir yazılım web sunucusu, barındırılan dosyalara çevrimiçi kullanıcılar tarafından nasıl erişileceğini düzenleyen bir dizi yazılım bileşenine sahiptir. Bu en azından bir HTTP sunucusudur. HTTP ve URL'leri (web adresleri) bilen ve anlayan yazılım, HTTP sunucusu (tarayıcınızın web sayfalarını görüntülemek için kullandığı protokol) olarak bilinir.
* [Nginx](https://nginx.org/): NGINX güçlü bir web sunucusudur ve doğru yapılandırılırsa Apache'den daha iyi performans göstermesini sağlayan iş parçacıklı olmayan, olaya dayalı bir mimari kullanır. Ayrıca, yük dengeleme, HTTP önbelleğe alma gibi diğer önemli şeyleri de yapabilir veya ters proxy olarak kullanılabilir.


## **15. Adım: Building for Scale**
* Genel terimlerle konuşursak, ölçeklenebilirlik, bir sistemin kendisine kaynak ekleyerek giderek artan miktarda işin üstesinden gelme yeteneğidir.
* Ölçeklenebilir bir mimari düşünülerek tasarlanmış bir yazılım, daha yüksek iş yüklerini, üzerinde herhangi bir temel değişiklik olmaksızın destekleyecek bir sistemdir, ancak aldanmayın, bu sihir değildir. Daha fazla kaynak eklemeden akıllı düşünceyle yalnızca bir yere kadar gelirsiniz.
> * Enstrümantasyon, İzleme ve Telemetri: 
> [Enstrümantasyon](https://en.wikipedia.org/wiki/Instrumentation_(computer_programming)), hataları teşhis etmek ve iz bilgilerini yazmak için bir ürünün performansının ölçüsünü ifade eder. Enstrümantasyon iki tip olabilir: kaynak enstrümantasyon ve ikili enstrümantasyon.
> [Arka uç izleme](https://www.yottaa.com/performance-monitoring-backend-vs-front-end-solutions/), kullanıcının altyapının performansını, yani bir web uygulamasını çalıştıran bileşenleri görüntülemesine olanak tanır. Bunlara HTTP sunucusu, ara yazılım, veritabanı, üçüncü taraf API hizmetleri ve daha fazlası dahildir.
> [Telemetri](https://www.sumologic.com/glossary/telemetry/), uygulamanın farklı bileşenlerinden sürekli olarak veri toplama işlemidir. Bu veriler, mühendislik ekiplerinin hizmetlerdeki sorunları gidermesine ve temel nedenleri belirlemesine yardımcı olur. Başka bir deyişle, telemetri verileri, dağıtılmış uygulamalarınız için gözlemlenebilirliği güçlendirir.

* [Graceful Degradation](https://newrelic.com/blog/best-practices/design-software-for-graceful-degradation): Bir sistemin bazı bileşenleri veya özellikleri mevcut olmasa bile çalışmaya devam edecek şekilde tasarlanması gerektiğini belirten bir tasarım ilkesidir. Web geliştirme bağlamında, zarif bozulma, kullanıcının tarayıcısı veya cihazı belirli özellikleri veya teknolojileri desteklemese bile bir web sayfasının veya uygulamasının çalışmaya devam edebilmesi anlamına gelir.


### **Kaynakça:**
* [Roadmap](https://roadmap.sh/backend)

**Detaylı açıklamaları kaynaklarda bulunan linkten öğrenebilirsiniz.**
**Yol haritamız buraya kadardı. Fakat iş burada bitmedi. Geriye sizin yapacağınız projeler kaldı. Yakın bir zamanda Back End ile ilgili proje fikirleri ve ekstra bilgiler de paylaşacağım.**
