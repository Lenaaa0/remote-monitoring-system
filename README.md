# INTRODUCE
## Remote Screen Monitoring System
### Problem Description:
The remote screen monitoring system uses a client/server model to automatically capture screen images from the monitored host and send them to the monitoring station. The images are displayed on the monitoring station to achieve remote monitoring purposes. It is widely used in data center management, online examinations, and other scenarios.
### Basic Functions:
#### Client Side (Monitored Host):
- Client registration, login, and logout: Registration information includes at least username, password, host IP address, and host MAC address.
- Screen capture: Screenshots are taken at set intervals.
- Sending screen images: Image files are compressed and sent to the monitoring host.
- Client system minimization to tray.
- Parameter configuration: Monitoring frequency, monitoring host IP address, and port number.
#### Server Side (Monitoring Host):
- Registration: Communicate with the client to complete registration (including necessary checks).
- Receiving screen images: Continuously receive and decompress screen images from the client.
- Screen image display: Display the screen images on the monitoring host’s screen.
- User tree maintenance: Real-time maintenance of the client’s user tree, highlighting online users, and greying out those who exit.
- Storage of historical screen images based on MAC address, username, IP address, etc., and displaying them in chronological order.
- Command issuance: Change monitoring frequency.
#### Advanced Features:
- Mutual authentication and encrypted transmission: Perform mutual authentication before transmission.
### ps
大二下小学期，选题：远程屏幕监控系统

# USAGE
客户端先注册再登陆，服务器端点击用户查看监控屏幕

