# StackIt - A Minimal Q&A Forum Platform (Frontend Only)

StackIt is a modern, minimal question-and-answer platform designed for collaborative learning and structured knowledge sharing. Built with React and using local storage for data persistence, it provides a clean and intuitive interface for asking questions, providing answers, and engaging with the community.

## 🚀 Features

### Core Features
- **Ask Questions**: Create detailed questions with rich text formatting
- **Answer Questions**: Provide comprehensive answers
- **Voting System**: Upvote and downvote questions and answers
- **Accept Answers**: Mark the best answer for your questions
- **Tagging System**: Organize content with relevant tags
- **Search Functionality**: Find questions quickly with powerful search
- **Local Storage**: All data persists in your browser

### User Management
- **User Registration & Login**: Secure authentication system
- **User Profiles**: Customizable profiles with bio and stats
- **Role-based Access**: Guest, User, and Admin roles
- **Reputation System**: Build reputation through quality contributions

### Community Features
- **View Tracking**: Track question views and engagement
- **Popular Tags**: Discover trending topics
- **Demo Data**: Pre-loaded with sample questions and answers

## 🛠️ Tech Stack

### Frontend
- **React** - UI library
- **React Router** - Navigation
- **Tailwind CSS** - Styling
- **Framer Motion** - Animations
- **React Hot Toast** - Notifications
- **Local Storage** - Data persistence

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd stackit-qa-forum
   ```

2. **Install dependencies**
   ```bash
   npm run install-all
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 🗄️ Data Storage

The application uses browser local storage for data persistence:
- **Users**: User accounts and profiles
- **Questions**: Questions with metadata
- **Answers**: Answers to questions
- **Notifications**: User notifications

### Demo Credentials
- **Email**: `demo@stackit.com`
- **Password**: `demo123`

## 🔧 Configuration

### Environment Variables

No environment variables are required for the frontend-only version.

### Features

| Feature | Status |
|---------|--------|
| User Registration | ✅ Working |
| User Login | ✅ Working |
| Ask Questions | ✅ Working |
| Answer Questions | ✅ Working |
| Voting System | ✅ Working |
| Search & Filter | ✅ Working |
| Tags System | ✅ Working |
| Local Storage | ✅ Working |

## 🎨 Features in Detail

### Authentication System
- User registration with username, email, and password
- Secure login with email and password
- Session persistence using local storage
- Demo user account included

### Question Management
- Create detailed questions with title, content, and tags
- Rich text support for question content
- Tag system for categorization
- Search and filter functionality

### Answer System
- Provide comprehensive answers to questions
- Vote on answers (upvote/downvote)
- Accept best answers
- Track answer counts

### Voting System
- Upvote/downvote questions and answers
- Prevent duplicate votes
- Track vote counts
- Build user reputation

### Search & Discovery
- Full-text search across questions
- Tag-based filtering
- Sort by newest, votes, views
- Popular tags discovery

## 🚀 Deployment

### Frontend Deployment
1. Build the application: `npm run build`
2. Deploy the `client/build` folder to your hosting service

### Popular Deployment Options
- **Vercel**: Connect your GitHub repository
- **Netlify**: Drag and drop the build folder
- **GitHub Pages**: Use GitHub Actions for automatic deployment
- **Firebase Hosting**: Use Firebase CLI

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📝 License

This project is licensed under the MIT License.

## 🆘 Support

For support and questions:
- Create an issue in the repository
- Check the documentation
- Review the features list

## 🎯 Roadmap

- [ ] Rich text editor integration
- [ ] Image upload support
- [ ] Export/import data functionality
- [ ] Dark mode theme
- [ ] Mobile app
- [ ] Offline support
- [ ] Data backup/restore
- [ ] Advanced search filters
- [ ] User badges and achievements
- [ ] Internationalization

## 🔄 Migration from Backend Version

If you're migrating from the backend version:

1. **Data Export**: Export your data from the backend
2. **Data Import**: The frontend version includes demo data
3. **User Accounts**: Create new accounts in the frontend version
4. **Features**: All core features are available in the frontend version

---

**StackIt** - Making knowledge sharing simple and effective, now with local storage for complete privacy and offline functionality. 