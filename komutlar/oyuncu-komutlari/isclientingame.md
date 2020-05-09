---
description: Oyuncunun oyuna giriş yapıp/yapmadığını kontrol etmenizi sağlar.
---

# IsClientInGame

{% tabs %}
{% tab title="Kullanım" %}
```cpp
if(IsClientInGame(client)) {
    // Oyuncu Oyuna Giriş Yapmış
} else {
    // Oyuncu Oyuna Giriş Yapmamış
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool IsClientInGame(int client);
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

