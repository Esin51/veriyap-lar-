## 📌 Task: Creating the README.md File

Bu belge, Git komutlarını nasıl kullandığımı, yerel Git iş akışı ile GitHub iş akışı arasındaki farkları, karşılaştığım zorlukları, commit kararlarımı nasıl verdiğimi ve süreç boyunca yapay zekadan nasıl yardım aldığımı detaylandırmaktadır.

---

## 🧪 Kullandığım Git Komutları

```bash
# Yeni bir Git deposu başlat
 git init

# GitHub'dan var olan bir depoyu klonla
git clone <repo_url>

# Değişiklikleri sahnele (staging area'ya ekle)
git add <dosya_adi>

# Sahneye alınan değişiklikleri commit et
git commit -m "Açıklayıcı commit mesajı"

# Commitleri uzak (remote) depoya gönder
git push origin main

# Uzak depodaki en güncel değişiklikleri al
git pull origin main

# Yeni bir dal (branch) oluştur
git branch <dal_adi>

# Belirli bir dala geç
git checkout <dal_adi>

# Bir dalı mevcut dala birleştir
git merge <dal_adi>
```

---

## 🔄 Yerel Git İş Akışı ile GitHub İş Akışı Arasındaki Farklar

### 🏠 Yerel Git İş Akışım:

- Değişiklikleri kendi bilgisayarımda yaptım.
- `git add` komutuyla değişiklikleri sahneledim.
- `git commit` komutuyla değişiklikleri kaydettim.
- Tüm süreç yerelde kaldı, ancak `git push` ile uzak depoya gönderdim.

### ☁ GitHub İş Akışım:

- Değişiklikleri `git push` ile GitHub'a yükledim.
- Pull request açarak başkalarıyla iş birliği yaptım.
- `git merge` veya GitHub arayüzü ile dalları birleştirdim.
- `git pull` ile uzak depodaki değişiklikleri kendi yerel depoma çektim.

---

## ⚠ Karşılaştığım Zorluklar

- Yerel ve uzak depoların farkını tam olarak anlamak.
- Merge işlemleri sırasında yaşanan çakışmaları (conflict) çözmek.
- Git komutlarının doğru sırasını hatırlamak.
- Sahneleme (staging) ve sahne dışı (unstaged) değişiklikleri yönetmek.

---

## ✅ Commit Yapmaya Ne Zaman Karar Verdim?

- Önemli bir özellik ekledikten veya hata düzelttikten sonra.
- Uzak depodan değişiklikleri almadan önce (`git pull` öncesi).
- Merge çakışmalarını çözdükten sonra kodun stabil olduğundan emin olmak için.
- Dal değiştirmeden (`git checkout`) önce yaptığım işleri kaybetmemek için.

---

## 🤖 Yapay Zeka Bana Nasıl Yardımcı Oldu?

### 🔍 AI ile Deneyimim:

Yapay zekadan aşağıdaki konularda destek aldım:

- Yerel ve uzak iş akışlarının farklarını anlamak.
- Merge çakışmalarını nasıl çözebileceğimi öğrenmek.
- Anlamlı commit mesajları yazmak için en iyi uygulamaları keşfetmek.

### 💌 Kullandığım Platform:

*ChatGPT* kullanarak Git komutları, iş akışları ve hata giderme konularında rehberlik aldım.

### 📚 Öğrendiklerim:

- İş birliği için etkili bir Git iş akışı nasıl yönetilir.
- Açıklayıcı ve düzenli commit mesajlarının önemi.
- Merge çakışmalarının nasıl çözülebileceği.

---

## 📚 Ek Kaynaklar

- [Git Dokümantasyonu](https://git-scm.com/doc)
- [GitHub Dökümanları](https://docs.github.com/)

---

## 🖼️ Örnek Git İş Akışı

\
Şekil: Örnek Git İş Akışı

