# Architecture Plan

## A. Demo
index.html
- Header
- Hero
- Trust strip
- About
- Services
- Doctors
- Why Us
- Reviews
- Emergency CTA
- Location
- Appointment
- Footer
- Floating actions

## B. Production
app/
  layout
  page
  components/
    Header
    Hero
    TrustStrip
    About
    Services
    Doctors
    Reviews
    EmergencyCTA
    Location
    AppointmentForm
    Footer
  lib/
    validation
    analytics
    api
  styles/

backend/
  appointments
  admin
  notifications
  auth
  rate-limit

database/
  appointments
  admins
  audit_logs
  site_settings

## C. Data model
Appointment:
id
name
phone
preferred_date
message
status
created_at
updated_at

Status:
new
contacted
confirmed
completed
cancelled

## D. Security
- Server-side validation
- Rate limiting
- CAPTCHA/anti-spam
- HTTPS
- Secrets only server-side
- Admin RBAC
- Audit logs
- No patient medical data in public frontend
