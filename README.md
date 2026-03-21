# VPS Monitor Pro+ Ultimate Setup Guide 🚀

## 📦 PREREQUISITES

### Update System
sudo apt update && sudo apt upgrade -y

### Install Node.js (v18+)
curl -sL https://deb.nodesource.com/setup_23.x | sudo bash -
sudo apt install -y nodejs

### Verify Installation
node --version
npm --version

### Install Git
sudo apt install git -y

## 🚀 INSTALLATION STEPS

### 1. Clone Repository
git clone https://github.com/jlpggamerz/status-page

### 2. Navigate to Directory
cd status-page

### 3. Install Dependencies
npm install

## 🎯 STARTING THE APPLICATION

### OPTION A: Direct Start (Development)
npm start

### Install PM2 Globally
npm install pm2@latest -g

### Start Application with PM2
pm2 start app.js

### Save PM2 Configuration
pm2 save

### Setup PM2 to Auto-start on Boot
pm2 startup

### Follow the instructions provided by the above command, then:
pm2 save

### Check Application Status
pm2 status

### Health Check Endpoint
http://localhost:3000/api/health

### System Requirements:
- Minimum: 1GB RAM, 10GB Disk
- Recommended: 2GB RAM, 20GB Disk
- Node.js: v16 or higher
- Database: SQLite (included)

## 📋 POST-INSTALLATION CHECKLIST

✅ Update default admin password
✅ Configure environment variables
✅ Setup firewall rules
✅ Configure domain name (optional)
✅ Setup SSL certificate (optional)
✅ Configure backup schedule
✅ Add monitoring nodes
✅ Test alerts and notifications
✅ Verify data export functionality
✅ Check audit logs are working

## 🎉 CONGRATULATIONS!

Your VPS Monitor Pro+ is now installed and running!

Next Steps:
1. Login and change admin password
2. Add your first monitoring node
3. Configure alert thresholds
4. Setup email/Slack notifications
5. Share status page with your team

For updates and documentation, visit:
https://github.com/jlpggamerz/status-page

Support: support@yourcompany.com
Documentation: https://docs.yourdomain.com
