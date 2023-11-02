# Currency Authority Table
The Currency authority table is a controlled vocabulary that lists concepts associated with currencies and currency subunits. The concepts included are correlated with the ISO 4217 international standard.
The Currency authority table is updated based on the stakeholders’ needs. The Currency authority table is maintained by the Finamatix data team.

**Domain:** Finance  
**Subdomain:** Assets  
**Subject:** Money  
**Version:** 20231102
**Status:** Draft

[Currency/finxio_currencies.yaml ](https://github.com/finamatix/fnxio-vocabularies/blob/main/Currency/finxio_currencies.yaml)

**attributes:**:ENTITY:: priority:iso_code:name:full_name:symbol:unicode:hex:html:CSS:subunit:subunit_to_unit:symbol_first:decimal_mark:thousands_separator

**example:**
:JPY: 
  :priority: 6
  :iso_code: JPY
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

**Currrency Incorporation**

|Currency|Status|Priority| Updated|
|:----|:----:| :----: | :----: |
|US dollar|Active|5| 2023-11-02 |
|Japanese Yen|Active| 6 | 2023-11-02|
