1. Stok Takibine Ürün Ekleme
    * *API Metodu:* POST /stock-alerts
    * *Açıklama:* Kullanıcının mağazada tükenmiş olan bir ürünün yeniden satışa çıkması durumunda anında haberdar olmak için o ürünü takibe almasını sağlar.

2. Stok Takip Listesi Görüntüleme
    * *API Metodu:* GET /stock-alerts
    * *Açıklama:* Kullanıcının stok durumunu takip ettiği tüm ürünleri tek bir sayfada liste halinde görmesini ve durumlarını kontrol etmesini sağlar.

3. Stok Takibinden Ürün Silme
    * *API Metodu:* DELETE /stock-alerts/{alertId}
    * *Açıklama:* Kullanıcının stoğa girmesini beklemekten vazgeçtiği ürünü stok bildirim listesinden çıkarmasını sağlar.

4. Fiyat Alarmı Ekleme
    * *API Metodu:* POST /price-alerts
    * *Açıklama:* Kullanıcının bir ürünün fiyatı kendi belirlediği bütçenin altına düştüğünde sistemden uyarı mesajı almak için alarm kurmasını sağlar.

5. Fiyat Alarmı Görüntüleme
    * *API Metodu:* GET /price-alerts
    * *Açıklama:* Kullanıcının kurmuş olduğu tüm fiyat düşüş alarmlarını ve belirlediği hedef fiyatları listeleyip inceleyebilmesini sağlar.

6. Fiyat Alarmı Güncelleme
    * *API Metodu:* PUT /price-alerts/{alertId}
    * *Açıklama:* Kullanıcının mevcut bir alarmdaki hedef fiyat beklentisini veya bildirim alma tercihlerini sonradan değiştirmesine olanak tanır.

7. Fiyat Alarmı Silme
    * *API Metodu:* DELETE /price-alerts/{alertId}
    * *Açıklama:* Kullanıcının artık ucuzlamasını beklemediği bir ürünün fiyat alarmını iptal edip sistemden kaldırmasını sağlar.