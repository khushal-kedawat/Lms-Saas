# LMS SaaS - AI-Powered Learning Management System

![LMS SaaS Banner](https://via.placeholder.com/1200x400/1a1a1a/ffffff?text=LMS+SaaS+-+AI-Powered+Learning+Platform)

## 🚀 Overview

LMS SaaS is a comprehensive Learning Management System designed to revolutionize online education through AI-powered course creation and management. This platform enables educators, institutions, and businesses to create, manage, and deliver engaging educational content with the help of artificial intelligence.

### ✨ Key Features

- **🤖 AI-Powered Course Creation** - Generate course content, quizzes, and assessments using advanced AI
- **📚 Course Management** - Create, organize, and manage courses with intuitive interfaces
- **👥 User Management** - Multi-role support for administrators, instructors, and students
- **💳 Subscription Management** - Flexible pricing plans and payment processing
- **📊 Analytics Dashboard** - Comprehensive insights into learning progress and engagement
- **🎯 Interactive Learning** - Multimedia content support with interactive elements
- **📱 Responsive Design** - Seamless experience across all devices
- **🔒 Secure Authentication** - Enterprise-grade security and user authentication

## 🛠️ Tech Stack

### Frontend
- **Next.js** - React framework for production
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/ui** - Modern UI components
- **React Query** - Data fetching and state management

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling

### AI & External Services
- **OpenAI API** - AI-powered content generation
- **Stripe** - Payment processing
- **Cloudinary** - Media management
- **Resend** - Email services

### Development Tools
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Husky** - Git hooks
- **Docker** - Containerization

## 📦 Installation

### Prerequisites

- Node.js (v18 or higher)
- MongoDB (v5.0 or higher)
- npm or yarn package manager

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/khushal-kedawat/Lms-Saas.git
   cd Lms-Saas
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Environment Setup**
   ```bash
   cp .env.example .env.local
   ```

4. **Configure environment variables**
   ```env
   # Database
   MONGODB_URI=mongodb://localhost:27017/lms-saas
   
   # Authentication
   NEXTAUTH_SECRET=your-nextauth-secret
   NEXTAUTH_URL=http://localhost:3000
   
   # AI Services
   OPENAI_API_KEY=your-openai-api-key
   
   # Payment Processing
   STRIPE_SECRET_KEY=your-stripe-secret-key
   STRIPE_PUBLISHABLE_KEY=your-stripe-publishable-key
   STRIPE_WEBHOOK_SECRET=your-stripe-webhook-secret
   
   # Media Storage
   CLOUDINARY_CLOUD_NAME=your-cloudinary-name
   CLOUDINARY_API_KEY=your-cloudinary-api-key
   CLOUDINARY_API_SECRET=your-cloudinary-api-secret
   
   # Email
   RESEND_API_KEY=your-resend-api-key
   ```

5. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🐳 Docker Setup

1. **Build and run with Docker Compose**
   ```bash
   docker-compose up --build
   ```

2. **Access the application**
   - Frontend: http://localhost:3000
   - API: http://localhost:3001

## 🚀 Deployment

### Vercel (Recommended for Frontend)

1. **Connect your GitHub repository to Vercel**
2. **Configure environment variables**
3. **Deploy automatically on push to main branch**

### Railway/Heroku (Backend)

1. **Create a new project**
2. **Connect your repository**
3. **Set environment variables**
4. **Deploy**

### Docker Deployment

```bash
# Build production image
docker build -t lms-saas .

# Run container
docker run -p 3000:3000 lms-saas
```

## 📚 Usage

### For Administrators

1. **Dashboard Access** - Monitor system-wide metrics and user activity
2. **User Management** - Manage instructors and students
3. **Course Oversight** - Review and approve courses
4. **Subscription Management** - Handle billing and payments

### For Instructors

1. **Course Creation** - Use AI to generate course outlines and content
2. **Content Management** - Upload videos, documents, and interactive materials
3. **Student Progress** - Track student engagement and performance
4. **Assessment Tools** - Create quizzes and assignments

### For Students

1. **Course Enrollment** - Browse and enroll in courses
2. **Learning Progress** - Track completion and achievements
3. **Interactive Learning** - Engage with multimedia content
4. **Assessments** - Take quizzes and submit assignments

## 🔧 API Documentation

### Authentication Endpoints

```
POST /api/auth/login
POST /api/auth/register
POST /api/auth/logout
GET  /api/auth/me
```

### Course Management

```
GET    /api/courses
POST   /api/courses
GET    /api/courses/:id
PUT    /api/courses/:id
DELETE /api/courses/:id
```

### User Management

```
GET    /api/users
GET    /api/users/:id
PUT    /api/users/:id
DELETE /api/users/:id
```

For complete API documentation, visit `/api/docs` when running the development server.

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Workflow

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Code Standards

- Follow ESLint and Prettier configurations
- Write meaningful commit messages
- Add tests for new features
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React framework for production
- [OpenAI](https://openai.com/) - AI-powered content generation
- [Stripe](https://stripe.com/) - Payment processing
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework

## 📞 Support

- **Documentation**: [docs.yourapp.com](https://docs.yourapp.com)
- **Email**: support@yourapp.com
- **Discord**: [Join our community](https://discord.gg/yourapp)
- **Issues**: [GitHub Issues](https://github.com/khushal-kedawat/Lms-Saas/issues)



---

<div align="center">
  <p>Made with ❤️ by <a href="https://github.com/khushal-kedawat">Khushal Kedawat</a></p>
  <p>
    <a href="https://github.com/khushal-kedawat/Lms-Saas/stargazers">⭐ Star this project</a> •
    <a href="https://github.com/khushal-kedawat/Lms-Saas/issues">Report Bug</a> •
    <a href="https://github.com/khushal-kedawat/Lms-Saas/issues">Request Feature</a>
  </p>
</div>