## Data we store

Git Stronk Workout Tracker stores people names, routines, exercises, notes, session history, working weights, max weights, weight logs, and settings in AsyncStorage on the device. There is no developer backend.

## Backups and network

On Android, Auto Backup can copy app data to the user's Google account when device backup is enabled. That is the user's Google backup, not developer servers. On iOS, backup can include app data. The platform runtime may use the network. We do not sync to a developer server, and workout data is not sent to a developer server.

## CSV import and export

CSV import uses a document picker so you choose the file. On Android, export can save to a folder you choose, or you can share the file. On iOS, export uses the system share sheet.

## Permissions we use

Rest and timed-circuit countdown notifications and background countdown sound keep countdown audio running. Rest-timer haptics provide feedback. CSV uses the document picker, folder save, and share as described above.

## Deleting data

Uninstall removes all local workout data. The app does not offer a single clear-all button. You can delete a person or delete a routine in the app. You can discard an in-progress workout.

## Accounts, sale, and analytics

No account is required. We do not sell your data. We do not use third-party analytics.
