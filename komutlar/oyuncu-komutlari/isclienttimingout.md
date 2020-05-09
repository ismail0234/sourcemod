---
description: Oyuncunun zaman aşımına uğrayıp/uğramadığını anlamak için kullanılır.
---

# IsClientTimingOut

{% tabs %}
{% tab title="Kullanım" %}
```cpp
if(IsClientTimingOut(client)) {
    // Oyuncu Zaman Aşımına Uğradı
} else {
    // Oyuncu Zaman Aşımına Uğramadı
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool IsClientTimingOut(int client);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | İstemci numarası |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **bool** değerinde **başarılı/başarısız** döndürmez
{% endhint %}

