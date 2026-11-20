# My Coffee Spot Privacy Policy — Draft

This is a working draft for review before publication. Confirm the operator's identity, applicable retention periods, deletion procedure, and production CloudKit configuration before removing this notice.

**Contact:** appsitetown@gmail.com

## About this policy

My Coffee Spot is a game in which you can create a virtual café, explore other players’ cafés, and exchange preset stickers. This policy describes the data used by the current app and how to contact us about it.

## Information used by the app

- **Café and profile information:** The display name and café name you choose; the city and country selected for your café; its design, menu, level, story and other game details. Your café information is stored in a public CloudKit database and can be viewed by other users of the service.
- **Visits and interactions:** Orders made with game coins, including the displayed buyer name, country, item, price and time; guestbook stickers, visitor names, countries and times; likes; and reports, including the reported café, reason and time. These records are stored in the public CloudKit database. Information stored there may be accessible to users of the service even when it is not displayed on every screen.
- **Game progress and preferences:** Your game state, including coins, passport, collected stickers and notification preferences, is saved on your device and may also be stored in your private iCloud database. The app also keeps a local cache of café data.
- **iCloud identifier:** CloudKit provides an app-specific user record identifier that the app uses to associate a café and other game activity with an iCloud account. Café and like record identifiers are derived from it. An iCloud account is used for the app’s online features.
- **Location and city search:** If you choose to find your city using location and grant permission, the app obtains a device location and uses Apple’s geocoding service to identify a city. The app saves and shares the selected city, country, time zone and coordinates for the city area rather than saving the original location fix. If a city-centre lookup is unavailable, it uses device coordinates rounded to one decimal place; these approximate coordinates may reflect your general area. You can choose a city manually instead.
- **Notifications:** With your permission, the app can send local notifications and use CloudKit subscriptions for events such as a new café or visitors. Notification preferences are saved with your game state and on the device.
- **Messages to us:** If you contact us by email, we receive the information and contact details you choose to include and use them to respond and handle your request.

## Why information is used and shared

We use this information to operate and display cafés, save progress, facilitate visits and stickers, provide weather for cities, send notifications you choose to receive, respond to support requests and address reports. Apple services including iCloud/CloudKit, Maps and geocoding, WeatherKit and Apple Push Notification service support these features. Apple processes information under its own terms and privacy documentation: https://www.apple.com/legal/privacy/.

The current app does not include advertising or advertising-tracking features. The app’s game coins are virtual; they are not payments.

## Your choices

You can choose a city without granting location permission. You can change location permission and notification permission in iOS Settings, and adjust the app’s notification preferences in the app. You can change your displayed names in the app and block or report cafés. Information already shared in interactions may remain in CloudKit after a name change.

## Retention and deletion

The app retains saved game information on the device until it is reset or removed, subject to device backups. The intended policy is to keep visits and guestbook stickers until a player requests deletion, rather than delete them automatically after 90 days. The deletion process is not yet implemented or verified. The intended retention period for safety reports remains 90 days, but automatic deletion is not yet implemented or verified. Public and private CloudKit records and records of interactions may remain in iCloud after a local reset. The app’s reset function removes the local saved game and resets notification settings; it does not currently delete CloudKit records. Some versions may retain a local café cache after reset. Uninstalling the app does not by itself guarantee deletion of cloud records.

To ask about your data or request deletion, contact appsitetown@gmail.com. We may need information to identify the relevant records and verify the request without asking for your Apple Account password. Some data may need to be retained where required by law or to handle safety and disputes. The actual retention periods and procedure for locating and deleting every type of CloudKit record must be confirmed before this policy is published.

## Children

The app is not intended to collect personal information from children knowingly. The applicable age rating and any child-specific safeguards must be verified before release.

## Changes and contact

We may update this policy as the app changes. Contact us at appsitetown@gmail.com with privacy questions or requests.
