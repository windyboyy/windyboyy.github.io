# Third-Party SDK List

**Last Updated: January 5, 2026**

This application integrates the following SDKs:

## 1. Apple System SDKs

### 1.1 Foundation
- **Provider**: Apple Inc.
- **Function**: Basic framework support, provides basic data types and collections
- **Information Collected**: None

### 1.2 SwiftUI
- **Provider**: Apple Inc.
- **Function**: User interface framework, builds app interface
- **Information Collected**: None

### 1.3 UIKit
- **Provider**: Apple Inc.
- **Function**: UI component support, obtains device information
- **Information Collected**: Device name, system version, battery status

### 1.4 Network
- **Provider**: Apple Inc.
- **Function**: Network communication support, TCP/UDP connections, network status monitoring
- **Information Collected**: Network connection status

### 1.5 CoreTelephony
- **Provider**: Apple Inc.
- **Function**: Obtains cellular network information
- **Information Collected**: Cellular network type (2G/3G/4G/5G)

### 1.6 NetworkExtension
- **Provider**: Apple Inc.
- **Function**: Network extension support (reserved for packet capture feature)
- **Information Collected**: None

### 1.7 Security
- **Provider**: Apple Inc.
- **Function**: Security framework support
- **Information Collected**: None

### 1.8 Darwin
- **Provider**: Apple Inc.
- **Function**: Low-level system calls, used for Ping, Traceroute, etc.
- **Information Collected**: None

### 1.9 dnssd
- **Provider**: Apple Inc.
- **Function**: DNS service discovery, used for DNS query feature
- **Information Collected**: None

## 2. Third-Party Commercial SDKs

This application currently does not integrate any third-party commercial SDKs, including but not limited to:
- No advertising SDKs
- No analytics SDKs
- No social sharing SDKs
- No push notification SDKs
- No payment SDKs

## 3. Third-Party Network Services

### 3.1 NetEase IP Query Service
- **Service URL**: mail.163.com
- **Provider**: NetEase, Inc.
- **Function**: Obtain current device's public IP address and geolocation
- **Data Sent**: Network request (automatically carries public IP)
- **Data Returned**: Public IP address, country, province, city, ISP

### 3.2 Bilibili IP Query Service
- **Service URL**: api.live.bilibili.com
- **Provider**: Bilibili Inc.
- **Function**: Query geographic location of specified IP
- **Data Sent**: IP address to query
- **Data Returned**: Country, province, city, ISP, coordinates

### 3.3 ipinfo.io ASN Query Service
- **Service URL**: api.ipinfo.io
- **Provider**: IPinfo Inc. (USA)
- **Function**: Query AS number (Autonomous System Number) of IP
- **Data Sent**: IP address to query
- **Data Returned**: AS number, AS name, country

## 4. Notes

1. This application only uses Apple official system SDKs to ensure safety and reliability.
2. If new third-party SDKs are integrated in the future, we will update this list and notify you promptly.
3. All SDK usage follows the principle of minimum necessity.
