---
description: Oyuncunun oyuna bağlı olup/olmadığını kontrol etmenizi sağlar.
---

# IsClientConnected

{% tabs %}
{% tab title="Kullanım" %}
```cpp
if(IsClientConnected(client)) {
    // Oyuncu Oyuna Bağlı
} else {
    // Oyuncu Oyuna Bağlı Değil
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool IsClientConnected(int client);
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

