## This is the SOAP service to access for calculating the distance between 2 locations by using GPS coordinates

## Link to access to te cloud website : https://soap-felastronaut-trouvetontra.herokuapp.com/services/CalculDistance
## Link to access the WDSL file : http://soap-felastronaut-trouvetontra.herokuapp.com/services/CalculDistance?wsdl
## Link for the Args to use for the SOAP request : http://soap-felastronaut-trouvetontra.herokuapp.com/services/CalculDistance?xsd=1

```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:exam="http://example/">
   <soapenv:Header/>
   <soapenv:Body>
      <exam:distance>
         <arg0>53</arg0>
         <arg1>32</arg1>
         <arg2>12</arg2>
         <arg3>12</arg3>
         <!--Optional:-->
         <arg4>?</arg4>
      </exam:distance>
   </soapenv:Body>
</soapenv:Envelope>
```
