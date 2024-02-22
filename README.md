# Imaginify: An AI SaaS Platform

An AI image SaaS platform that excels in image processing capabilities, integrates a secure payment infrastructure, offers advanced image search functionalities, and supports multiple AI features, including image restoration, recoloring, object removal, generative filling, and background removal. This project can be a guide for your next AI image tool and a boost to your portfolio.


### Live Demo: https://project-imaginify.netlify.app/

## Tech Stack

- Next.js
- TypeScript
- MongoDB
- Clerk
- Cloudinary
- Stripe
- Shadcn
- TailwindCSS

## About the project 

- Secure user access: Registration, login, and route protection.
- Community Image Showcase: Easy navigation with pagination.
- Advanced Image Search: Quick and accurate content-based search.
- Image Restoration: Effortless revival of old or damaged images.
- Image Recoloring: Simple customization with color replacement.
- Image Generative Fill: Seamless filling of missing areas.
- Object Removal: Precise cleanup by removing unwanted objects.
- Background Removal: Easy extraction of objects from backgrounds.
- Download Transformed Images: Convenient saving and sharing.
- Transformed Image Details: Detailed information on transformations.
- Transformation Management: Control over deletion and updates.
- Credits System: Earn or purchase credits for transformations.
- Profile Page: Personal access to images and credit info.
- Credits Purchase: Secure buying via Stripe.
- Responsive UI/UX: Seamless cross-device experience.

## Getting Started

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/moinuddinrao/project_imaginify.git
cd project_imaginify
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#NEXT
NEXT_PUBLIC_SERVER_URL=

#MONGODB
MONGODB_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#CLOUDINARY
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Replace the placeholder values with your actual respective account credentials. You can obtain these credentials by signing up on the [Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/), [Cloudinary](https://cloudinary.com/) and [Stripe](https://stripe.com)

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project. 
