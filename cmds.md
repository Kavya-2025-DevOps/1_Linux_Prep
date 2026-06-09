top – Monitor real-time CPU and memory usage
htop – Interactive system monitoring
df -h – Check disk space usage
du -sh * – Find large files/directories
free -m – Check memory usage
ps -ef – List running processes
netstat -tulnp – Check listening ports
ss -tulnp – View active network connections
lsof -i :80 – Check process using a port
systemctl status nginx – Check service status
systemctl restart nginx – Restart service
journalctl -xe – View system logs
tail -f /var/log/messages – Monitor logs in real time
grep "error" logfile – Search logs for errors
find / -name file.txt – Search files in Linux
chmod 755 file.sh – Change file permissions
chown user:user file.txt – Change file ownership
crontab -e – Schedule cron jobs
scp file.txt user@server:/tmp – Copy files remotely
ssh user@server – Connect remote Linux server
vmstat 1 – Monitor CPU, memory, and processes
iostat -x 1 – Check disk I/O performance
sar -u 1 5 – Monitor CPU utilization history
uptime – Check server uptime and load average
hostnamectl – Show system hostname details
ip addr show – Display IP addresses
ping google.com – Test network connectivity
traceroute google.com – Trace network path
curl -I https://example.com – Check website response headers
wget <url> – Download files from internet
