---
description: Oyuncunun bulunduğu konumun açılarını almanızı sağlar.
---

# GetClientAbsAngles

{% tabs %}
{% tab title="Kullanım" %}
```cpp
float angles[3];
GetClientAbsAngles(client, angles);
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
void GetClientAbsAngles(int client, float angles[3]);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | İstemci numarası |
| angles | float\[\] | Açıların depolanacağı değişken |

#### Geri Dönüş Değeri

{% hint style="warning" %}
Bu fonksiyon geriye veri döndürmez.
{% endhint %}



