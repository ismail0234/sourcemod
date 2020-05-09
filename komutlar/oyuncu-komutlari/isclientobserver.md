---
description: Oyuncunun Observer(Gözlemci) modunda olup/olmadığını kontrol etmenizi sağlar.
---

# IsClientObserver

{% tabs %}
{% tab title="Kullanım" %}
```cpp
if(IsClientObserver(client)) {
    // Oyuncu Observer Modunda
} else {
    // Oyuncu Observer Modunda Değil
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
bool IsClientObserver(int client);
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

