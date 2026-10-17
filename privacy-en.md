# Grams privacy policy

Revision dated October 17, 2026.

The controller of support correspondence is the Grams developer, Andrei Gavrilenko. Privacy contact: **gaavr.apps@yandex.ru**.

Grams is a food diary with calculations and statistics. This policy describes information used on your device, shared with external services, and information you may choose to send to the developer.

## Information and purposes

Grams stores foods, recipes, their photos, food entries with amounts, nutrients and dates, settings, and profile details you enter. Your profile includes sex, date of birth, height, activity level, and weight or body fat goals. Locally stored information also includes your latest weight, manual targets, daily target history, streak freezes, and body composition measurements with their date, method, and source. These support your diary, food search, calculations, and statistics. Calculations run on your device. No separate Grams account is required.

The developer operates no servers for collecting Grams data. The app does not send your diary, profile, or Health measurements to the developer. The primary database is on your device; when you enable the relevant features, the information described below goes to your Health store and private iCloud database. The developer is not given remote access to your app database or Apple Account data. It does not include advertising networks or third-party behavioral analytics. Grams does not share your diary or Health data for advertising or use them to train cloud models. This does not mean all information stays on your phone: network features are described below.

## Food sync through iCloud

Sync is off by default. If you turn it on and restart Grams, the app transfers the following to your private iCloud database:

- foods and recipes: names, ingredients, nutrients, portions, barcodes, instructions, and saved photos;
- food entries: name, amount, nutrients, date and time, time zone, and meal, as well as saved entry components, if present;
- favorites, food usage information, and supporting data for linking and syncing entries. These include the originating device identifier and identifiers of food samples the app wrote to Health.

Your profile, manual targets, streak freezes, weight and body composition measurements read from Health, and the local Health delivery queue are not included in this sync. Manual body composition measurements, daily target history, and other readings from Health are not included in this database either. The built-in food catalog ships with the app.

