# Authority Table: Currency

**Domain:** Finance  
**Subdomain:** Assets  
**Subject:** Money  
**Version:** 20231102
**Status:** Draft

The Currency NAL is a controlled vocabulary that lists entities and properties associated with currencies and currency subunits. 
[Currency/finxio_currencies.yaml ](https://github.com/finamatix/fnxio-vocabularies/blob/main/Currency/finxio_currencies.yaml)

The list and properties included are correlated with the ISO 4217 international standard: 

**attributes:**:ENTITY:: priority: 4217code: num4217:name: full_name: symbol: unicode: hex: html: CSS: subunit: subunit_to_unit: symbol_first: decimal_mark: thousands_separator

**example:**
:JPY: 
  :priority: 6
  :code4217: JPY
  :num4217: 392
  :name: Yen
  :full_name: "Japanese Yen"
  :symbol: ¥
  :unicode: U+000A5
  :hex: &#xa5
  :html: &#165
  :CSS: \00A5
  :subunit: Sen
  :subunit_to_unit: 100
  :symbol_first: true
  :decimal_mark: "."
  :thousands_separator: ","

The Currency authority table is maintained by the Finamatix data team but may be updated based on the stakeholders’ needs. 

**Currrency Incorporation**

|Currency|Status|Priority| Updated|
|:----|:----:| :----: | :----: |
|US dollar|Active|5| 2023-11-02 |
|Japanese Yen|Active| 6 | 2023-11-02|
