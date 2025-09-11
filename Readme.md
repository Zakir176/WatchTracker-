# WatchTracker 🎬

A beautiful, responsive web application for tracking your movies and anime watchlist. Keep organized with what you want to watch and what you've already completed!

![WatchTracker Preview](https://via.placeholder.com/800x400/667eea/ffffff?text=WatchTracker+Preview)

## ✨ Features

### 🎯 Core Functionality
- **Add Items**: Easily add movies, anime, series, and documentaries to your watchlist
- **Track Progress**: Mark items as completed when you've watched them
- **Smart Filtering**: Filter by content type or completion status
- **Quick Management**: Delete items you no longer need
- **Real-time Stats**: View your watching progress at a glance

### 🎨 User Experience
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations
- **Type Recognition**: Color-coded badges for different content types
- **Interactive Elements**: Hover effects and smooth transitions
- **Intuitive Interface**: Clean, user-friendly design

### 📊 Organization Features
- **Multiple Content Types**: Movies, Anime, Series, Documentaries
- **Filter Options**: All, by type, completed, or pending items
- **Statistics Dashboard**: Track total items, completed count, and pending items
- **Date Tracking**: See when you added each item to your list

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or dependencies required!

### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/watchtracker.git
   cd watchtracker
   ```

2. **Open the application**
   ```bash
   # Simply open index.html in your browser
   open index.html
   # Or on Windows
   start index.html
   # Or on Linux
   xdg-open index.html
   ```

3. **Start tracking!**
   - Add your first movie or anime
   - Organize with filters
   - Mark items as complete when watched

## 🎮 Usage Guide

### Adding Items
1. Enter the title of the movie/anime you want to watch
2. Optionally add the release year
3. Select the content type (Movie, Anime, Series, Documentary)
4. Click "Add to List" or press Enter

### Managing Your List
- **Mark as Watched**: Click the checkbox next to any item
- **Filter Items**: Use the filter buttons to view specific categories
- **Delete Items**: Click the red "Delete" button to remove items
- **View Stats**: Check your progress in the statistics section

### Keyboard Shortcuts
- **Enter**: Add item when title input is focused
- **Tab**: Navigate between input fields

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with gradients, animations, and flexbox
- **Vanilla JavaScript**: No frameworks or dependencies
- **Responsive Design**: CSS Grid and Flexbox for all screen sizes

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

### File Structure
```
watchtracker/
├── index.html          # Main application file
├── README.md           # This documentation
└── LICENSE            # MIT License
```

## 🎨 Customization

### Changing Colors
The app uses CSS custom properties for easy theming. Main colors are defined in the CSS:
```css
/* Primary gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Accent colors */
--movie-color: #ff6b6b;
--anime-color: #4ecdc4;
--series-color: #45b7d1;
--documentary-color: #96ceb4;
```

### Adding New Content Types
1. Add a new button in the type selector section
2. Add corresponding CSS class for the badge color
3. Update the JavaScript `selectedType` options

## 📱 Screenshots

### Desktop View
- Clean, spacious layout with all features visible
- Hover effects and smooth animations
- Easy-to-use filter and type selection

### Mobile View
- Responsive design adapts to smaller screens
- Touch-friendly buttons and inputs
- Maintains full functionality

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Make your changes**
4. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
5. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
6. **Open a Pull Request**

### Development Guidelines
- Keep the code simple and readable
- Maintain the existing code style
- Test on multiple browsers and devices
- Update documentation for new features

## 🐛 Issue Reporting

Found a bug or have a feature request? Please open an issue on GitHub with:

- **Bug Reports**: Steps to reproduce, expected vs actual behavior, browser/device info
- **Feature Requests**: Clear description of the proposed feature and its benefits
- **Questions**: Use the discussions tab for general questions

## 📋 Roadmap

### Planned Features
- [ ] **Local Storage**: Persist data between sessions
- [ ] **Import/Export**: Backup and restore your watchlist
- [ ] **Ratings System**: Rate movies and anime after watching
- [ ] **Notes**: Add personal notes to each item
- [ ] **Search**: Search through your watchlist
- [ ] **Sorting**: Sort by title, year, date added, etc.
- [ ] **Genres**: Categorize by genre
- [ ] **Recommendations**: Get suggestions based on your list

### Future Enhancements
- **API Integration**: Fetch movie/anime details from external APIs
- **Social Features**: Share your watchlist with friends
- **Statistics**: More detailed viewing statistics and charts
- **Themes**: Multiple color themes to choose from
- **PWA Support**: Install as a progressive web app

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 WatchTracker

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👥 Authors

- **Your Name** - *Initial work* - [YourGitHub](https://github.com/yourusername)

## 🙏 Acknowledgments

- Inspired by the need for a simple, beautiful watchlist tracker
- Icons and emojis from various sources
- Modern web design principles and best practices
- The anime and movie communities for inspiration

---

**⭐ Star this repository if you found it helpful!**

## 🔗 Links

- **Live Demo**: [Add your GitHub Pages link here]
- **Report Issues**: [GitHub Issues](https://github.com/yourusername/watchtracker/issues)
- **Discussions**: [GitHub Discussions](https://github.com/yourusername/watchtracker/discussions)

---

*Made with ❤️ for movie and anime enthusiasts*