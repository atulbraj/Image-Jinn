# Image-Jinn

Image-Jinn is a cutting-edge AI image processing platform. It integrates advanced image processing features, a secure payment system, and a robust image search functionality. Whether you're looking to restore, recolor, remove objects, generatively fill, or remove backgrounds, Image-Jinn has got you covered.

## 🔧 Tech Stack
- **Next.js**
- **TypeScript**
- **MongoDB**
- **Clerk**
- **Cloudinary**
- **Stripe**
- **Shadcn**
- **TailwindCSS**

## 🚀 Features
- **Authentication and Authorization**: Secure user access with registration, login, and route protection.
- **Community Image Showcase**: Explore user transformations with pagination.
- **Advanced Image Search**: Find images quickly and accurately by content or objects present inside the image.
- **Image Restoration**: Revive old or damaged images effortlessly.
- **Image Recoloring**: Customize images by replacing objects with desired colors.
- **Image Generative Fill**: Seamlessly fill in missing areas of images.
- **Object Removal**: Clean up images by removing unwanted objects with precision.
- **Background Removal**: Extract objects from backgrounds easily.
- **Download Transformed Images**: Save and share AI-transformed images conveniently.
- **Transformed Image Details**: View transformation details for each image.
- **Transformation Management**: Control over deletion and updates of transformations.
- **Credits System**: Earn or purchase credits for image transformations.
- **Profile Page**: Access transformed images and credit information.
- **Credits Purchase**: Securely buy credits via Stripe for uninterrupted use.
- **Responsive UI/UX**: A seamless experience across devices with a user-friendly interface.

## ⚙️ Quick Start
Follow these steps to set up Image-Jinn locally on your machine.

### Prerequisites
Make sure you have the following installed on your machine:
- **Git**
- **Node.js**
- **npm (Node Package Manager)**

### Cloning the Repository
```sh
git clone https://github.com/atulbraj/Image-Jinn.git
cd <Navigate to Folder>
```

### Installation
Install the project dependencies using npm:
```sh
npm install
npm run dev
```

### Set Up Environment Variables
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
Replace the placeholder values with your actual account credentials from Clerk, MongoDB, Cloudinary, and Stripe.

### Running the Project
```sh
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## 🕸️ Snippets
- `tailwind.config.ts`
- `globals.css`
- `constants/index.ts`
- `user.model.ts`
- `transaction.model.ts`
- `InsufficientCreditsModal.tsx`
- `user.action.ts`
- `utils.ts`
- `types/index.d.ts`
- `api/webhooks/clerk/route.ts`
- `components/shared/CustomField.tsx`
- `components/shared/Collection.tsx`
- `components/shared/Search.tsx`
- `image.actions.ts`
- `transformations/[id]/page.tsx`
- `transformations/[id]/update/page.tsx`
- `components/shared/DeleteConfirmation.tsx`
- `api/webhooks/stripe/route.ts`
- `credits/page.tsx`
- `components/shared/Checkout.tsx`
- `profile/page.tsx`
