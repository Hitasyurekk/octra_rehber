# Şimdi ilk TX'i atarak ilk hafta görevini tamamlayacağız.

**Öncelikle altta ki kodu kopyalarak tamamen çalıştırın**
```

git clone https://github.com/octra-labs/octra_pre_client.git
cd octra_pre_client
python3 -m venv venv
source venv/bin/activate # for windows use: venv\Scripts\activate
pip install -r requirements.txt
cp wallet.json.example wallet.json

``` 
---

# Wallet Bilgilerini Değiştirme 

**Bu komut ile wallet bilgilerini değiştireceğiz.**

``` nano wallet.json ```

```
{
  "priv": "private-key-here",
  "addr": "octxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "rpc": "https://octra.network"
}
```
**Son adım çalıştırma**
```
./run.sh       # on linux/mac
run.bat        # on windows
```
