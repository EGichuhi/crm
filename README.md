# Frappe CRM Project

## Overview
This is a custom Customer Relationship Management (CRM) application built using the Frappe Framework, designed to provide robust customer management capabilities.

## Prerequisites
Before setting up the project, ensure you have the following installed:
- Git
- Python (3.7+)
- Node.js (14+)
- Frappe Framework
- Bench CLI

## Local Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/EGichuhi/crm.git
cd crm
```

### 2. Install Frappe Bench
```bash
pip install frappe-bench
bench init frappe-bench
cd frappe-bench
```

### 3. Add CRM App to Bench
```bash
bench get-app crm https://github.com/EGichuhi/crm.git
```

### 4. Create a New Site
```bash
bench new-site your-site-name
bench use your-site-name
```

### 5. Install CRM App
```bash
bench install-app crm
```

### 6. Start Development Server
```bash
bench start
```

## Accessing the Application
- Site URL: `http://your-site-name:8000`
- Admin credentials will be generated during site creation

## Development Workflow

### Setting Up Development Environment
1. Use Visual Studio Code for editing
2. Recommended VSCode Extensions:
   - Python
   - Frappe
   - ERPNext
   - Pylance

### Version Control
- Use Git for tracking changes
- Create feature branches for new developments
- Follow conventional commit messages

## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## Troubleshooting
- Ensure all prerequisites are installed
- Check Frappe Framework documentation
- Verify Python and Node.js compatibility
- Consult GitHub issues for known problems

## Contact
For issues or questions:
- Open a GitHub issue
- Contact the repository owner

## License
[Add License Information Here]

## Acknowledgments
- Frappe Framework
- Original Project Contributors
```

Would you like me to modify anything about the README?
