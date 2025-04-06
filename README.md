# AI News Portal

A modern news aggregation platform built with Django and Tailwind CSS that automatically scrapes and presents news from various sources.

## Features

### News Management
- Automated news scraping from multiple sources
- Article categorization and filtering
- Advanced search capabilities
- Reading time estimation
- Social sharing functionality

### Modern UI
- Responsive design using Tailwind CSS
- Dark mode support with system preference detection
- Modern animations and transitions
- Enhanced typography with Google Fonts
- Icon integration with Font Awesome

### Service Management
- Service status monitoring dashboard
- Configurable scraper settings
- Service logs and error tracking
- Service restart capabilities

## Technical Stack

- **Backend**: Django
- **Frontend**: Tailwind CSS, JavaScript
- **Database**: SQLite/PostgreSQL
- **Task Queue**: Redis, Celery
- **Additional Libraries**:
  - Font Awesome for icons
  - Google Fonts for typography

## Setup

1. Clone the repository
```bash
git clone <repository-url>
cd newsportal_project
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run migrations
```bash
python manage.py migrate
```

4. Start the development server
```bash
python manage.py runserver
```

## Usage

### News Browsing
- Visit the homepage to see the latest news articles
- Use filters to sort by date, source, or search terms
- Click on articles to read full content
- Share articles using the share button
- Toggle dark mode using the theme switcher

### Service Management
- Access the service status dashboard at `/service/status/`
- Monitor scraper status and logs
- Configure scraper settings
- Restart services when needed

## Development

### Project Structure
```
newsportal_project/
├── news/
│   ├── scrapers/         # News scraper implementations
│   ├── services/         # Service implementations
│   ├── templates/        # HTML templates
│   ├── management/       # Management commands
│   └── views.py         # View controllers
├── static/              # Static assets
└── newsportal_project/  # Project settings
```

### Key Components

1. **News Scrapers**
   - Configurable scraping intervals
   - Multiple source support
   - Error handling and logging

2. **Service Monitoring**
   - Real-time status updates
   - Error tracking
   - Service management interface

3. **User Interface**
   - Responsive design
   - Dark mode support
   - Modern UI components

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.