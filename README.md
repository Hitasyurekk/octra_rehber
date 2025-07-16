
-----

# Cüzdan Oluşturucu Kurulum Rehberi

Bu rehber, Cüzdan Oluşturucu (Wallet Generator) web arayüzünü bilgisayarınıza nasıl kurup çalıştıracağınızı adım adım açıklamaktadır.

## Genel Bakış

Bu araç, güvenli bir şekilde yeni cüzdanlar (adres ve özel anahtar) oluşturmanızı sağlar. Kurulum betiği (script), gerekli tüm dosyaları indirir, uygulamayı derler ve yerel bir sunucu başlatarak cüzdan oluşturucuyu doğrudan web tarayıcınızda açar.

## Hızlı Kurulum

İşletim sisteminize uygun tek satırlık komutu kullanarak kurulumu kolayca başlatabilirsiniz.

### Linux / macOS

Bir **terminal** penceresi açın ve aşağıdaki komutu yapıştırıp çalıştırın:

```bash
curl -fsSL https://octra.org/wallet-generator.sh | bash
```

### Windows

**Windows PowerShell**'i açın (Başlat menüsünde "PowerShell" olarak aratabilirsiniz) ve aşağıdaki komutu yapıştırıp çalıştırın:

```powershell
powershell -c "irm octra.org/wallet-generator.ps1 | iex"
```

-----
**Linux/Mac için:**

```bash
# Betiğe çalıştırma izni verin (gerekirse)
chmod +x ~/.octra/wallet-generator/start.sh

# Başlatın
~/.octra/wallet-generator/start.sh
```

**Windows için:**
PowerShell'i açıp aşağıdaki komutu çalıştırın:

```powershell
# Betik çalıştırma politikasını ayarlayın (eğer daha önce yapılmadıysa)
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

# Başlatın
& ~/.octra/wallet-generator/start.ps1
```

**Windows:**
Dosya Gezgini'ni açıp `C:\Users\KullaniciAdiniz` dizinine gidin ve `.octra` klasörünü silin veya PowerShell'de aşağıdaki komutu kullanın:

```powershell
Remove-Item -Path ~/.octra -Recurse -Force
```
