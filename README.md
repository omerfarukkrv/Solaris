Solaris Arşivi (Solaris Archive)
Solaris Arşivi, güneş sistemindeki gezegenleri keşfetmenizi sağlayan, minimalist ve etkileşimli bir web deneyimidir. Modern web teknolojileri kullanılarak tasarlanan bu projede, kullanıcılar uzay boşluğunda akıcı bir yolculuğa çıkar.

✨ Özellikler
3D Gezegen Görselleştirme: Three.js kullanılarak oluşturulmuş yüksek kaliteli küresel modeller.

Akıcı Geçişler: GSAP (GreenSock Animation Platform) ile sahneler arası pürüzsüz animasyonlar.

Gerçek Zamanlı Kontrol: Kullanıcıların gezegen ölçeğini, ufuk çizgisini ve atmosferik ışımayı (glow) anlık olarak değiştirebileceği kontrol paneli.

Dinamik Veri Paneli: Her gezegen için tip, sıcaklık, kütle ve yaş gibi teknik bilgilerin anlık dökümü.

Responsive Tasarım: Tüm ekran boyutlarına uyumlu, tipografi odaklı fütüristik arayüz.

🛠️ Kullanılan Teknolojiler
HTML5 & CSS3: Modern arayüz yerleşimi ve cam (glassmorphism) efektleri için.

Three.js: 3D grafiklerin render edilmesi, ışıklandırma ve doku yönetimi için.

GSAP: UI elementleri ve gezegen geçişleri için gelişmiş animasyon motoru.

GLSL (Shaders): Gezegenlerin etrafındaki atmosferik ışıma efekti için özel shader yazımı.

🚀 Kurulum
Projeyi yerel makinenizde çalıştırmak için şu adımları izleyin:

Depoyu klonlayın:

Bash
git clone https://github.com/kullaniciadi/solaris-arsivi.git
Proje dizinine gidin:

Bash
cd solaris-arsivi
Bir yerel sunucu (Live Server vb.) yardımıyla index.html dosyasını tarayıcınızda açın.

Not: Üç boyutlu dokuların (texture) doğru şekilde yüklenmesi için projenin bir HTTP sunucusu üzerinden çalıştırılması önerilir.

🕹️ Kullanım
Kaydırma (Scroll): Gezegenler arasında ileri/geri gitmek için farenizin tekerleğini kullanın.

Kontrol Paneli: Sağ üst köşedeki panelden "Ölçek", "Ufuk" ve "Işıma" ayarlarını değiştirerek görsel deneyimi kişiselleştirin.

📂 Dosya Yapısı
Plaintext
├── index.html      # Ana yapı ve stil tanımlamaları
├── img/            # Gezegen dokuları (Texture maps)
└── README.md       # Proje dökümantasyonu
📜 Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Daha fazla bilgi için LICENSE dosyasına göz atabilirsiniz.

💡 Geliştirici Notu
Bu proje, web tabanlı grafiklerin gücünü göstermek amacıyla estetik ve performansı bir araya getirmek için geliştirilmiştir. Tasarımda Syncopate ve Inter fontları kullanılarak minimalist bir "bilim kurgu arayüzü" (Sci-Fi UI) hedeflenmiştir.
