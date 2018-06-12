# Donation

何でもしませんけど寄付はほしいﾃﾞｽ  
以下のアドレスでどうぞどうぞ

[Sensuでやるならこちら](https://shinoharata.github.io/TipSensuWithTwitter/?name=uesitananame55)

{% for adress in site.data.addresss.list %}
## {{ address.name }} - {{ address.code }}
`{{ address.address }}`
{% endfor %}