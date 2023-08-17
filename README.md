# GitHub Giriş
GitHub, web tabanlı bir platform olarak kullanılan bir kod barındırma ve sürüm kontrol platformudur. Geliştiriciler, projelerini GitHub'a yükleyerek kodlarını depolayabilir, paylaşabilir ve işbirliği yapabilirler. GitHub, özellikle açık kaynak yazılım projeleri için popülerdir, çünkü geliştiricilere kodlarını diğerlerine açık bir şekilde paylaşma ve katkıda bulunma imkanı sunar. Pull requestler, kod incelemeleri ve issue takibi gibi özellikleriyle geliştirme süreçlerini kolaylaştırır ve daha işbirlikçi hale getirir.

# README.md Nedir?
`README.md`, bir projenin kök dizininde bulunan ve projenin temel bilgilerini ve belgelerini içeren bir metin dosyasının adıdır. "README" kısaltması, "Read Me" ifadesinden gelir, yani dosyanın kullanıcılara ve diğer geliştiricilere projeyi nasıl kullanacaklarına dair rehberlik sağlayacağını ifade eder.

Markdown (genellikle `.md` uzantılı dosyalar olarak görünür) biçimlendirmesini kullanarak yazılır. Markdown, metni basit ve hızlı bir şekilde zengin biçimlendirmelerle düzenlemenizi sağlayan bir hafif işaretleme dilidir.

Bir `README.md` dosyası, aşağıdaki gibi temel bilgileri içerebilir:
* **Proje Açıklaması:** Projeyi neyin oluşturduğu ve hangi amaçla kullanıldığına dair bir genel açıklama.
* **Kurulum Talimatları:** Projeyi nasıl kurulacağına dair adımlar veya gereksinimler.
* **Kullanım Kılavuzu:** Projeyi nasıl kullanacaklarınıza dair talimatlar, komutlar ve örnekler.
* **Katılım Kuralları:** Açık kaynak projelerde, diğer geliştiricilerin projeye katkıda bulunma yönergeleri.
* **Lisans Bilgisi:** Projeyi kullanma ve dağıtma hakkında bilgi içeren lisans bilgileri.
* **İletişim Bilgileri:** Proje sahibinin veya ekibinin iletişim bilgileri.
* **Sürüm Geçmişi:** Farklı sürümlerde yapılan değişiklikleri ve güncellemeleri içeren bir sürüm geçmişi.

`README.md` dosyası, projenizin kullanıcıları ve diğer geliştiricileri için ilk elde başvurulacak kaynak olabilir. Projeyi anlamak, kullanmak ve geliştirmek isteyenler için önemli bir rehberdir.

# Github üzerinden Kendi İnternet Sitenizi Oluşturun
GitHub ile kendi websitesini oluşturmak oldukça yaygın bir uygulamadır.

1. **GitHub Hesabı Oluşturun:** Eğer bir GitHub hesabınız yoksa, https://github.com adresine giderek ücretsiz bir hesap oluşturun.
2. **Yeni Bir Repository (Depo) Oluşturun:** GitHub hesabınıza giriş yaptıktan sonra sağ üst köşede bulunan "New" butonuna tıklayarak yeni bir repository oluşturun. Repository adını `kullaniciadi.github.io` olarak belirleyin. Buradaki "kullaniciadi" kısmını GitHub kullanıcı adınızla değiştirin. Bu adım, GitHub Pages özelliğini kullanarak websitesi barındırmak için gereklidir.
3. **Website Dosyalarınızı Hazırlayın:** Oluşturduğunuz repository içine websitesi dosyalarınızı yerleştirin. HTML, CSS, JavaScript dosyalarını bu depoya ekleyerek websitenizin tasarımını ve içeriğini oluşturabilirsiniz. Ayrıca ana dizinde `index.html` dosyası olması gerektiğini unutmayın. Bu dosya, websitesinin ana sayfası olarak görüntülenecektir.
4. **README.md Dosyası Oluşturun:** Ana dizinde bir `README.md` dosyası oluşturarak, websitesi hakkında temel bilgileri açıklayabilirsiniz. Bu dosya, GitHub'un websitesini ziyaret edenlere projeniz hakkında hızlıca bilgi vermeniz için kullanılır.
5. **Commit ve Push İşlemleri:** Hazırladığınız dosyaları repository'nize yüklemek için "Commit" ve "Push" işlemlerini gerçekleştirin. Bu, değişikliklerin GitHub'a kaydedilmesini sağlar.

