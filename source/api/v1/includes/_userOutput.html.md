|Field|Description|Required| Type |
|-------|-------|-----| ------ |
|firstName| User's First Name| `Yes` | `String` |
|lastName| User's Last Name| `Yes` | `String` |
|address| Object of User's Address| `Yes` | `String` |
|address.address1| Street Address| `Yes` | `String` |
|address.address2| Apartment Number| `Yes` | `String` |
|address.city| City| `Yes` | `String` |
|address.state| State| `Yes` | `String` |
|address.country | Country ***ISO 2 Format***| `Yes` | `String` |
|address.zip| Zipcode | `Yes` | `String` |
|email| User's Email Address| `Yes` | `String` |
|phone| Phone Number ***include Country Code***| `Yes` | `String` |
|dateOfBirth| Birthday | `Yes` | `String` |
|typeOfHome| Type of Home | `Yes` | `String` |
|isHomeOwner| Does user own a home | `Yes` | `Boolean` |
|proMonitoringEnabled| User has professional security monitoring system| `Yes` | `Boolean` |
|devices| List of security devices| `Optional` | `Object` |
|devices.moisture| # of Moisture Devices | `Optional` | `String` |
|devices.theft| # of Theft Devices | `Optional` | `String` |
|devices.smoke| # of Smoke Devices | `Optional` | `String` |
|devices.motion| # of Motion detection Devices | `Optional` | `String` |
|devices.waterShutoff| # of Water Shutoff Devices | `Optional` | `String` |
|devices.fire| # of Fire Detect Devices | `Optional` | `String` |
