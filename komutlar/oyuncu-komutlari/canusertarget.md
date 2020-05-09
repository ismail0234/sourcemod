---
description: Oyuncunun başka bir oyuncuya yetkisinin yetip/yetmediğini öğrenmenizi sağlar.
---

# CanUserTarget

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

