# XeroRuby::CISOrgSetting

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**cis_contractor_enabled** | **Boolean** | true or false - Boolean that describes if the organisation is a CIS Contractor | [optional] 
**cis_sub_contractor_enabled** | **Boolean** | true or false - Boolean that describes if the organisation is a CIS SubContractor | [optional] 
**rate** | **Integer** | CIS Deduction rate for the organisation | [optional] 

## Code Sample

```ruby
require 'XeroRuby'

instance = XeroRuby::CISOrgSetting.new(cis_contractor_enabled: null,
                                 cis_sub_contractor_enabled: null,
                                 rate: null)
```


