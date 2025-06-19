# 🚀 Modern HTML Form Templates

Bu repository, modern ve responsive HTML form template'lerini içerir. Tüm template'ler **TailwindCSS** ile stillendirilmiş ve **tamamen açık kaynak**tır.

## ✨ Özellikler

- 🌙 **Dark/Light Mode** desteği
- 📱 **Tamamen responsive** tasarım
- ✅ **Form validasyonu** ve gerçek zamanlı kontroller
- 🎨 **Modern ve temiz** arayüz
- 🚀 **Plug & Play** - Doğrudan kullanıma hazır
- 🔧 **Kolay özelleştirme**
- 🌍 **Türkçe dil desteği**

## 📁 Template'ler

### 1. 📦 Online Sipariş Formu (`index.html`)

- **Kullanım Alanı**: E-ticaret, sipariş sistemleri
- **Özellikler**:
  - Kişisel bilgi formları
  - Adres bilgileri
  - Telefon formatlaması
  - E-posta validasyonu
  - Posta kodu kontrolü

### 2. 🔐 Giriş Formu (`index1.html`)

- **Kullanım Alanı**: Login sistemleri, üye girişi
- **Özellikler**:
  - E-posta/şifre validasyonu
  - Şifre göster/gizle
  - "Beni hatırla" seçeneği
  - Sosyal medya giriş butonları
  - Demo bilgileri

### 3. 📧 Newsletter Abonelik Formu (`index4.html`)

- **Kullanım Alanı**: E-posta pazarlama, haber bülteni
- **Özellikler**:
  - E-posta validasyonu
  - İlgi alanı seçimi
  - GDPR uyumlu onay sistemi
  - Minimalist tasarım

### 4. 📅 Rezervasyon Formu (`index5.html`)

- **Kullanım Alanı**: Randevu sistemleri, rezervasyon
- **Özellikler**:
  - Tarih/saat seçimi
  - Hizmet türü seçimi
  - Kişi sayısı
  - Gelecek tarih kontrolü
  - Telefon formatlaması

## 🚀 Hızlı Başlangıç

1. **Template'i indirin**:

   ```bash
   git clone https://github.com/your-username/html-form-templates
   cd html-form-templates
   ```

2. **Favori template'inizi seçin**:

   - `index.html` - Sipariş formu
   - `index1.html` - Giriş formu
   - `index4.html` - Newsletter formu
   - `index5.html` - Rezervasyon formu

3. **Doğrudan kullanmaya başlayın**:
   ```bash
   # Herhangi bir web tarayıcısında açın
   open index.html
   ```

## 🎨 Özelleştirme

### Renk Teması Değiştirme

Template'lerde kullanılan ana renkler:

- **Mavi**: `blue-600`, `blue-700`
- **Mor**: `purple-600`, `purple-700`
- **Pembe**: `pink-600`, `pink-700`

Renkleri değiştirmek için CSS class'larını düzenleyin:

```html
<!-- Mevcut -->
<button class="bg-blue-600 hover:bg-blue-700">
	<!-- Yeşil tema için -->
	<button class="bg-green-600 hover:bg-green-700"></button>
</button>
```

### Form Alanları Ekleme

Yeni form alanı eklemek için mevcut yapıyı takip edin:

```html
<div>
	<label for="newField" class="block text-sm font-medium text-gray-700 dark:text-gray-300 mb-2"> Yeni Alan * </label>
	<input
		type="text"
		id="newField"
		name="newField"
		required
		class="w-full px-4 py-3 border border-gray-300 dark:border-gray-600 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent bg-white dark:bg-gray-700 text-gray-900 dark:text-white placeholder-gray-500 dark:placeholder-gray-400 transition-all duration-200"
		placeholder="Placeholder metni"
	/>
	<div class="error-message text-red-500 text-sm mt-1 hidden"></div>
</div>
```

## 🔧 Teknik Detaylar

### Kullanılan Teknolojiler

- **HTML5**: Semantic markup
- **TailwindCSS**: Utility-first CSS framework
- **Vanilla JavaScript**: Form validasyonu ve etkileşimler
- **CSS3**: Custom animasyonlar ve geçişler

### Tarayıcı Desteği

- ✅ Chrome (son 3 versiyon)
- ✅ Firefox (son 3 versiyon)
- ✅ Safari (son 3 versiyon)
- ✅ Edge (son 3 versiyon)

### Form Validasyon Özellikleri

- **Real-time validasyon**: Kullanıcı yazdıkça kontrol
- **E-posta formatı**: RFC compliant regex
- **Telefon formatlaması**: Otomatik formatting
- **Tarih kontrolü**: Geçmiş tarih engelleme
- **Required alan kontrolü**: Boş alan uyarıları

## 📱 Responsive Breakpoint'ler

Template'ler aşağıdaki breakpoint'leri kullanır:

- **Mobile**: < 640px
- **Tablet**: 640px - 1024px
- **Desktop**: > 1024px

## 🌙 Dark Mode

Dark mode otomatik olarak localStorage'da saklanır:

```javascript
// Manuel olarak dark mode açma
localStorage.setItem('theme', 'dark')
document.documentElement.classList.add('dark')

// Manuel olarak light mode açma
localStorage.setItem('theme', 'light')
document.documentElement.classList.remove('dark')
```

## 🔒 Güvenlik

Template'ler client-side validasyon içerir. **Üretim ortamında mutlaka server-side validasyon ekleyin**:

- Input sanitization
- SQL injection koruması
- XSS koruması
- CSRF token kontrolü
- Rate limiting

## 🤝 Katkıda Bulunma

1. Repository'yi fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request açın

## 📝 Lisans

Bu proje **MIT License** altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

## 🙏 Teşekkürler

- [TailwindCSS](https://tailwindcss.com/) - Styling framework
- [Heroicons](https://heroicons.com/) - Icon seti
- Tüm katkıda bulunanlar

## 📞 İletişim

- **GitHub Issues**: Bug report ve feature request için
- **Email**: your-email@example.com
- **Twitter**: [@yourusername](https://twitter.com/yourusername)

---

⭐ Bu projeyi beğendiyseniz, lütfen star verin!

**Made with ❤️ for the developer community**
