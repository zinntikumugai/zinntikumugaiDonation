# Donation

何でもしませんけど寄付はほしいﾃﾞｽ  
以下のアドレスでどうぞどうぞ

[Sensuでやるならこちら](https://shinoharata.github.io/TipSensuWithTwitter/?name=uesitananame55)

## Mainnet

{% for address in site.data.addresss.Mainnet %}
### {{ address.name }} - {{ address.code }}
`{{ address.address }}` ![img](https://img.shields.io/badge/dynamic/json.svg?url={{ address.insght || "https://insight.bitpay.com/"}}{{ address.addresss }}&label=tip&query=%24.balance&suffix=%20{{ address.code }})
{% endfor %}