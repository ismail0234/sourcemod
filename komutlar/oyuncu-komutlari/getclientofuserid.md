---
description: Oyuncunun userId numarasını clientId numarasına dönüştürür.
---

# GetClientOfUserId

{% tabs %}
{% tab title="Kullanım" %}
```cpp
int clientId = GetClientOfUserId(userId);
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
int GetClientOfUserId(int userId);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| userId | int | Oyuncunun UserId numarası |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **int** değerinde **clientId** döndürür.
{% endhint %}

