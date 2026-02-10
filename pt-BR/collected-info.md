# Collected Personal Information List

**Last Updated: January 5, 2026**

In accordance with GDPR Article 13, CCPA, and other relevant laws and regulations, we explain the personal information collected by this application:

> **IMPORTANT**: All information below is stored only on your device locally and will not be uploaded to any server.

## 1. Device Information (Read locally for display)

### 1.1 Basic Device Information
- **Information Type**: Device name, device model, system version
- **Collection Purpose**: Display on "Device Info" page
- **Legal Basis**: Contract performance (providing services you request)
- **Collection Method**: Read via system API
- **API Used**: UIDevice.current
- **Retention Period**: Duration of app use

### 1.2 Device Identifier
- **Information Type**: Model identifier (e.g., iPhone17,1)
- **Collection Purpose**: Identify device model for display
- **Legal Basis**: Contract performance
- **Collection Method**: Via utsname system call
- **Note**: Not advertising identifier (IDFA), not device unique identifier (IDFV)

### 1.3 Device Status Information
- **Information Type**: Battery level, battery status, disk space, memory usage
- **Collection Purpose**: Display on "Device Info" page
- **Legal Basis**: Contract performance
- **Collection Method**: Read via system API

## 2. Network Information (Read locally for diagnostics)

### 2.1 IP Address
- **Information Type**: Local IPv4 address, local IPv6 address
- **Collection Purpose**: Network diagnostics, device info display
- **Legal Basis**: Contract performance
- **Collection Method**: Via getifaddrs system call

### 2.2 Network Status
- **Information Type**: Network type (WiFi/Cellular/No network)
- **Collection Purpose**: Determine network environment, network diagnostics
- **Legal Basis**: Contract performance
- **Collection Method**: Via NWPathMonitor listener

### 2.3 Cellular Network Type
- **Information Type**: 2G/3G/4G/5G
- **Collection Purpose**: Display detailed network type
- **Legal Basis**: Contract performance
- **Collection Method**: Via CoreTelephony framework

## 3. History Records (Stored locally)

### 3.1 Probe Target History
- **Information Type**: Ping/DNS/TCP/UDP/Trace/HTTP target addresses
- **Collection Purpose**: Convenient for users to quickly select common targets
- **Legal Basis**: Legitimate interests (improving user experience)
- **Storage Method**: UserDefaults local storage
- **Storage Limit**: Up to 10 records per category
- **Retention Period**: Until user clears or uninstalls app

### 3.2 IP Query History
- **Information Type**: Queried IP addresses
- **Collection Purpose**: Convenient for users to view query history
- **Legal Basis**: Legitimate interests
- **Storage Method**: UserDefaults local storage

### 3.3 Connection Test/Quick Diagnosis History
- **Information Type**: Test target addresses
- **Collection Purpose**: Convenient for users to repeat tests
- **Legal Basis**: Legitimate interests
- **Storage Method**: UserDefaults local storage

## 4. User Identifier (Generated locally)

### 4.1 Guest ID
- **Information Type**: Randomly generated string
- **Collection Purpose**: Local user identification
- **Legal Basis**: Contract performance
- **Storage Method**: UserDefaults local storage
- **Note**: Completely randomly generated, not associated with any personal identity information

## 5. Network Requests (Required for functionality) - International Data Transfers

### 5.1 NetEase IP Query Service
- **Service URL**: mail.163.com
- **Provider**: NetEase, Inc. (China)
- **Data Sent**: Network request (automatically carries public IP)
- **Data Received**: Public IP address, country, province, city, ISP
- **Purpose**: Obtain current device's public IP and geolocation information
- **Legal Basis**: Contract performance

### 5.2 Bilibili IP Query Service
- **Service URL**: api.live.bilibili.com
- **Provider**: Bilibili Inc. (China)
- **Data Sent**: IP address to query
- **Data Received**: Country, province, city, ISP, coordinates
- **Purpose**: Query geographic location of specified IP
- **Legal Basis**: Contract performance

### 5.3 ipinfo.io ASN Query Service
- **Service URL**: api.ipinfo.io
- **Provider**: IPinfo Inc. (USA)
- **Data Sent**: IP address to query
- **Data Received**: AS number, AS name, country
- **Purpose**: Query AS number (Autonomous System Number) of IP
- **Legal Basis**: Contract performance
- **International Transfer Note**: Data may be transferred to USA; service complies with GDPR

## 6. How to Clear Information

- **History**: Manually clear on each feature page
- **All Data**: Uninstall the app to delete all local data
- **Exercise Data Rights**: Contact zjccc5889@gmail.com
