---
description: Oyuncunun mevcut takımını değiştirmek için kullanılır.
---

# ChangeClientTeam

**Not:** CS\_TEAM\_T sabit değerlerini kullanabilmeniz için **cstrike** kütüphanesini kodunuza dahil etmeyi unutmayın.

{% tabs %}
{% tab title="Kullanım" %}
```cpp
#include <cstrike>

// Oyuncuyu Terörist Takımına Gönderir
ChangeClientTeam(client, CS_TEAM_T);

// Oyuncuyu Anti-Terörist Takımına Gönderir
ChangeClientTeam(client, CS_TEAM_CT);

// Oyuncuyu İzleyici Takımına Gönderir
ChangeClientTeam(client, CS_TEAM_SPECTATOR);
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
void ChangeClientTeam(int client, int team);
```
{% endtab %}
{% endtabs %}

#### Parametreler

| Değişken | Tür | Açıklama |
| :--- | :--- | :--- |
| name | char\[\] | BOT'un adı |

#### Geri Dönüş Değeri

{% hint style="info" %}
Bu fonksiyon geriye **int** değerinde **BOT clientId** numarasını döndürür.
{% endhint %}

