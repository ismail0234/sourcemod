---
description: Oyuncunun admin yetkisinin ne olduğunu öğrenmeniz için kullanılır.
---

# GetUserAdmin

{% tabs %}
{% tab title="Kullanım" %}
```cpp
AdminId adminId = GetUserAdmin(client);
if(adminId != INVALID_ADMIN_ID) {
    // Oyuncu Admindir.
} else {
    // Oyuncu Admin Değildir.
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
AdminId GetUserAdmin(int client);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| client | int | Oyuncunun numarası |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **AdminId** değerinde **adminId** döndürür.
{% endhint %}

