1. Liste Oluşturma
   * *API Metodu:* POST /lists
   * *Açıklama:* Kullanıcıların favori veya takip etmek istedikleri ürünleri kendi içlerinde gruplayabilmesi için sisteme yeni bir liste eklemesini sağlar.

2. Listeleri Görüntüleme
   * *API Metodu:* GET /lists
   * *Açıklama:* Kullanıcının daha önceden oluşturduğu tüm listelerini tek bir ekranda kolayca görmesini sağlar.

3. Liste Silme
   * *API Metodu:* DELETE /lists/{listId}
   * *Açıklama:* Kullanıcının artık ihtiyaç duymadığı veya kullanmak istemediği bir listeyi sistemden tamamen kaldırmasını sağlar.

4. Liste İsmi Güncelleme
   * *API Metodu:* PUT /lists/{listId}
   * *Açıklama:* Kullanıcının mevcut bir listenin adını veya detaylarını kendi isteğine göre değiştirmesine olanak tanır.

5. Liste İçeriği Görüntüleme
   * *API Metodu:* GET /lists/{listId}/items
   * *Açıklama:* Kullanıcının seçtiği belirli bir listenin içine girerek, o listeye eklenmiş olan tüm ürünleri detaylı bir şekilde görmesini sağlar.

6. Listeden Ürün Silme
   * *API Metodu:* DELETE /lists/{listId}/items/{itemId}
   * *Açıklama:* Kullanıcının bir liste içerisinden artık takip etmek istemediği belirli bir ürünü tek başına çıkarmasını sağlar.

7. Listeye Ürün Ekleme
   * *API Metodu:* POST /lists/{listId}/items
   * *Açıklama:* Kullanıcının incelerken beğendiği veya ilgilendiği bir ürünü, daha önceden oluşturduğu bir listeye sonradan dahil etmesini sağlar.