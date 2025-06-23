# Introduction to Git and GitHub

IBM Developer Skills Network'in "Introduction to Git and GitHub" kursunun eğitim materyali. Bu proje, Git ve GitHub'ın temel kavramlarını öğrenmek için geliştirilmiş basit faiz hesaplama uygulamalarını içerir.

## 🎯 Proje Amacı

Bu proje, Git ve GitHub'ın temel kavramlarını öğrenmek için tasarlanmış eğitim materyalidir. Basit ve bileşik faiz hesaplama uygulamaları üzerinden versiyon kontrol sistemi pratikleri yapılır.

## 📊 Hesaplama Uygulamaları

### 1. Simple Interest Calculator (Basit Faiz)
- **Dosya**: `simple-interest.sh`
- **Dil**: Bash Script
- **Formül**: `simple interest = p * t * r`
- **Girdi**: Principal (p), Time (t), Rate (r)
- **Çıktı**: Basit faiz miktarı

### 2. Compound Interest Calculator (Bileşik Faiz)
- **Dosya**: `compound_interest.py`
- **Dil**: Python
- **Formül**: `compound interest = p * (1 + r/100)^t`
- **Girdi**: Principal (p), Time (t), Rate (r)
- **Çıktı**: Bileşik faiz miktarı

## 🚀 Kurulum ve Çalıştırma

### Basit Faiz Hesaplayıcı (Bash)
```bash
# Dosyayı çalıştırılabilir yapın
chmod +x simple-interest.sh

# Uygulamayı çalıştırın
./simple-interest.sh
```

### Bileşik Faiz Hesaplayıcı (Python)
```bash
# Python ile çalıştırın
python compound_interest.py
```

## 📁 Proje Yapısı

```
jbbmo-Introduction-to-Git-and-GitHub/
├── .github/                    # GitHub özel dosyaları
│   ├── ISSUE_TEMPLATE/        # Issue şablonları
│   └── workflows/             # GitHub Actions
├── compound_interest.py       # Python bileşik faiz hesaplayıcı
├── simple-interest.sh         # Bash basit faiz hesaplayıcı
├── README.md                  # Bu dosya
├── LICENSE                    # Apache 2.0 lisansı
├── CODE_OF_CONDUCT.md         # Davranış kuralları
├── CONTRIBUTING.md            # Katkı rehberi
└── .gitignore                 # Git ignore dosyası
```

## 🎓 Öğrenme Hedefleri

Bu proje şu Git ve GitHub konularını kapsar:

- ✅ **Repository Oluşturma**: Yeni repo başlatma
- ✅ **Commit İşlemleri**: Değişiklikleri kaydetme
- ✅ **Branch Yönetimi**: Dal oluşturma ve birleştirme
- ✅ **Pull Request**: Değişiklik önerileri
- ✅ **Collaboration**: Takım çalışması
- ✅ **Version Control**: Versiyon kontrol sistemi

## 🛠️ Kullanılan Teknolojiler

- **Git**: Versiyon kontrol sistemi
- **GitHub**: Kod barındırma platformu
- **Python**: Bileşik faiz hesaplama
- **Bash**: Basit faiz hesaplama
- **Markdown**: Dokümantasyon

## 📝 Örnek Kullanım

### Basit Faiz Hesaplama
```bash
Enter the principal: 1000
Enter rate of interest per year: 5
Enter time period in years: 2
The simple interest is: 100
```

### Bileşik Faiz Hesaplama
```python
Enter the principal amount: 1000
Enter the time period: 2
Enter the rate of interest: 5
The compound interest is 110.25
```

## 🤝 Katkıda Bulunma

Bu proje eğitim amaçlı geliştirilmiştir. Katkıda bulunmak için:

1. Fork yapın
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Branch'inizi push edin (`git push origin feature/AmazingFeature`)
5. Pull Request açın

## 📄 Lisans

Bu proje [Apache License 2.0](LICENSE) lisansı altında lisanslanmıştır.

**Copyright 2022 IBM Developer Skills Network**

## 🔗 İlgili Kaynaklar

- [IBM Developer Skills Network](https://skills.network/)
- [Introduction to Git and GitHub](https://skills.network/course/introduction-to-git-and-github)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)

## ⚠️ Önemli Not

Bu uygulamalar sadece eğitim amaçlıdır. Üretim ortamında kullanmayınız.

---

IBM Developer Skills Network'in Git ve GitHub eğitiminin bir parçası olarak geliştirilmiştir. 🚀
