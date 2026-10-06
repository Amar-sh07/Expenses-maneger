# ExpenseFlow Pro Android

A native Android WebView shell around the ExpenseFlow Pro mobile finance app. The app uses the existing Supabase project for email/password authentication and PostgreSQL data with RLS.

## Features
- Expense and income tracking
- Categories and payment methods
- Monthly budgets
- Reports and category spending
- Profile and sign-out
- Supabase authentication
- Responsive mobile UI
- ExpenseFlow Pro logo and splash assets

## Build
Open this folder in Android Studio and let Gradle sync, then run:
`./gradlew assembleDebug`

The debug APK will be generated at:
`app/build/outputs/apk/debug/app-debug.apk`

## Important
The Supabase publishable key is intended for client-side use. Database security must remain enforced by Supabase RLS policies.
