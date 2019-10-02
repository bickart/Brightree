## Available Method Definitions

### InsuranceSearch
``` html
        <ins:InsuranceSearch>
         <!--Optional:-->
         <ins:searchRequest>
            <!--Optional:-->
            <brig:Address>?</brig:Address>
            <!--Optional:-->
            <brig:BrightreeID>?</brig:BrightreeID>
            <!--Optional:-->
            <brig:City>?</brig:City>
            <!--Optional:-->
            <brig:Company>
               <!--Optional:-->
               <brig1:ID>?</brig1:ID>
               <!--Optional:-->
               <brig1:Value>?</brig1:Value>
            </brig:Company>
            <!--Optional:-->
            <brig:CoverageType>?</brig:CoverageType>
            <!--Optional:-->
            <brig:ExternalID>?</brig:ExternalID>
            <!--Optional:-->
            <brig:Group>
               <!--Optional:-->
               <brig1:ID>?</brig1:ID>
               <!--Optional:-->
               <brig1:Value>?</brig1:Value>
            </brig:Group>
            <!--Optional:-->
            <brig:InsuranceID>?</brig:InsuranceID>
            <!--Optional:-->
            <brig:InsuranceName>?</brig:InsuranceName>
            <!--Optional:-->
            <brig:PlanType>
               <!--Optional:-->
               <brig1:ID>?</brig1:ID>
               <!--Optional:-->
               <brig1:Value>?</brig1:Value>
            </brig:PlanType>
            <!--Optional:-->
            <brig:PriceTable>
               <!--Optional:-->
               <brig1:ID>?</brig1:ID>
               <!--Optional:-->
               <brig1:Value>?</brig1:Value>
            </brig:PriceTable>
            <!--Optional:-->
            <brig:State>
               <!--Optional:-->
               <brig1:ID>?</brig1:ID>
               <!--Optional:-->
               <brig1:Value>?</brig1:Value>
            </brig:State>
         </ins:searchRequest>
         <!--Optional:-->
         <ins:sortRequest>
            <!--Zero or more repetitions:-->
            <brig:InsuranceSortParameter>
               <!--Optional:-->
               <brig:SortField>?</brig:SortField>
               <!--Optional:-->
               <brig:SortOrder>?</brig:SortOrder>
            </brig:InsuranceSortParameter>
         </ins:sortRequest>
         <!--Optional:-->
         <ins:pageSize>?</ins:pageSize>
         <!--Optional:-->
         <ins:page>?</ins:page>
      </ins:InsuranceSearch>
```

### InsuranceUpdate
``` html
        <ins:InsuranceUpdate>
         <!--Optional:-->
         <ins:BrightreeID>?</ins:BrightreeID>
         <!--Optional:-->
         <ins:Insurance>
            <!--Optional:-->
            <brig:BrightreeID>?</brig:BrightreeID>
            <!--Optional:-->
            <brig:ExternalID>?</brig:ExternalID>
            <!--Optional:-->
            <brig:InsuranceGeneralInfo>
               <!--Optional:-->
               <brig:Address>
                  <!--Optional:-->
                  <brig1:AddressLine1>?</brig1:AddressLine1>
                  <!--Optional:-->
                  <brig1:AddressLine2>?</brig1:AddressLine2>
                  <!--Optional:-->
                  <brig1:AddressLine3>?</brig1:AddressLine3>
                  <!--Optional:-->
                  <brig1:City>?</brig1:City>
                  <!--Optional:-->
                  <brig1:Country>?</brig1:Country>
                  <!--Optional:-->
                  <brig1:County>?</brig1:County>
                  <!--Optional:-->
                  <brig1:PostalCode>?</brig1:PostalCode>
                  <!--Optional:-->
                  <brig1:State>?</brig1:State>
               </brig:Address>
               <!--Optional:-->
               <brig:Name>?</brig:Name>
               <!--Optional:-->
               <brig:Note>?</brig:Note>
            </brig:InsuranceGeneralInfo>
         </ins:Insurance>
      </ins:InsuranceUpdate>
```