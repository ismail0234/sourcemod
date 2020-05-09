---
description: Bir sahte istemci yani bot oluşturmak için kullanılabilir.
---

# CreateFakeClient

{% tabs %}
{% tab title="Kullanım" %}
```cpp
int clientId = CreateFakeClient("BOT Benson");
if(clientId > 0) {
    // BOT oluşturma başarılı
} else {
    // BOT oluşturma başarısız
}
```
{% endtab %}

{% tab title="Orijinal Kod" %}
```cpp
int CreateFakeClient(const char[] name);
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

