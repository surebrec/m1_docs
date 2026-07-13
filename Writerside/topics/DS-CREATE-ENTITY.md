# DS_CREATE_ENTITY

Start typing here...

<chapter id="variable" title="variable">

<tabs group="call">
<tab id="request" title="Request">

{ type="wide" }
`ENTITY`
: variable

`NAME`
: name

`DESC`
: description

`VALIDATOR_ID`
: validator Id for variable value

`IS_CUSTOMIZABLE`
: `TRUE` | `FALSE`

`IS_CRITICAL`
: `TRUE` | `FALSE`

`MIN`
: min value

`MAX`
: max value

`STEP`
: step

`UNIT`
: dimension

`ICON`
: icon name

</tab>
<tab id="response" title="Response">

{ type="wide" }
`VALID`
: `TRUE` | `FALSE`

</tab>
</tabs>

</chapter>

<chapter id="validator" title="validator">

<tabs group="call">
<tab id="request2" title="Request">

{ type="wide" }
`ENTITY`
: validator

`NAME`
: validator name

`VALUE`
: validator expression

</tab>
<tab id="response2" title="Response">

{ type="wide" }
`VALID`
: `TRUE` | `FALSE`

</tab>
</tabs>

</chapter>

<chapter id="provider" title="provider">

<tabs group="call">
<tab id="request3" title="Request">

{ type="wide" }
`ENTITY`
: provider

`NAME`
: provider name

`TYPE`
: `OPC_UA` | `CSV` | `SQL`

`ENABLED`
: `TRUE` | `FALSE`

</tab>
<tab id="response3" title="Response">

{ type="wide" }
`VALID`
: `TRUE` | `FALSE`

</tab>
</tabs>

</chapter>