# AWS Bootcamp Cloud App

A Next.js application for managing AWS Cloud Practitioner bootcamp registrations.

## Features

- Bootcamp Schedule Display
- Session Registration
- Instructor Information
- Course Content Overview

## Tech Stack

- Next.js 14
- TypeScript
- Tailwind CSS
- AWS Services (upcoming)
  - AppSync
  - DynamoDB
  - Lambda
  - SES

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/RendaniXcode/freebootcamp-cloudapp.git
cd freebootcamp-cloudapp
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
src/
├── app/
│   ├── page.tsx (Home)
│   ├── bootcamp/
│   │   └── page.tsx (Schedule)
│   └── register/
│       └── page.tsx (Registration)
├── components/
│   └── common/
└── types/
    └── index.ts
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.
