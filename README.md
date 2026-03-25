# Queenstown Golf Club — Membership Management

A web-based membership management system for Queenstown Golf Club built with Supabase and vanilla JavaScript.

## Features

- **Member Management**: Add, view, and manage club members
- **Payment Tracking**: Record and track membership payment status
- **Dashboard**: View membership statistics and payment metrics
- **Authentication**: Secure login with Supabase Auth
- **Category Management**: Support for Full, Senior, Junior, and Social membership categories

## Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Backend**: Supabase (PostgreSQL + Auth)
- **Deployment**: Static hosting (Netlify/Vercel)

## Setup

### Prerequisites
- A Supabase project with the necessary tables configured
- A modern web browser

### Configuration

1. Update the Supabase credentials in `qgc_membership_supabase.html`:
   ```javascript
   const SUPABASE_URL = 'your-supabase-url';
   const SUPABASE_ANON = 'your-anon-key';
   ```

2. Ensure your Supabase project has these tables:
   - `members` - Members information
   - `payments` - Payment records

3. Create an admin user in Supabase Authentication

### Running Locally

Simply open `qgc_membership_supabase.html` in a modern web browser.

## License

Private - Queenstown Golf Club
