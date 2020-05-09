---
description: Oyuncunun bir bot olup/olmadığını kontrol etmenizi sağlar.
---

# IsFakeClient

{% tabs %}
{% tab title="Kullanım" %}
```cpp
if(IsFakeClient(client)) {
    // Oyuncu Bir Bot
} else {
    // Oyuncu Bir Bot Değil
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool IsFakeClient(int client);
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

