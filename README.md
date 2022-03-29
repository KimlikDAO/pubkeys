# Açık anahtarlar

KimlikAŞ'ye ait 1024 adet Ed25519 açık anahtarı. Repo şu an `testing.pubkeys` dosyasında test anahtarlarını içeriyor; asıl anahtarlar ileriki bir tarihte
yayımlanacak.

Toplamda yaklaşık 200M tane imza atılacağı için her gizli anahtar 
`200.000 ± 500` kere kullanılacak. Bu rakam Ed25519 için tamamen güvenli 
sınırlar içinde.

```shell
$ shasum -a 256 testing.pubkeys
68d3c25a87f34ce02012d57bd85eb9f1e0911ffe74143c2eebf5efd7f75ef2ed  testing.pubkeys
```
