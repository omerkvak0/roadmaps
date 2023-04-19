# **Front End Yol Haritası**
Merhaba. Bu yazımda Front End Developer yol haritası hakkında bahsettim. Araştırıp öğrendiğim ve çoğunu deneyimlediğim konuları ele aldım. Bu alanda ilerlemek isteyen ve ilerlemiş olan herkese başarılar dilerim.

## **1. Adım: HTML**
* Hiper Yazı İşaretleme Dili (HTML, İngilizce Hyper Text Markup Language kelimelerinin baş harflerinin kısaltılmasıdır) web sayfalarını oluşturmak için kullanılan standart metin işaretleme dilidir.
* Web tasarımın temel yapıtaşıdır.
* Bu adımda öğreneceğiniz alt başlıklar kısaca şu şekildedir;
> - [HTML Basic](https://www.w3schools.com/html/html_intro.asp)
> - [Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)
> - [Forms and Validations](https://web.dev/learn/forms/)

* İsteğe bağlı olarak öğrenebileceğiniz konular şu şekildedir:
> - [Accessibility](https://www.w3schools.com/accessibility/index.php)
> - [SEO Basic](https://developers.google.com/search/docs?hl=tr)


## **2. Adım: CSS**
* Herhangi bir web sitesinin ön yüzünü biçimlendirmek için kullanılan dildir.
* Bu adımda öğreneceğiniz alt başlıklar kısaca şu şekildedir;
> - [CSS Basic](https://www.w3schools.com/css/)
> - [Making Layouts](https://css-tricks.com/all-about-floats/)
> - [Responsive Tasarım](https://www.w3schools.com/css/css_rwd_intro.asp)


## **3. Adım: JavaScript**
* JavaScript, sayfalarınıza etkileşim eklemenizi sağlar. Web sitelerinde görmüş olabileceğiniz yaygın örnekler; kaydırıcılar, tıklama etkileşimleri, açılır pencereler vb.
* Bu adımda öğreneceğiniz alt başlıklar kısaca şu şekildedir;
> - [Syntax ve Basic Constructs]()
> - [DOM Manipülatör]()
> - [Fetch API / Ajax (XHR)]()
> - [ES6+ ve Modular JavaScript]()

* JavaScript kavramları:
> - [Hoisting](https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)
> - [Bubbling and Capturing](https://javascript.info/bubbling-and-capturing)
> - [Scope](https://developer.mozilla.org/en-US/docs/Glossary/Scope)
> - [Var, Let, and Const](https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/)
> - [Inheritance and Prototype Chain](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
> - [Strict Mode](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Strict_mode)
> - [JavaScript Visualized](https://dev.to/lydiahallie/javascript-visualized-event-loop-3dif)
> - [DOM, Shadow DOM and Virtual DOM](https://www.youtube.com/watch?v=7Tok22qxPzQ)
> - [JavaScript Promises](https://blog.greenroots.info/series/javascript-promises)


## **4. Adım: Version Control Systems**
* [Sürüm Kontrol Sistemleri](https://www.youtube.com/watch?v=zbKdDsNNOhg), zaman içinde kod tabanınızda/dosyalarınızda meydana gelen değişiklikleri izlemenizi sağlar. Herhangi bir sorun olmadan kod tabanının önceki bazı sürümlerine geri dönmenize izin verirler.
* Repo Hosting Services (Depo Barındırma Hizmetleri): En ünlüsü [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/) ve [BitBucket](https://bitbucket.org/product/) olan farklı depo barındırma hizmetleri vardır. GitHub'da bir hesap oluşturmanızı tavsiye ederim çünkü OpenSource çalışmalarının çoğunun yapıldığı ve geliştiricilerin çoğunun bulunduğu yer burasıdır.


## **5. Adım: Package Managers**
* [npm](https://www.npmjs.com/), npm Inc. tarafından sağlanan JavaScript programlama dili için bir paket yöneticisidir. npm, JavaScript çalışma zamanı ortamı Node.js için varsayılan paket yöneticisidir.
* [yarn](https://classic.yarnpkg.com/en/docs/getting-started), npm'ye (paket yöneticisi) alternatif olarak hız, tutarlılık, kararlılık ve güvenlik sağlayan Node.js JavaScript çalıştırma ortamı için Facebook tarafından 2016 yılında geliştirilen bir yazılım paketleme sistemidir.
* [pnpm](https://pnpm.io/), Node.js için alternatif bir paket yöneticisidir. pnpm'nin temel amacı, tüm paketleri global (merkezi) bir mağazada tutmak ve gerektiğinde diğer projeler için de hard linkler oluşturarak kullanmaktır.

## **6. Adım: Build Tools**
* Görev çalıştırıcılar otomatik olarak komutları yürütür ve perde arkasında işlemleri yürütür. Bu, aksi takdirde kendinizi tekrarlamak için çok fazla zaman harcayacağınız sıradan, tekrarlayan görevleri gerçekleştirerek iş akışınızı otomatikleştirmenize yardımcı olur.
* Görev çalıştırıcıların yaygın kullanımları, geliştirme sunucularını döndürme, kod derleme (ör. SCSS'den CSS'ye), linter çalıştırma, dosyaları bilgisayarınızdaki yerel bir bağlantı noktasından sunma ve çok daha fazlası gibi çok sayıda geliştirme görevini içerir.
* Bu adımda öğreneceğiniz alt başlıklar kısaca şu şekildedir;
> - [Linters and Formatters](https://www.testim.io/blog/what-is-a-linter-heres-a-definition-and-quick-start-guide/): Linter, kodu analiz etmek ve hataları, sözdizimi hatalarını, biçimsel tutarsızlıkları ve şüpheli yapıları keşfetmek için kullanılan bir araçtır. JavaScript için popüler linter'lar arasında ESLint, JSLint ve JSHint bulunur.
> - [Task Runners](https://docs.npmjs.com/cli/v8/using-npm/scripts): Task Runner, sass/scss derlemesini otomatikleştirme, varlıkları gruplama, kaynak kodunu dizme ve yerel sunucuyu çalışırken yeniden yükleme gibi belirli sıkıcı geliştirme görevlerini basitleştirmeye yönelik araçlardır.
> - [Module Bundlers](https://www.freecodecamp.org/news/lets-learn-how-module-bundlers-work-and-then-write-one-ourselves-b2e3fe6c88ae/): Modül paketleyici, JavaScript parçalarını ve bağımlılıklarını alan ve bunları genellikle tarayıcıda kullanılmak üzere tek bir dosyada toplayan bir araçtır. Bazı araçlar: [Vite](https://vitejs.dev/), [Esbuild](https://esbuild.github.io/), [Rollup](https://rollupjs.org/).


## **7. Adım: Frameworks**
* Web çerçeveleri, web uygulamaları yazmak için tasarlanmıştır. Çerçeveler, bir yazılım ürününün veya web sitesinin geliştirilmesine yardımcı olan kitaplık koleksiyonlarıdır.
* Bazı frameworkler şu şekildedir;
> - [React](https://react.dev/): React, kullanıcı arabirimleri oluşturmak için en popüler ön uç JavaScript kitaplığıdır.
> - [Angular](https://angular.io/start): Angular, yönlendirme, form yönetimi, istemci-sunucu iletişimi ve daha fazlası gibi özellikleri içeren iyi entegre edilmiş kitaplıklardan oluşan bir koleksiyon içeren, TypeScript üzerine inşa edilmiş bileşen tabanlı bir ön uç geliştirme çerçevesidir.


## **8. Adım: Modern CSS**
* [Styled Components](https://styled-components.com/): Styled-components, normal CSS yazmanıza ve JavaScript bileşenlerine eklemenize olanak tanıyan bir JS içinde CSS kitaplığıdır. Stil bileşenleri ile, yeni bir stil yapısı öğrenmek zorunda kalmak yerine zaten aşina olduğunuz CSS'yi kullanabilirsiniz.
* [CSS Modülleri](https://github.com/css-modules/css-modules): Tüm sınıf adlarının ve animasyon adlarının varsayılan olarak yerel olarak kapsamlandırıldığı CSS dosyalarıdır.
* [Styled JSX](https://github.com/vercel/styled-jsx): Styled JSX, bileşenlerinize stil vermek için kapsüllenmiş ve kapsamlı CSS yazmanıza izin veren bir JS içinde CSS kitaplığıdır.
* [Emotion](https://emotion.sh/docs/introduction): Emotion, JavaScript ile css stilleri yazmak için tasarlanmış bir kütüphanedir. Kaynak haritalar, etiketler ve test yardımcı programları gibi özelliklerle harika bir geliştirici deneyimine ek olarak güçlü ve öngörülebilir stil kompozisyonu sağlar.


## **9. Adım: CSS Frameworks**
* [Bir CSS çerçevesi](https://en.wikipedia.org/wiki/CSS_framework), kullanıcıya tamamen işlevsel bir CSS stil sayfası sağlar ve HTML’i uygun sınıflar, yapı ve kimliklerle basitçe kodlayarak bir web sayfası oluşturmalarına olanak tanır.
* Bazı frameworkler şu şekildedir;
> - [Tailwind](https://tailwindcss.com/): Tailwind, en temel CSS kullanımlarını sıfırdan yazmanızı tekrar tekrar yazmanızı engelleyen, yazılımcıların ve tasarımcıların işini kolaylaştıran bir CSS framework’üdür. Tailwind, bir UI kiti olmadığı için Bootstrap, Foundation gibi frameworklerden farklıdır.
> - [Material UI](https://mui.com/): Material-UI, Google'ın Materyal Tasarımını uygulayan React bileşenlerini içeren açık kaynaklı bir çerçevedir.


## **10. Adım: Uygulamalarınızı Test Etme**
* Uygulamanızı kullanıcılara teslim etmeden önce, uygulamanızın tasarlandığı gereksinimleri karşıladığından ve garip, istenmeyen şeyler ("hata" olarak adlandırılır) yapmadığından emin olmanız gerekir. Bunu başarmak için uygulamalarımızı farklı şekillerde test ediyoruz.
* Bazı test araçları şu şekildedir:
> - [Jest](https://jestjs.io/): Jest, basitliğe odaklanan keyifli bir JavaScript Test Çerçevesidir. Şunları kullanan projelerle çalışır: Babel, TypeScript, Node, React, Angular, Vue ve daha fazlası.
> - [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/): React Testing Library, React bileşenlerini test etmek için çok hafif bir çözümdür. Daha iyi test uygulamalarını teşvik edecek şekilde, tepki-dom ve tepki-dom/test-utils'in üzerinde hafif yardımcı işlevler sağlar. Başlıca yol gösterici ilkesi şudur: Testleriniz yazılımınızın kullanım şekline ne kadar benzerse, size o kadar güven verebilirler.

## **11. Adım: Authentication Strategies**
* Kimlik doğrulama stratejileri, korunan bir kaynağa erişim izni vermek amacıyla bir kullanıcının veya sistemin kimliğini doğrulamak için kullanılan yöntem veya tekniklerdir. Aşağıdakiler dahil kullanılabilecek birkaç farklı kimlik doğrulama stratejisi vardır:

> - Basic Authentication
> - Session Based Authentication
> - Token Based Authentication
> - JWT Authentication
> - OAuth
> - SSO

* Bunların hepsini, nasıl uygulanacağını ve işin püf noktalarını baştan öğrenmenize gerek yok. Ancak ne olduklarını ve nasıl çalıştıklarını bilmek önemlidir. Bu, uygulamanız için bir kimlik doğrulama stratejisi seçerken daha iyi kararlar almanıza yardımcı olacaktır.


## **12. Adım: TypeScript**
* [TypeScript](https://www.tutorialspoint.com/typescript/index.htm), JavaScript'i temel alan ve size her ölçekte daha iyi araçlar sağlayan, türü kesin olarak belirlenmiş bir programlama dilidir.



### **Kaynakça:**
* [Wikipedia](https://tr.wikipedia.org/wiki/HTML)
* [Roadmap](https://roadmap.sh/frontend)

**Yol haritamız buraya kadardı. Fakat iş burada bitmedi. Geriye sizin yapacağınız projeler kaldı. Yakın bir zamanda Front End ile ilgili proje fikirleri de paylaşacağım.**

_**Not: Yol haritasının Ekstra bölümü daha sonra yayınlanacaktır. Ekstra bölümünde daha sonra araştırıp öğrendiğim ve daha sonra da öğrenilebilir olan konuları ele alacağım.**_

