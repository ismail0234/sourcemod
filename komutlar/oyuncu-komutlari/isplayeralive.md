---
description: Oyuncunun yaşayıp/yaşamadığını kontrol etmenizi sağlar.
---

# IsPlayerAlive

{% tabs %}
{% tab title="Kullanım" %}
```cpp
if(IsPlayerAlive(client)) {
    // Oyuncu Yaşıyor
} else {
    // Oyuncu Yaşamıyor
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool IsPlayerAlive(int client);
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

