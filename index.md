# Parent Companion
## Privacy Policy — Beta Version

**Effective date: 16 October 2026**

### 1. Introduction

Parent Companion is a mobile application under development to help
parents organize information about their child's growth, daily care,
and important life events.

The application includes an interactive Timeline, growth charts,
and tools for recording measurements and other observations.

This privacy policy describes how information is handled during
the initial beta testing phase on iOS and Android.

### 2. Beta testing restrictions

**The current beta version must be used exclusively with fictional
or synthetic data.**

Testers must not enter genuine personal or medical information,
including identifiable information about children, parents,
or patients.

Parent Companion is not intended for clinical use, diagnosis,
treatment decisions, or management of real patient records.

These restrictions also apply to healthcare professionals
participating in testing.

### 3. Information stored by the application

Parent Companion allows users to create fictional child profiles
and record information such as:

- Growth measurements
- Feeding and sleep records
- Temperature observations
- Timeline events and notes

These records are stored in a local SQLite database on the device.

The application does not require a Parent Companion user account.

The current beta does not automatically synchronize child records
with a developer-operated cloud database.

### 4. Local storage and security

Parent Companion uses operating-system security mechanisms and
additional safeguards implemented within the application.

**On iOS:**

The application uses Apple's application sandbox and file-protection
mechanisms for its local database and associated files.

The database directory is configured to be excluded from ordinary
device backups.

**On Android:**

The application stores its database within Android's private
application storage.

The application is configured to restrict automatic cloud backups
and operating-system-managed device-to-device transfers of
application data.

The Android release APK has been verified not to request internet,
location, camera, microphone, or contacts permissions.

**On both platforms:**

The application enables SQLite's `secure_delete` feature.

Deleting a child profile removes its associated records from the
active local database. A SQLite write-ahead-log checkpoint is
performed to reduce the persistence of deleted information.

These mechanisms do not guarantee that deleted information is
irrecoverable.

The current beta has not undergone an independent comprehensive
security assessment and does not implement separate application-level
database encryption.

Testers must therefore use fictional information only.

### 5. Information transmission and sharing

The application's core record-management functions are designed
to operate locally.

Parent Companion does not automatically upload child records to
a developer-operated cloud database.

Where supported, users may initiate import, export, or sharing
operations.

Information intentionally exported or shared may subsequently
be handled by other applications or services selected by the user.

Only fictional data should be imported, exported, or shared.

### 6. Data deletion

Users can delete a child profile and its associated records
through the application's settings.

Removing the application generally removes its application-specific
local storage, subject to operating-system behavior and any
copies created elsewhere.

Deleting information from Parent Companion does not automatically
delete previously exported or shared copies.

Beta test data may be lost during application removal, resets,
updates, or technical failures.

### 7. Testing diagnostics and feedback

Parent Companion may be distributed through Apple TestFlight
and Google Play testing services.

These platforms may process device information, installation
details, crash reports, usage diagnostics, and testing feedback
under their respective privacy practices.

Testers may voluntarily provide comments, screenshots, or other
feedback to the developer.

Feedback received by the developer is used to identify problems
and improve the application's usability and functionality.

**Feedback and screenshots must not contain genuine personal
or medical information.**

### 8. Data retention

Records entered into Parent Companion remain in local application
storage until deleted, reset, or removed, subject to the device's
storage behavior.

Feedback and diagnostics received by the developer may be retained
for as long as reasonably necessary to investigate reported
problems and evaluate the beta.

Information processed independently by Apple, Google, or other
service providers is subject to their respective policies.

### 9. Future development

Parent Companion is under active development.

Future versions may include additional security mechanisms,
secure backup and recovery, and controlled exchange of structured
information with healthcare systems.

Before supporting genuine personal or clinical information,
additional security validation and appropriate privacy assessments
will be necessary.

This policy will be updated to reflect material changes.

### 10. Privacy contact

**Application:** Parent Companion

**Developer / Data Controller:** Raffaello Ferone
**Country:** Switzerland

**Email:** parentcompanion.app@gmail.com

Questions concerning privacy or information received during
beta testing can be sent to this email address.

### 11. Changes to this policy

This privacy policy may be updated as Parent Companion evolves.

The latest version will remain publicly accessible at this website.
