# Software Engineering Take-Home Exercise

## Objective

Investment bankers and M&A advisors spend significant time performing repetitive tasks, such as identifying portfolio companies listed on private equity firms' websites. Your task is to create a functional full-stack web application that automates this process. Users should be able to input a private equity firm's website URL, and your system must comprehensively and accurately extract and display the names and descriptions of all portfolio companies listed.

## Key Requirements

### Frontend (Next.js)

- Create a simple and clear user interface using Next.js.
- Provide an input field for users to submit the URL of a private equity firm's website.
- Display the extracted portfolio companies' names and descriptions clearly on the webpage.

### Backend (Flexible)

- You may use Next.js server actions, API routes, or any other backend language/framework of your preference.
- Your backend must perform web scraping and/or use AI-driven methods to parse and extract portfolio company data.
- Ensure accurate and comprehensive extraction of:
  - **Company Names**
  - **Company Descriptions**

### Evaluation Examples

Test your application thoroughly using these example private equity firm websites:
- [https://ancorcapital.com/](https://ancorcapital.com/)
- [https://stellapoint.com/](https://stellapoint.com/)
- [https://global.abb/group/en/technology/ventures](https://global.abb/group/en/technology/ventures)
- [https://www.angelesequity.com/portfolio](https://www.angelesequity.com/portfolio)
- [https://www.assemblyventures.com](https://www.assemblyventures.com)
- [https://astaracapital.com/](https://astaracapital.com/)
- [https://cfb.com/](https://cfb.com/)
- [https://www.chartline.com/](https://www.chartline.com/)
- [https://www.edgewaterfunds.com/](https://www.edgewaterfunds.com/)
- [https://engineventures.com/](https://engineventures.com/)
- [https://cowlescompany.com/](https://cowlescompany.com/)

Your solution should handle varying HTML structures and potential complexities present across these examples.

## Technical and AI Considerations

- You're encouraged to utilize AI/ML or NLP tools to enhance the comprehensiveness and accuracy of data extraction.
- Clearly document any AI models, scraping libraries, APIs, or external services used.
- How would you evaluate the output of the system?

## Testability and Deployment

- Ensure your app can be easily tested:
  - Provide clear instructions for local setup and execution.
  - Optionally, deploy your app using services such as Vercel (not mandatory).

## Submission Requirements

- Include a detailed README covering:
  - Setup and installation instructions.
  - Technologies and methodologies used.
  - Challenges faced and how you overcame them.
  - Any trade-offs or limitations.
- Provide clear documentation and structured code with comments for readability.

### Evaluation Criteria

- **Comprehensiveness**: Ability to extract all portfolio companies from provided websites.
- **Accuracy**: Correct extraction of company names and descriptions.
- **Robustness**: The app should handle various website structures gracefully.
- **Code Quality**: Readable, maintainable, and well-documented code.
- **Innovation**: Effective use of AI/ML or other intelligent scraping techniques.

UI/UX design is not evaluated; functionality is the key priority.

# Setup Instruction

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
