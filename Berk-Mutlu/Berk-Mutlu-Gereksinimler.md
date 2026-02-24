
1. Üye Olma
   * **API Metodu:** `POST /auth/register`
   * **Açıklama:** Kullanıcıların yeni hesaplar oluşturarak sisteme kayıt olmasını sağlar. Kişisel bilgilerin toplanmasını ve hesap oluşturma işlemlerini içerir. Kullanıcılar email adresi ve şifre belirleyerek hesap oluşturur.

2. Profil Görüntüleme
   * **API Metodu:** `GET /users/{userId}`
   * **Açıklama:** Kullanıcının profil bilgilerini görüntülemesini sağlar. Kullanıcı adı, email, telefon gibi kişisel bilgiler ve hesap durumu gösterilir. Güvenlik için giriş yapmış olmak gerekir.

3. Profil Güncelleme
    * **API Metodu:** `PUT /users/{userId}`
    * **Açıklama:** Kullanıcının profil bilgilerini güncellemesini sağlar. Kullanıcılar ad, soyad, email, telefon gibi kişisel bilgilerini değiştirebilir. Güvenlik için giriş yapmış olmak gerekir ve kullanıcılar yalnızca kendi bilgilerini güncelleyebilir.

4. Hesap Silme
    * **API Metodu:** `DELETE /users/{userId}`
    * **Açıklama:** Kullanıcının hesabını sistemden kalıcı olarak silmesini sağlar. Kullanıcı hesabını kapatmak istediğinde kullanılır. Bu işlem geri alınamaz ve kullanıcının tüm verileri silinir. Güvenlik için giriş yapmış olmak gerekir.

5. Karşılaştırma Listesine Ürün Ekleme
    * **API Metodu:** `POST /comparisons/items`
    * **Açıklama:** Kullanıcının özelliklerini veya fiyatını kıyaslamak istediği bir ürünü genel karşılaştırma panosuna eklemesini sağlar.

6. Karşılaştırma Listesinden Ürün Kaldırma
    * **API Metodu:** `DELETE /comparisons/items/{itemId}`
    * **Açıklama:** Kullanıcının kıyaslamaktan vazgeçtiği bir ürünü karşılaştırma panosundan çıkarmasını sağlar.

7. Ürün Detayı Görüntüleme
    * **API Metodu:** `GET /products/{productId}`
    * **Açıklama:** Kullanıcının sistemdeki herhangi bir ürünün üzerine tıkladığında o ürüne ait resim, güncel fiyat ve marka özelliklerini detaylıca incelemesini sağlar.

