---
description: Oyuncunun bulunduğu takımı almanızı sağlar.
---

# GetClientTeam

{% tabs %}
{% tab title="Kullanım" %}
```cpp
int clientTeam = GetClientTeam(client);
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
int GetClientTeam(int client);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | Oyuncu numarası |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **int** değerinde **oyuncunun takımını** döndürür.

* **İzleyici**  Takımı için **1** değeri
* **Terörist** Takımı için **2** değeri
* **Counter** Takımı için **3** değeri
{% endhint %}

