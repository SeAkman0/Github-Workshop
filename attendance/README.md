# 📋 Yoklama İşlemleri Rehberi

Bu klasör, GitHub Workshop eğitimine katılan öğrencilerin yoklama kayıtlarını tutmaktadır. Yoklamaya katılmak için aşağıdaki adımları dikkatlice takip edin.

## 🚀 Adım Adım Yoklama Kılavuzu

### 1. Hazırlık
Öncelikle bu repository'yi (depoyu) kendi hesabınıza **Fork** edin.

### 2. Dosya Oluşturma
Bu klasör (`attendance/`) içerisine yeni bir dosya oluşturun.

- **Dosya Adı:** Okul numaranız olmalıdır.
- **Uzantı:** `.txt`
- **Örnek:** `210316011.txt`

### 3. İçerik Ekleme
Oluşturduğunuz dosyanın içerisine **SADECE** öğrenci e-posta adresinizi yazın.

- **Format:** `ogrenci_no@ogr.cbu.edu.tr`
- **Örnek İçerik:**
  ```text
  210316011@ogr.cbu.edu.tr
  ```

> [!WARNING]
> Dosya adı ile e-posta adresindeki numara **BİREBİR AYNI** olmalıdır.
> - ✅ Dosya: `210316011.txt` -> E-posta: `210316011@ogr.cbu.edu.tr`
> - ❌ Dosya: `ahmet.txt` -> E-posta: `210316011@ogr.cbu.edu.tr` (Kabul Edilmez)

### 4. Pull Request (PR) Açma
Değişikliklerinizi kaydedin (Commit) ve bu repoya bir **Pull Request** gönderin.

---

## ❓ Sıkça Sorulan Sorular

### Neden PR açıyorum?
Bu işlem, gerçek hayattaki **Açık Kaynak (Open Source)** projelere katkı yapma sürecini simüle etmektedir. Kendi dosyanızı oluşturup ana projeye "merge" (birleştirme) isteği gönderiyorsunuz.

### "Check Failed" hatası alıyorum, neden?
Bunun birkaç sebebi olabilir:
1. ❌ **Dosya Adı Uyuşmazlığı:** Dosya adınız ve e-postanızdaki numara farklıdır.
2. ❌ **Yanlış Format:** E-posta adresiniz `@ogr.cbu.edu.tr` uzantılı değildir veya hatalı yazılmıştır.
3. ❌ **Güvenlik İhlali:** Başkasının dosyasını silmeye veya değiştirmeye çalışmış olabilirsiniz (Sadece kendi dosyanızı ekleyin).
4. ❌ **Dosya Yeri:** Dosyayı `attendance/` klasörü dışına oluşturmuş olabilirsiniz.

### Başkasının dosyasını görebilir miyim?
Evet, bu klasördeki tüm dosyalar herkese açıktır. Ancak başkasının dosyasını **değiştiremezsiniz**, sistem buna izin vermez.
