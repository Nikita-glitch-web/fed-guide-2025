# Fed Guide 2025 - Junior Full-Stack Developer Track

Welcome to the Fed Guide 2025! This repository contains comprehensive handbooks and capstone project requirements for junior full-stack developers. The curriculum covers modern web development technologies including Angular, NestJS, and MongoDB.

## 📚 Documentation Overview

This guide is structured into modules covering frontend and backend development:

### Frontend Development (Angular)

- **[1. Angular Basics Handbook](docs/1.%20angular_basics_handbook.md)** - Comprehensive guide to Angular fundamentals, components, services, routing, and testing
- **[1.2 Capstone Requirements](docs/1.2%20capstone_requirements.md)** - Frontend capstone project specifications and requirements

### Backend Development (NestJS + MongoDB)

- **[2. NestJS + MongoDB Basics Handbook](docs/2.%20nest_mongodb_basics_handbook.md)** - Complete guide to building REST APIs with NestJS and MongoDB
- **[2.2 NestJS + MongoDB Capstone](docs/2.2%20nest_mongodb_capstone.md)** - Backend capstone project specifications and requirements

## 🚀 Getting Started

### Prerequisites

- Node.js LTS (recommend using `fnm` or `nvm`)
- Yarn package manager
- Git
- MongoDB (for backend development)
- Docker (optional, for containerized development)

### Clone to Your Personal GitHub Repository

Follow these steps to create your own copy of this repository:

#### Option 1: Fork and Clone (Recommended)

1. **Fork this repository**
   - Click the "Fork" button at the top right of this repository's GitHub page
   - This creates a copy under your GitHub account

2. **Clone your fork**

   ```bash
   git clone https://github.com/YOUR_USERNAME/fed-guide-2025.git
   cd fed-guide-2025
   ```

3. **Set up remote tracking** (optional, to sync with original repo)

   ```bash
   git remote add upstream https://github.com/ORIGINAL_OWNER/fed-guide-2025.git
   git remote -v
   ```

#### Option 2: Create New Repository from Template

1. **Create a new repository** on GitHub with the name `fed-guide-2025`
2. **Clone this repository locally**

   ```bash
   git clone https://github.com/ORIGINAL_OWNER/fed-guide-2025.git
   cd fed-guide-2025
   ```

3. **Change the remote origin to your repository**

   ```bash
   git remote set-url origin https://github.com/YOUR_USERNAME/fed-guide-2025.git
   ```

4. **Push to your new repository**

   ```bash
   git push -u origin main
   ```

#### Option 3: Download and Upload

1. **Download** this repository as a ZIP file
2. **Extract** the contents to your local machine
3. **Create a new repository** on GitHub
4. **Initialize git and push**

   ```bash
   git init
   git add .
   git commit -m "Initial commit: Fed Guide 2025"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/fed-guide-2025.git
   git push -u origin main
   ```

### Sync with Original Repository (if forked)

To keep your fork up to date with the original repository:

```bash
# Fetch updates from the original repository
git fetch upstream

# Merge updates into your main branch
git checkout main
git merge upstream/main

# Push updates to your fork
git push origin main
```

## 📋 Learning Path

### Phase 1: Frontend Development (Angular)

1. Start with the **[Angular Basics Handbook](docs/1.%20angular_basics_handbook.md)**
2. Follow the step-by-step instructions to build Angular applications
3. Complete the **[Frontend Capstone Project](docs/1.2%20capstone_requirements.md)**

### Phase 2: Backend Development (NestJS + MongoDB)

1. Study the **[NestJS + MongoDB Basics Handbook](docs/2.%20nest_mongodb_basics_handbook.md)**
2. Learn REST API development, authentication, and database integration
3. Complete the **[Backend Capstone Project](docs/2.2%20nest_mongodb_capstone.md)**

### Phase 3: Full-Stack Integration

1. Integrate your Angular frontend with your NestJS backend
2. Implement authentication flows and data synchronization
3. Deploy your full-stack application

## 🛠️ Project Structure

```text
fed-guide-2025/
├── docs/                                    # Documentation and handbooks
│   ├── 1. angular_basics_handbook.md       # Angular fundamentals guide
│   ├── 1.2 capstone_requirements.md        # Frontend capstone specs
│   ├── 2. nest_mongodb_basics_handbook.md  # NestJS + MongoDB guide
│   └── 2.2 nest_mongodb_capstone.md        # Backend capstone specs
└── README.md                               # This file
```

## 🎯 Learning Objectives

By completing this guide, you will:

- ✅ Master Angular framework fundamentals
- ✅ Build responsive, component-based user interfaces
- ✅ Implement routing, forms, and state management
- ✅ Create secure REST APIs with NestJS
- ✅ Design and implement MongoDB database schemas
- ✅ Implement JWT authentication and authorization
- ✅ Write comprehensive tests (unit and e2e)
- ✅ Deploy applications to production environments
- ✅ Follow industry best practices and security guidelines

## 📞 Support

If you encounter any issues or have questions:

1. Check the documentation in the respective handbook
2. Review the examples and acceptance criteria in each section
3. Create an issue in your repository with a detailed description
4. Follow the learning path sequentially for best results

## 📝 License

This educational content is provided for learning purposes. Please check individual project requirements for specific licensing terms.

---

**Happy Learning!** 🚀

Start your journey with the [Angular Basics Handbook](docs/1.%20angular_basics_handbook.md) and work your way through each module systematically.
