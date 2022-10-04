|Field|Description|Required| Type |
|-------|-------|-----| ------ |
|firstName| User's First Name| `Yes` | `String` |
|lastName| User's Last Name| `Yes` | `String` |
|address| Object of User's Address| `No` | `String` |
|address.address1| Street Address| `No` | `String` |
|address.address2| Apartment Number| `No` | `String` |
|address.city| City| `No` | `String` |
|address.state| State| `No` | `String` |
|address.country | Country ***ISO 2 Format***| `No` | `String` |
|address.zip| Zipcode | `No` | `String` |
|email| User's Email Address| `Yes` | `String` |
|phone| Phone Number ***include Country Code***| `No` | `String` |
|dateOfBirth| Birthday | `No` | `String` |
|typeOfHome| Type of Home | `No` | `String` |
|isHomeOwner| Does user own a home | `No` | `Boolean` |
|proMonitoringEnabled| User has professional security monitoring system| `No` | `Boolean` |
|devices| List of security devices| `Optional` | `Object` |
|devices.moisture| # of Moisture Devices | `Optional` | `String` |
|devices.theft| # of Theft Devices | `Optional` | `String` |
|devices.smoke| # of Smoke Devices | `Optional` | `String` |
|devices.motion| # of Motion detection Devices | `Optional` | `String` |
|devices.waterShutoff| # of Water Shutoff Devices | `Optional` | `String` |
|devices.fire| # of Fire Detect Devices | `Optional` | `String` |
|policyNumber| Current insurance policy number | `No` | `String` |
|insuranceName| Name of current insurance | `No` | `String` |
|premiumPaid| --- | `No` | `String` |
|agentFirstName| Insurance agent first name | `No` | `String` |
|agentLastName| Insurance agent last name | `No` | `String` |
|agentEmail| Insurance agent email | `No` | `String` |
|agentPhone| Insurance agent phone # | `No` | `String` |
|carOwner| Are you a car owner | `No` | `String` |
|carVin| Car Vin Number | `No` | `String` |
|carCount| # of Cars | `No` | `integer` |
|homePurchaseDate| Date Purchased home | `No` | `String` |
|retired| Are you retired (yes/no) | `No` | `String` |
|specialOccupation| Current Occupation | `No` | `String` |
|loyalty| --- | `No` | `integer` |
|claimFree| --- | `No` | `integer` |
|mortgageFreeAndLienFree| --- | `No` | `String` |
|paidInFull| Current policy paid in full? | `No` | `String` |
|electronicFundTransfer| --- | `No` | `String` |
|paperless| Would you like paperless | `No` | `String` |
|maritalStatus| Martial Status | `No` | `String` |
|educationLevel| Level of Education | `No` | `String` |