6. **GitHub Pages Ayarları:** GitHub Pages özelliğini etkinleştirmek için repository'nin ayarlarına gidin. "Settings" (Ayarlar) sekmesine tıklayın ve sayfanın aşağısına ilerleyin. GitHub Pages bölümünde "Source" (Kaynak) seçeneğini "main" veya "master" (başka bir varsayılan dal da olabilir) olarak ayarlayın. Bu, GitHub'ın websitesini bu dalın içeriğiyle güncelleyeceği anlamına gelir.

7. **Websitenizi Kontrol Edin:** GitHub Pages özelliği etkinleştirildikten sonra, websiteniz `kullaniciadi.github.io` adresinde yayınlanmaya başlar. Tarayıcıdan bu adresi ziyaret ederek websitesinin canlı halini görüntüleyebilirsiniz.

8. **Düzenlemeler ve Güncellemeler:** Websitesinde yapacağınız güncellemeleri yapın ve dosyaları repository'ye yükleyerek GitHub Pages üzerinde güncel halde görüntülemeye devam edin.

Bu adımları izleyerek GitHub Pages üzerinde kendi websitenizi oluşturabilir ve yönetebilirsiniz. Özellikle HTML, CSS ve temel JavaScript bilgisine sahip olmanız, websitesi tasarımını ve işlevselliğini özelleştirmenize yardımcı olacaktır.

# Github Desktop Nedir?
GitHub Desktop, masaüstü bilgisayarlarınızda GitHub projeleriyle etkileşimde bulunmanızı kolaylaştıran bir uygulamadır. Bu uygulama, Git adlı dağıtık sürüm kontrol sistemiyle entegre çalışarak, kod depolama, sürüm yönetimi ve işbirliği süreçlerini daha kullanıcı dostu bir arayüz üzerinden yönetmenize yardımcı olur. GitHub Desktop, özellikle yeni başlayan geliştiriciler için Git ve GitHub işlemlerini daha erişilebilir hale getirirken, deneyimli geliştiricilerin de iş akışını hızlandırmasına yardımcı olabilir. **Github Desktop**'u indirmek için [burayı tıklayın](https://desktop.github.com).

# Repository Nasıl Oluşturulur?
GitHub'da bir "repository" (depot) oluşturmak oldukça basit ve hızlı bir işlemdir.

1. **GitHub Hesabına Giriş Yap:** Öncelikle https://github.com adresine giderek GitHub hesabınıza giriş yapın. Hesabınız yoksa ücretsiz bir hesap oluşturun.
2. **"New" (Yeni) Butonuna Tıkla:** Ana sayfanın sağ üst köşesinde "New" (Yeni) butonuna tıklayın. Bu buton, yeni bir repository oluşturmanızı sağlar.
3. **Repository Adını ve Açıklamasını Gir:** Yeni repository oluşturma sayfasında, repository için bir ad belirleyin. Bu ad genellikle projenizin adını yansıtmalıdır. Ayrıca, repository için kısa bir açıklama ekleyin. Bu açıklama, projenizin ne hakkında olduğunu anlatmalıdır.
4. **Gizlilik Ayarını Seç:** Repository'nin gizlilik düzeyini seçin. Eğer projenizi herkese açık olarak paylaşmak isterseniz "Public" (Açık) seçeneğini seçebilirsiniz. Eğer sadece belirli kullanıcıların erişebileceği bir repository oluşturmak isterseniz "Private" (Özel) seçeneğini seçebilirsiniz. Unutmayın ki "Private" seçeneği ücretli GitHub hesaplarında kullanılabilir.
5. **Lisans Seçeneğini Belirle (Opsiyonel):** Eğer projenize bir lisans eklemek isterseniz, lisans seçeneklerinden birini seçebilirsiniz. Lisanslar, projenizin kullanım ve dağıtım haklarını düzenler.
6. **Gitignore ve Lisans Dosyası Seç (Opsiyonel):** Eğer projeniz için belirli dosyaların veya klasörlerin izlenmemesini istiyorsanız `.gitignore` dosyası seçebilirsiniz. Ayrıca lisans dosyası eklemek isterseniz bu adımda bunu da yapabilirsiniz.
7. **"Create Repository" (Repository Oluştur) Butonuna Tıkla:** Gerekli bilgileri girdikten sonra "Create Repository" (Repository Oluştur) butonuna tıklayarak yeni repository'nizi oluşturabilirsiniz.

