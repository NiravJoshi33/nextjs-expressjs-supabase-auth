# NextJs-ExpressJs-Supabase Authentication Example

This repo demonstrates how to implement server-side authentication using Supabase with NextJs for Frontend and Express Js for Backend. Supabase's documentation doesn't have a dedicate guide for Express Js, so I thought I should make one to aid myself and others in the future.

## Code

For ease of deployment, I have split frontend and backend code into separate repos.

- [Frontend Repo](https://github.com/NiravJoshi33/supabase-auth-backend)
- [Backend Repo](https://github.com/NiravJoshi33/supabase-auth-backend)

## Features

- Cookie Based Authentication
- Email Verification
- Authentication Methods
  - Email/Password
  - OAuth (Google)

## Why Separate Express Js Backend if Already Using NextJs?

- If you have apps on multiple platforms (i.e. web, android, ios etc), single backend can server all the apps.
- Support for Websocket Connection & Long-running processes
- Separation of Concerns
