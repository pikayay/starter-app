# Change Log

All notable changes to this project will be documented in this file.

## [Unreleased]

### Added
- Created `profiles` table with declarative schema in `supabase/schemas/profiles.sql`.
- Generated migration `20260301120005_create_profiles.sql` from the declarative schema.
- Added RLS policies to the `profiles` table.
- Added a trigger to automatically create a profile for new users.
- Added a trigger to automatically update the `updated_at` field on profile updates.

## 2026-02-28

### Added
- sign up, sign in, and sign out functionality.