Bu adımları takip ederek GitHub üzerinde kolayca bir repository oluşturabilirsiniz. Oluşturduğunuz repository içine kodlarınızı yükleyebilir, sürüm yönetimi yapabilir ve işbirliği yapabilirsiniz.

# Repository Nasıl Yayınlanır?
Bir GitHub repository'sini yayınlamak, projenizi diğerlerine açık bir şekilde paylaşmanızı ve erişilebilir hale getirmenizi sağlar.

1. **Repository Oluşturun:** Eğer henüz bir repository oluşturmadıysanız, öncelikle GitHub hesabınıza giriş yaparak yeni bir repository oluşturun. Repository adı ve açıklamasını ekleyin, gizlilik ayarlarını belirleyin.
2. **Kod ve Dosyaları Yükleyin:** Yayınlamak istediğiniz kodları ve projenin dosyalarını repository'nize yükleyin. Bu işlem için GitHub Desktop veya Git komut satırı gibi araçları kullanabilirsiniz.
3. **README.md Dosyası Oluşturun:** Repository'nizde ana dizinde bir `README.md` dosyası oluşturun. Bu dosya, projenizi ziyaret edenlere projeniz hakkında temel bilgiler sunar.
4. **Gerekirse Lisans ve `.gitignore` Ekleyin:** Eğer projenize bir lisans eklemek veya belirli dosyaları `.gitignore` ile izlememek istiyorsanız, bu dosyaları da ekleyin.
5. **Push İşlemi:** Yaptığınız değişiklikleri commit edip (kaydet) ve ardından "Push" işlemi ile GitHub'a gönderin. Bu, kodlarınızın GitHub repository'sine yüklenmesini sağlar.
6. **GitHub Pages Ayarları (Opsiyonel):** Eğer bir web sitesi yayınlamak istiyorsanız, GitHub Pages özelliğini kullanarak bu işlemi gerçekleştirebilirsiniz. Repository'nizin ayarlarında, GitHub Pages bölümünde "Source" (Kaynak) seçeneğini belirleyerek websitesini yayınlayabilirsiniz.
7. **Repository'nizi Paylaşın:** Repository'nizi başkalarıyla paylaşmak için repository sayfanızın üst kısmında bulunan URL'yi kopyalayarak diğer geliştiricilerle ve ilgilenenlerle paylaşabilirsiniz.
8. **İşbirliği ve Çekme İstekleri:** Repository'nizi paylaştığınızda diğer geliştiriciler de projenizde işbirliği yapabilirler. Çekme istekleri (pull request) mekanizması ile diğer geliştiricilerin değişikliklerini entegre edebilirsiniz.

Repository'nizi yayınlamak, projenizi daha geniş bir toplulukla paylaşmanıza ve işbirliği yapmanıza olanak sağlar. Ayrıca GitHub'ın sağladığı işbirliği özellikleri ile projenizi daha geliştirilebilir hale getirebilirsiniz.

# Repository Nasıl Güncellenir?
Bir GitHub repository'sini güncellemek, projenizdeki değişiklikleri kaydetmek, yeni kodları eklemek veya mevcut kodları düzenlemek anlamına gelir.

1. **Kod Değişikliklerini Yapın:** Projede yapmak istediğiniz değişiklikleri gerçekleştirin. Bu, mevcut dosyalarda düzenlemeler yapmak veya yeni dosyalar eklemek olabilir.
2. **Değişiklikleri Kaydet (Commit):** Yaptığınız değişiklikleri commit (kaydet) ederek yereldeki projenizde sabitleyin. Bu, değişiklikleri Git sürüm kontrol sistemiyle kaydetmenizi sağlar.
3. **GitHub Desktop Kullanıyorsanız:**
   - GitHub Desktop gibi araçlarla çalışıyorsanız, yapmış olduğunuz değişiklikleri commit ederek ardından "Push" butonuna tıklayarak GitHub'a gönderin. Bu, yereldeki değişikliklerin uzak sunucuya yüklenmesini sağlar.
