# Homm Bitkisel Ürün Keşif Rehberi V22

GitHub Pages sürümü. Depoya bu klasörün içeriğini yükleyin, Settings → Pages → Branch: main / root seçin.

- `index.html` – uygulama
- `products.js` – 367 ürünün verisi (uygulama bunu kullanır)
- `products.json` – aynı verinin JSON kopyası
- `assets/images/thumbs/` – kart görselleri (WebP, en fazla 420 px)
- `assets/images/large/` – büyütme görselleri (WebP, en fazla 1000 px)

Bilgisayarda denemek için: zip'i önce bir klasöre çıkarın (sağ tık → Tümünü ayıkla), sonra `index.html` dosyasına çift tıklayın. Zip'in içinden doğrudan açarsanız görseller ve veri yüklenmez.

## Kendi alan adınızı bağlama

1. GitHub'da depo → Settings → Pages → Custom domain kutusuna alan adınızı yazın (ör. `www.alanadiniz.com`) ve Save'e basın.
2. Alan adını aldığınız firmanın DNS panelinde:
   - `www` için **CNAME** kaydı → `KULLANICIADINIZ.github.io`
   - Kök alan adı (`alanadiniz.com`) için 4 adet **A** kaydı → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
3. DNS'in yayılması birkaç saat sürebilir. Sonra Pages ekranında **Enforce HTTPS** kutusunu işaretleyin.
4. Instagram'da profil bağlantısına `https://www.alanadiniz.com` adresini yazın.

Kaynak: https://www.hommbitkisel.com.tr/urunler-b/tumu (03.11.2026)
