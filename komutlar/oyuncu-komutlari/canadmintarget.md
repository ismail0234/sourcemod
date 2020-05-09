---
description: >-
  Bir yöneticinin diğerini hedefleyip hedefleyemeyeceğini kontrol etmenizi
  sağlar.
---

# CanAdminTarget

#### Çalışma mantığı aşağıdaki gibidir;

1. Hedefleyen AdminId değeri INVALID\_ADMIN\_ID ise, hedefleme başarısız olur.
2. Hedeflenen AdminId değeri INVALID\_ADMIN\_ID ise, hedefleme başarılı olur.
3. Hedeflenen AdminId, hedefleyen AdminId ile aynıysa hedefleme başarılı olur.
4. Hedefleyen root yetkisine sahip ise, hedefleme başarılı olur.
5. Hedeflenen kişi, hedefleyen kişiden daha yüksek erişime sahipse, hedefleme başarısız olur
6. Hedeflenen kişi, grup bağışıklıkları aracılığıyla hedefleyen kişiden belirli bir bağışıklığı varsa, hedefleme başarısız olur.

{% tabs %}
{% tab title="Kullanım" %}
```cpp
if(CanUserTarget(clientId, targetId)) {
    // Oyuncunun yetkisi hedef oyuncuya yetiyor
} else {
    // Oyuncunun yetkisi hedef oyuncuya yetmiyor
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool CanUserTarget(int clientId, int targetId);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| clientId | int | Kaynak oyuncunun numarası |
| targetId | int | Hedef oyuncunun numarası |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **bool** değerinde **başarılı/başarısız** döndürür.
{% endhint %}

