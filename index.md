# Donation

何でもしませんけど寄付はほしいﾃﾞｽ  
以下のアドレスでどうぞどうぞ

[Sensuでやるならこちら](https://shinoharata.github.io/TipSensuWithTwitter/?name=uesitananame55)

## Mainnet

{% for address in site.data.addresss.Mainnet %}
### {{ address.name }} - {{ address.code }}
`{{ address.address }}` ![img](https://img.shields.io/badge/dynamic/json.svg?url={{ address.insght || "https://insight.bitpay.com/"}}{{ address.addresss }}&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIzMDAwcHgiIGhlaWdodD0iMzAwMHB4Ij4NCjxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik0xNTAxIDUxMmE5OTAgOTkwIDAgMCAxIDY0MCAxNzQ1aDM4NEExMjc2IDEyNzYgMCAwIDAgNjg3IDUxMmg4MTR6TTE1MDEgMjQ5M0E5OTAgOTkwIDAgMCAxIDg2NyA3NDJINDcxYTEyNzYgMTI3NiAwIDAgMCAxODI5IDE3NDhsLTc5OSAzeiIvPg0KPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIwMjcgMTgwMHYtNjAxYzAtMTI2LTEwMS0yMjctMjI3LTIyN2gtNjAxYTIyNyAyMjcgMCAwIDAtMjI3IDIyN3Y2MDFjMCAxMjYgMTAxIDIyNyAyMjcgMjI3aDYwMWMxMjYgMCAyMjctMTAxIDIyNy0yMjd6bS03NjItNjZ2LTQ2OWg0Njl2NDY5aC00Njl6Ii8%2BDQo8L3N2Zz4NCg%3D%3D&label=tip&query=%24.balance&suffix=%20{{ address.code }})
{% endfor %}