4. **Komut Satırını Kullanıyorsanız:**
   - Eğer komut satırını kullanıyorsanız, `git push` komutunu kullanarak değişiklikleri GitHub'a yükleyin.
5. **Çekme İstekleri (Pull Request):** Eğer başkalarının projenize katkıda bulunmasını istiyorsanız, çekme istekleri (pull request) mekanizmasını kullanarak bu değişiklikleri projenize entegre edebilirsiniz. Bu, diğer geliştiricilerin değişikliklerini projenize eklemenizi sağlar.
6. **GitHub Pages Kullanıyorsanız (Opsiyonel):** Eğer GitHub Pages ile websitesi yayınlıyorsanız, güncellemeleri yaptıktan sonra sayfanızın güncellendiğini kontrol edin.
7. **Projeyi Diğerleriyle Paylaşın:** Değişiklikleri yaptıktan ve güncellemeleri yükledikten sonra projenizi paylaşmayı unutmayın. Repository sayfanızdaki URL'yi paylaşarak diğer geliştiricilerin ve ilgilenenlerin güncel projenizi görmesini sağlayabilirsiniz.

Repository güncellemek, projenizi geliştirmek ve diğer geliştiricilerle işbirliği yapmak için önemlidir. Her güncelleme, projenizin daha iyi hale gelmesine ve genişleyen bir toplulukla daha iyi iletişim kurmanıza yardımcı olur.

# Forklama Nedir?
"Forklama", GitHub platformunda bulunan bir repository'yi kendi GitHub hesabınıza kopyalamanızı sağlayan bir işlemdir. Bu işlem, özellikle açık kaynak projelerde katkıda bulunmayı veya projeyi kişisel olarak kullanmayı amaçlayan geliştiriciler için önemlidir.

* **Açık Kaynak Projelerde Forklama:** Bir açık kaynak projenin repository'sini forklayarak, projenin bir kopyasını kendi GitHub hesabınıza alabilirsiniz. Bu, projeyi inceleme, değişiklik yapma veya önerilerde bulunma fırsatı sunar. Ana projede yapacağınız değişiklikleri kendi fork'ınızda gerçekleştirebilirsiniz.
* **Kişisel Kullanım İçin Forklama:** Aynı şekilde, kendi kişisel projelerinizde de forklama kullanabilirsiniz. Örneğin, başka bir projeden başlayarak kendi projenizi oluşturabilir veya temel bir yapıyı kullanarak kendi işinize uygun bir projeyi başlatabilirsiniz.
* **Forklama ve Çekme İstekleri (Pull Request):** Forkladığınız projeyi düzenledikten sonra, orijinal projeye değişikliklerinizi entegre etmek için "çekme isteği" (pull request) oluşturabilirsiniz. Bu, projenin sahibine ve yöneticilerine yaptığınız değişiklikleri inceleyip, projeye eklemeleri için istekte bulunmanızı sağlar.
* **Bağlantı ve Senkronizasyon:** Forkladığınız projenin orijinali güncellendiğinde, forkladığınız kopyanız otomatik olarak güncellenmez. Bu nedenle projenin orijinaline yaptığınız değişiklikleri veya güncellemeleri almak istiyorsanız, "upstream" (ana kaynak) olarak belirtilen orijinal projeden güncellemeleri çekmelisiniz.
Forklama, açık kaynak topluluklarında işbirliği yapmayı ve projeleri kendi ihtiyaçlarınıza uyarlamayı kolaylaştıran bir işlemdir. GitHub platformu, forklama ve çekme istekleri gibi özellikleri ile açık kaynak geliştirme süreçlerini daha etkili ve kolay hale getirir.

# Teşekkürler
Bu rehber `ChatGPT` ile birlikte hazırlanmış ve sunulmuştur. Aklınıza takılan konular için benimle iletişime geçiniz.

* [YouTube](https://youtube.com/@ilhamitugral)
* [Twitter](https://twitter.com/ilhamitugral)
* [Instagram](https://instagram.com/ilhamitugral)
* [Threads](https://threads.net/@ilhamitugral)
