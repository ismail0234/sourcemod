---
description: Oyuncunun steam id doğrulamasının başarılı olup/olmadığını almanızı sağlar.
---

# IsClientAuthorized

{% tabs %}
{% tab title="Kullanım" %}
```cpp
if(IsClientAuthorized(client)) {
    // Doğrulama Başarılı
} else {
    // Doğrulama Başarısız
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool IsClientAuthorized(int client);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | İstemci numarası |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **bool** değerinde **başarılı/başarısız** döndürmez.
{% endhint %}

