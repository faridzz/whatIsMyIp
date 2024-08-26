# `myip` - Find Your Public IP and Geolocation

`myip` is a simple and effective Bash script that helps you quickly find your public IP address and associated geolocation details. With just one command, you can retrieve your IP, city, region, country, and other relevant information.

## Features

- **Quick IP Lookup**: Instantly find your public IP address.
- **Geolocation Details**: Get detailed information about your location based on your IP.
- **Easy to Use**: Simple command-line interface.
- **Portable**: Set it up once and use it from anywhere on your Linux system.

## Installation

### 1. Clone the Repository or Download the Script

```bash
git clone https://github.com/your-username/myip.git
cd myip
```
Alternatively, you can directly download the script.

### 2. Make the Script Executable
Ensure that the script has the proper executable permissions:

```
chmod +x myip.sh
```
### 3. Move the Script to a Directory in Your PATH
To use the script from anywhere, move it to a directory like /usr/local/bin:

```bash
sudo mv myip.sh /usr/local/bin/myip
```
Now, you can run the script from any location on your system by simply typing:

```bash 
myip
```
Usage
After following the installation steps, you can run the myip command to get your public IP address and geolocation information:

```bash 
myip
```
Example Output:
```bash 
Your IP Address: 203.0.113.0
Geolocation Info:
{
  "ip": "203.0.113.0",
  "city": "Tehran",
  "region": "Tehran Province",
  "country": "IR",
  "loc": "35.6892,51.3890",
  "org": "AS12345 MyISP",
  "postal": "12345",
  "timezone": "Asia/Tehran"
}
```
### The output includes:

IP Address: Your public IP.
City: The city where your IP is located.
Region: The region or state associated with your IP.
Country: The country of your IP.
Location (Coordinates): Latitude and longitude.
Organization: The organization providing your IP (usually your ISP).
Postal Code: The postal code associated with your location.
Timezone: The timezone of your IP address.
Customization
If you wish to modify or extend the script (e.g., adding more details, changing the API used), you can easily do so by editing the myip script.

```bash 
nano /usr/local/bin/myip
```
Troubleshooting
Permission Issues: Ensure that the script has executable permissions (chmod +x myip).
Incorrect Output: Make sure you have internet access and the APIs used are reachable.
Path Issues: If the command myip is not recognized, ensure the script is in a directory listed in your PATH.
### Contributions
Feel free to fork this repository, submit pull requests, or open issues for any improvements or bug fixes.
