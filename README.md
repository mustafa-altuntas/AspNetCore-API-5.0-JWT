# Asp.Net Core Api 5.0 JWT (Json Web Token)


- Kimlik doğrulama : Sisteme giriş yapmak isteyen kullanıcı sisteme kayıtlımı koıntrol edilir.
- Kimlik yetkilendirme :sisteme kayıtlı kullanıcı sistem üzerindeki yetkileri.

- Token : String ve anlammlı bir ifade. İçinde data taşınabiliyor. Hangi api ye istek yapabileceğine ait datayı barındırır.
* Json Web Token : IETF tarafından sulunan standart bir token biçimidir.


## Access Token : 
JWT 'un ta kendisidir. Api lere istek yapmak için kullanırız.


## Refresh Token :
Access Token 'ın ömrü dolduğunda yeni bir token almak için kullanacağım token dır. Biçimi herhan gi bir string ifade oalabilir. Data barındırmaz. Refresh token sadece token dağıtan api 'ye gönderilir.

Access Token 'ın Ömrünü mümkün olduğunca kısa tutun örneğin 1 gün.

Refresh Token 'ın da ömrünü mümkül oldukça uzun tutyabiliriz örneğin 60 gün.
</br>
</br>
</br>


# NOT :
Token 'ın ömrü dolmuşsa veya geçersizse 401 durum kodu döner.

