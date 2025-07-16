
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

**Cüzdan olulturma:**

Her şey başarılı olduktan sonra web sayfası açılacak ve burada bir cüzdan oluşturulacak oluşturulan cüzdan keyi ve bilgisini verilen konumda görebilirsiniz.
<img width="1440" height="755" alt="image" src="https://github.com/user-attachments/assets/3ff3e294-9f7f-46ad-8f03-f220b825545f" />

