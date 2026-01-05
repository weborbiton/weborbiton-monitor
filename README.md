# WebOrbiton Monitor
Self-hosted status monitoring built for shared hosting. No VPS. No databases. PHP & Cron Jobs only.

### Key Features
Everything you need to monitor your websites and services effectively.
- Cron-based uptime checks with clear response status and latency tracking.
- Runs on PHP + Cron Jobs only. No background services.
- All data stored locally in lightweight JSON file.
- Designed to work on standard shared hosting environments.
- Instant email notifications for downtime and recovery events.
- Fully transparent, auditable source code. Full control over your data and deployment.

![img](https://weborbiton.com/images/webdemo.svg)

## License
Free for all websites and commercial projects, as long as your revenue does not exceed $1,500 per month from SaaS products built on WebOrbiton. You can use our Solution freely even if your site has ads.
The only restriction applies to developers creating their own SaaS on WebOrbiton that exceeds $1,500 in monthly revenue.

## Installation and Configuration
1. Download the latest version from the repository and extract it to your local computer.
2. Edit the config.php file and fill in your site information. Open sites.php and add the websites you want to monitor.
3. Upload all project files with your completed configuration to your shared hosting account.
4. Access your hosting control panel and search for Cron Jobs.
5. Add a cron job that executes the check.php script at your desired interval.
6. Make sure the cron job runs correctly.
