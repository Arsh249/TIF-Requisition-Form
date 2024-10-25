# Multi-Step Form with Live Preview

This project features a multi-step form that allows users to input their information across several steps, with a live preview section that updates as they fill out the form. Each step of the form requires successful submission before the user can proceed to the next step, ensuring that all necessary data is collected and validated.

## Features

- **Multi-Step Form**: Users can navigate through multiple steps to complete the form.
- **Live Preview**: The preview section updates in real-time as users enter values in the form fields.
- **Field Validation**: Each form includes validation to ensure all required fields are filled out correctly. If any field has an error, the form will not proceed to the next step.
- **Previous Values Saved**: When navigating back to previous steps, the values entered are retained and pre-filled in the form, allowing users to review and modify their inputs easily.

## Improvements

### Added Validations
Validations were previously missing from the Interview Settings form. These have now been implemented to ensure all fields meet the required criteria before submission.

### Bug Fixes
- Fixed an issue in the Job Details form where submitting the form did not allow the user to progress to the next step, even when there were no visible errors. This has been resolved, ensuring a smooth transition between steps when the form is filled out correctly.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
