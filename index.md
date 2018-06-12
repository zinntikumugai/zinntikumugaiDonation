# Donation

何でもしませんけど寄付はほしいﾃﾞｽ  
以下のアドレスでどうぞどうぞ

[Sensuでやるならこちら](https://shinoharata.github.io/TipSensuWithTwitter/?name=uesitananame55)

{% for address in site.data.addresss.Mainnet %}
## {{ address.name }} - {{ address.code }}
`{{ address.address }}`
{% endfor %}