---
description: Oyuncunun Maximum boyut vektörlerini almanızı sağlar.
---

# GetClientMaxs

{% tabs %}
{% tab title="Kullanım" %}
```cpp
float vectors[3];
GetClientMaxs(client, vectors);
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
void GetClientMaxs(int client, float vectors[3]);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | Oyuncunun numarası |
| vectors | float\[3\] | Oyuncunun vektörlerinin saklanacağı değişken |

#### Geri Dönüş Değeri

{% hint style="warning" %}
Bu fonksiyon geriye değer döndürmez.
{% endhint %}

