# CRM Project Setup Guide

## Prerequisites
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

### 2. Install Frappe Bench (if not already installed)
```bash
pip install frappe-bench
bench init frappe-bench
cd frappe-bench
```

### 3. Add the CRM App to Your Bench
```bash
bench get-app crm https://github.com/EGichuhi/crm.git
```

### 4. Create a New Site
```bash
bench new-site your-site-name
bench use your-site-name
```

### 5. Install the CRM App
```bash
bench install-app crm
```

### 6. Start the Development Server
```bash
bench start
```

## Development Workflow
- Access the site at `http://your-site-name:8000`
- Admin login credentials will be generated during site creation

## Troubleshooting
- Ensure all prerequisites are installed
- Check Frappe Framework documentation for detailed setup instructions
- Verify Python and Node.js versions are compatible

## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## Contact
For any issues or questions, please open a GitHub issue or contact the repository owner.