Sync makes your food data available on devices using the same Apple Account. Apple services handle this exchange; your diary does not pass through a developer-operated server. Sync depends on your account, network, and available storage. Apple's processing is described in [Apple's privacy policy](https://www.apple.com/legal/privacy/en-ww/).

Turning sync off takes effect after restarting the app, keeps the local copy, and does not delete existing iCloud data. This switch does not control device backups or the Health app's own sync, which depend on your Apple settings.

## Apple Health

Health integration is off by default. With your permission, Grams reads weight, height, sex, date of birth, body fat percentage, active energy, resting energy, and dietary calories for calculations and statistics. It writes calories, protein, fat, carbohydrates, and fiber from your food diary, the date and time, food name, meal, and entry and operation identifiers used to update and delete samples. Imported body fat measurements are stored locally with their date, sample identifier, and source app identifier.

Grams attempts to send edits and deletions to Health from the device that originally created the food entry. Completing an operation requires that device to retain its app data, have Health integration enabled, and have the necessary permissions. Changes made on another device must first reach the originating device through sync.

If the originating device is lost, the app and its local data are removed from it, or its operation queue is lost, automatic updates or deletion of Health samples may never complete. In that case, you need to remove the records yourself using the Health app. Grams does not guarantee that another device can complete the operation.

You can change read and write permissions using Apple's Health access settings. Turning off Health integration in Grams or revoking permission does not delete previously written data.

## Open Food Facts search

On the add-food screen, Grams automatically sends the current search text to Open Food Facts over HTTPS after a pause while you type when the query has at least three characters and there are no results in either the built-in catalog or your saved foods. If search fails, the Retry button repeats the search; Open Food Facts is contacted under the same conditions. The current version has no separate online-search button when local results exist. Automatic search does not ask for separate confirmation: an unfinished phrase may be sent. Names may be typed or obtained from voice input.

For a query containing Cyrillic letters, the app also sends a version with those letters replaced by Latin letters to find alternative spellings. This is an additional request to the same service, not a translation by another provider. If a barcode is absent from your foods and recipes and the built-in catalog, the app automatically sends it to Open Food Facts without separate confirmation.

Open Food Facts receives the query text or barcode, your IP address, and app information (a User-Agent identifying Grams, a version, and the platform). Your diary, profile, photos, audio recordings, and measurements from Health are not attached as separate data. However, personal or sensitive information you enter in the search field may be sent as part of its text.

The current version has no separate switch to disable online search. The iCloud and Health switches do not control it. Without a network connection, requests are not delivered and the built-in catalog remains available.

Open Food Facts processes requests under its [privacy policy](https://world.openfoodfacts.org/privacy). The Grams developer does not control that service's log retention. The built-in catalog is available offline.

## Camera, voice, and saved photos

The camera reads barcodes. Barcode reading and speech recognition run on your device; Grams does not send audio or camera images to recognition servers. Downloading Apple's system models may require a network connection.

Recognized names and barcodes may subsequently be used for online search. A photo saved with a food or recipe may be included in iCloud sync if you turn it on.

New recipe photos are saved as re-encoded images without the original metadata: location coordinates, capture date, camera information, and author details. Image orientation and transparency are preserved. Previously saved photos are not automatically cleaned: any metadata in those files may remain in local and cloud copies. Originals in your photo library are not changed. The app does not use photo coordinates for nutrition calculations.

You can revoke camera and microphone access in device settings. This does not delete previously saved photos or their copies.

## Sharing you initiate and support

If you send a daily report using the system share menu, the selected app or recipient receives its contents. External websites apply their own policies when you follow their links.

If you email **gaavr.apps@yandex.ru**, the developer receives your email address, sender name if supplied by your email app, subject, message, date and time, any attachments you send, and delivery headers. Header contents depend on the email service and may include delivery route information. These data concern people contacting support or making a request about their data. They are used to answer and resolve your request. You do not need to send an email to use Grams. Please do not send passwords, your entire diary database, or medical documents; a description and a screenshot without personal information are usually enough to report an issue. Addresses from support requests are not used for promotional mailings. Before sending a screenshot, hide names, addresses, and health information. You do not need to send your full diary to report an issue: where possible, describe it using fictional foods and values. Contacting support does not mean that you consent to advertising, publication of your message, or any further use of your information.

The support button pre-fills a subject containing the app version and a draft body containing the Grams version, device type (such as iPhone), and iOS version. The app does not automatically attach your diary, profile, Health measurements, photos, audio, or diagnostic logs. If you attach them yourself, they also become available to the recipient. You can edit or remove these details before sending. Opening the draft does not send the email to the developer; the selected email app and its service handle the draft.

To handle a request, the developer receives, reads, stores and, where needed, corrects the correspondence, uses it to reply, and then deletes it under the rules below. Processing uses an email service and email app.

Support email is hosted by Yandex Mail (Yandex LLC, Russia). Yandex processes the address, message content, attachments, and technical information to deliver and store email under its [privacy policy](https://yandex.com/legal/confidential/).

Ordinary support correspondence, including replies and attachments, is kept for no longer than **90 calendar days after the last message in the conversation**. Correspondence is deleted earlier once its purpose has been fulfilled and there is no remaining basis for retention, or where applicable law requires a shorter period. The 90 days are a maximum, not a minimum retention period. This period applies to the mailbox and other copies under the developer's control, including downloaded attachments. Messages are also removed from Trash.

You may request earlier deletion by writing to the same address. Personal data requests are handled without undue delay, no later than one month after receipt, or sooner if applicable law requires. Where the law permits an extension, you will be told the reasons and the new deadline before the initial applicable response period expires. This is the time frame for handling data requests, not a promise to fix every app issue within a month.

Specific information may be kept longer only where necessary to meet an applicable legal obligation or to establish, exercise, or defend legal claims. Only the necessary portion is retained, and only for a justified period. For example, where the law requires evidence of data destruction, the necessary records of completing the request are retained separately from ordinary correspondence for the legally required period; this does not justify keeping all messages and attachments. If deletion is refused in whole or in part, the developer will explain the reason and the applicable retention period or criterion, unless that notice is prohibited by law.

Deletion from the mailbox does not mean that all of Yandex's technical and backup copies are immediately erased: those are subject to the retention rules described in Yandex's [privacy policy](https://yandex.com/legal/confidential/). Copies in your own mailbox also remain under your control.

## Retention, deletion, and your choices

The working diary and saved information have no automatic expiry: they remain until removed using the available controls. Stopping use of the app does not itself erase them. The local Health delivery log holds the information needed to deliver and correct entries: names, dates, nutrients, and operation identifiers.

Deleting an entry, food, or recipe removes that object from the current working Grams database after a successful save. Unused saved items from the external catalog may be cleaned up automatically. With sync enabled, deletions from the working database reach iCloud after a successful exchange; immediate deletion on every device is not guaranteed. Deleting a food or recipe does not erase existing diary entries: they retain snapshots of the name and nutrients. Delete those entries separately.

“Delete Grams data” removes from the current database the diary, your own and saved foods, recipes, daily target history, streak freezes, the profile with goals and manual target, saved body composition measurements, the Health delivery queue, and app caches. The iCloud setting is retained. With sync on, the deletion goes to iCloud and reaches your other devices with the same Apple ID once they are online; the app does not promise it is instant. Devices with sync off do not receive it, and the profile and measurements on other devices are not in iCloud, so they are deleted on each device separately. With sync off, the copy in iCloud and the data on other devices stay. An entry made on another device while offline before it received the deletion will appear again once that device is online. The Health queue is cleared with the rest: samples already written to Health are not deleted by this button, and it leaves no pending deletions that would change Health later. Previous database files kept after migration from an older version are deleted too. Device technical settings unrelated to your information remain. “Reset settings” returns the profile, goals, appearance and Health sync to defaults and does not delete anything from the diary.

After upgrading from some earlier versions, Grams keeps previous database files on the device to support recovery if migration fails. These files may contain the previous diary, photos, profile, and other information stored by that version. Deleting or editing an item in the current working database does not change these old copies. They have no automatic cleanup deadline; “Delete Grams data” deletes them. These copies are kept by Grams itself, not just by Apple backups.

The data copy file you save with “Save a copy” is created and read only on your device: Grams does not send it anywhere or check it on a server. Where you put the file and whom you share it with is up to you; it contains the diary, your own foods and recipes, daily target history and streak freezes, without the profile, Health data or recipe photos.

Device backups are managed separately through Apple and may also contain earlier versions of your information. Deletion from the current database does not mean immediate deletion from those backups.

Removal of the corresponding Health samples is separate from diary deletion and is subject to the conditions in the Apple Health section above. Removing Grams and its local device data does not automatically delete Health data, existing iCloud copies, backups, or support correspondence. You can manage data held in Apple's services and backups using Apple's controls.

You can edit and delete entries in the app, turn sync off, and revoke permissions, subject to the limitations described above. These actions do not automatically disable online search. For questions about your information and requests to exercise your rights, contact **gaavr.apps@yandex.ru**. The developer cannot remotely open your local database or manage your Apple Account, but can explain the available controls and handle requests relating to information the developer holds, such as correspondence.

Where GDPR applies to the processing of your data, you may, in the circumstances it provides, request access and a copy, correction, erasure, restriction of processing, and portability, object to processing, and withdraw consent where processing is based on it. Withdrawal does not affect the lawfulness of processing before withdrawal. You may also lodge a complaint with a competent data protection authority. Requests are answered within one month; complexity or a large number of requests may justify up to two additional months, with an explanation within the first month. Requests are normally free of charge. Reasonable doubts about identity may require proportionate verification. A refusal will explain the reasons and the right to complain to a supervisory authority and seek a judicial remedy. The availability of individual rights and exceptions depends on the operation and its legal basis.

Where Russian Federal Law No. 152-FZ applies, you may request information about processing and access to your data, correction, blocking or destruction where the law provides, cessation of processing, and complain to Roskomnadzor or a court. Access requests and responses have a deadline of 10 working days, extendable by no more than 5 working days with a reasoned notice. Confirmed inaccurate information is corrected within 7 working days of receiving supporting information. Cessation and destruction follow the deadlines and exceptions in Articles 20–21, rather than a universal one-month deadline.

For users in other countries, the rights and deadlines under the applicable law apply. An Apple system permission does not, by itself, replace a legally required basis for processing.

## Recipients and international processing

Depending on the feature used, recipients include Apple services, Open Food Facts, Yandex when you contact the support address, and recipients you select for reports. External services also apply their own policies. The absence of a developer-operated server does not mean information is processed exclusively in your country. Processing and storage locations depend on the service and settings; Grams does not promise that all information is held in a single country.

## Changes to this policy

This policy will be updated with a new date when Grams' practices change. Users must be informed of material changes to purposes, data categories, or recipients before new processing starts. Updating the text does not replace a separate permission where one is required for new processing.
