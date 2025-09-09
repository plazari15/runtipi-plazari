# Blinko

Blinko is a self-hosted note-taking and knowledge management application that helps you capture, organize, and retrieve your thoughts and ideas efficiently.

## Features

- **Self-hosted**: Keep your data private and under your control
- **Note-taking**: Create and organize notes with ease
- **Knowledge management**: Build your personal knowledge base
- **Search capabilities**: Find your information quickly
- **Modern web interface**: Clean and intuitive user experience
- **PostgreSQL backend**: Reliable and robust data storage

## Getting Started

After installation, you can access Blinko through your Tipi dashboard. The application will be available on port 1111.

### Important Configuration Notes

- **NEXTAUTH_SECRET**: This must be a secure, random string of at least 32 characters. This is crucial for authentication security.
- **Database Password**: Choose a strong password for your PostgreSQL database.
- **Domain Configuration**: If you plan to use SSO or access Blinko from a custom domain, make sure to set the NEXTAUTH_URL and NEXT_PUBLIC_BASE_URL accordingly.

## Data Persistence

Your Blinko data is stored in:
- Application data: `${APP_DATA_DIR}/data/blinko`
- Database data: `${APP_DATA_DIR}/data/postgres`

This ensures your notes and configuration are preserved across container updates.

## Support

For more information and support, visit the [Blinko GitHub repository](https://github.com/blinkospace/blinko).
