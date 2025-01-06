# Imaginify - Revolutionizing Image Transformations with AI

Imaginify is an advanced image transformation platform leveraging cutting-edge AI technologies to provide seamless, intuitive, and powerful tools for image restoration, recoloring, background manipulation, object removal, and much more. Designed for creators and enthusiasts alike, Imaginify ensures a dynamic and responsive user experience with secure transactions and state-of-the-art search functionalities.

---

# 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets](#snippets)
6. 🔗 [Links](#links)
7. 🚀 [More](#more)

---

## <a name="tech-stack">⚙️ Tech Stack</a>

- **Next.js**: Scalable React framework for server-side rendering and static web apps.
- **TypeScript**: Type-safe and robust JavaScript alternative.
- **MongoDB**: NoSQL database for flexible data storage.
- **Clerk**: Comprehensive authentication and user management.
- **Cloudinary**: Image and video optimization with cloud-based processing.
- **Stripe**: Secure payment gateway for credit transactions.
- **Shadcn**: Component framework for fast UI development.
- **TailwindCSS**: Utility-first CSS for custom and responsive designs.

---

## <a name="features">🔋 Features</a>

👉 **Authentication and Authorization**: Secure user access with multi-factor authentication, role-based access controls, and protected routes.

👉 **Community Image Showcase**: Paginated display of user transformations for effortless exploration.

👉 **Advanced Image Search**: AI-powered semantic search for locating images by content or objects within.

👉 **Image Restoration**: State-of-the-art tools for reviving old or damaged images.

👉 **Image Recoloring**: Seamlessly adjust or replace object colors with precision.

👉 **Generative Fill**: AI-driven filling of missing or incomplete image areas.

👉 **Object and Background Removal**: Intuitive tools to clean up images with ease.

👉 **Transformed Image Download**: Hassle-free saving and sharing of edited images.

👉 **Transformation Insights**: View detailed history and metadata for each transformation.

👉 **Transformation Management**: User control for updating or deleting image transformations.

👉 **Credits System**: Earn or purchase credits for various transformation operations.

👉 **Profile Management**: Comprehensive dashboard for managing credits, images, and account settings.

👉 **Secure Payments**: Stripe-powered transactions ensuring data security and compliance.

👉 **Responsive Design**: Consistent performance and UX across all devices.

---

## <a name="quick-start">🤸 Quick Start</a>

### **Prerequisites**

Ensure the following are installed on your system:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### **Cloning the Repository**

```bash
# Clone the repository and navigate to the project directory
git clone https://github.com/adrianhajdin/imaginify.git
cd imaginify
```

### **Installation**

Install project dependencies:

```bash
npm install
```

### **Set Up Environment Variables**

Create a `.env.local` file in the root directory and configure it as follows:

```env
# NEXT.js Configuration
NEXT_PUBLIC_SERVER_URL=

# MongoDB Configuration
MONGODB_URL=

# Clerk Configuration
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# Cloudinary Configuration
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

# Stripe Configuration
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

Replace placeholders with your actual credentials from [Clerk](https://clerk.com/), [MongoDB](https://www.mongodb.com/), [Cloudinary](https://cloudinary.com/), and [Stripe](https://stripe.com).

### **Running the Project**

Start the development server:

```bash
npm run dev
```

Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to view the application.

---
