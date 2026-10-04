# Ghraba MVP

MVP Android-ready for invoice/decharge tracking.

## Included
- Dashboard
- Invoice list
- Search and status filters
- Add invoice
- Invoice detail
- Status workflow: Non reçue -> Décharge -> Facturée
- Local persistence with SharedPreferences
- French UI
- No external backend required for the first run

## Run
Install Flutter 3.x, then:

```bash
flutter pub get
flutter run
```

## Build APK

```bash
flutter build apk --release
```

APK output:
`build/app/outputs/flutter-apk/app-release.apk`

## Android Studio
Open this folder in Android Studio or VS Code after installing Flutter.

## Production next step
Replace the local repository with Supabase:
- Auth
- PostgreSQL
- Storage for invoice/decharge documents
- RLS
- Notifications

The database schema is included in `supabase/schema.sql`.
