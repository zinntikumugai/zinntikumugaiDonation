# Donation

何でもしませんけど寄付はほしいﾃﾞｽ  
以下のアドレスでどうぞどうぞ

[Sensuでやるならこちら](https://shinoharata.github.io/TipSensuWithTwitter/?name=uesitananame55)

## Mainnet

{% for address in site.data.addresss.Mainnet %}
### {{ address.name }} - {{ address.code }}
{% capture img %}https://img.shields.io/badge/dynamic/json.svg?url={{ address.insight }}{{ address.addresss }}&label=tip&query=%24.balance&suffix=%20{{ address.code }}{% endcapture %}
`{{ address.address }}` {% if address.insight != null %}![img]({{ img }}){% else %}BudgeNotSupport{% endif %}
{% endfor %}