---
description: Oyuncunun bulunduğu konumun merkez vektörlerini almanızı sağlar.
---

# GetClientAbsOrigin

{% tabs %}
{% tab title="Kullanım" %}
```cpp
float vectors[3];
GetClientAbsOrigin(client, vectors);
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
void GetClientAbsOrigin(int client, float vectors[3]);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | Oyuncu numarası |
| vectors | float\[\] | Vektörlerin depolanacağı değişken |

#### Geri Dönüş Değeri

{% hint style="warning" %}
Bu fonksiyon geriye veri döndürmez.
{% endhint %}

