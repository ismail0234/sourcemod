---
description: Oyuncunun SourceTV Botu olup/olmadığını kontrol etmenizi sağlar.
---

# IsClientSourceTV

{% tabs %}
{% tab title="Kullanım" %}
```cpp
if(IsClientSourceTV(client)) {
    // Oyuncu SourceTV Botu
} else {
    // Oyuncu SourceTV Botu Değil
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool IsClientSourceTV(int client);
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

