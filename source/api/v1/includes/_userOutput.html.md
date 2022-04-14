|Field|Description|Required| Type |
|-------|-------|-----| ------ |
|firstName| User's First Name| `Yes` | `String` |
|lastName| User's Last Name| `Yes` | `String` |
|address| Object of User's Address| `Yes` | `String` |
|address.address1| Street Address| `Yes` | `String` |
|address.address2| Apartment Number| `Yes` | `String` |
|address.city| City| `Yes` | `String` |
|address.state| State| `Yes` | `String` |
|address.country| Country| `Yes` | `String` |
|address.zip| Zipcode | `Yes` | `String` |
|email| User's Email Address| `Yes` | `String` |
|phone| User's Phone Number| `Yes` | `String` |
|dateOfBirth| Birthday | `Yes` | `String` |
|typeOfHome| Type of Home "`Rent/Home`"| `Yes` | `String` |
|isHomeOwner| Check if a Homeowner | `Yes` | `Boolean` |
|proMonitoringEnabled| Does User have Subscription| `Yes` | `Boolean` |
|devices| List of Devices| `Yes` | `Object` |
|devices.moisture| # of Moisture Devices | `Yes` | `String` |
|devices.theft| # of Theft Devices | `Yes` | `String` |
|devices.smoke| # of Smoke Devices | `Yes` | `String` |
|devices.motion| # of Motion Devices | `Yes` | `String` |
|devices.waterShutoff| # of Water Shutoff Devices | `Yes` | `String` |
|devices.fire| # of Fire Detect Devices | `Yes` | `String` |
