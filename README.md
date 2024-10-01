# Wireshark Network Traffic Analysis

## Project Overview
In this project I focused on capturing and analyzing network traffic using Wireshark to better understand network protocols like HTTP and DNS.

## Tools Used:
- Wireshark
- Ubuntu (Virtual Machine)
- Firefox Browser

## Steps Performed:

### 1. Capturing Traffic:
- I used Wireshark to capture network traffic on the `enp0s3` interface of my Ubuntu VM while browsing websites like Google and Yahoo.

### 2. Filtering and Analyzing HTTP Traffic:
- I applied a filter (`http`) to focus on HTTP traffic and inspected key HTTP requests and responses.
- **GET Request Example**: Captured a GET request to `/canonical.html` from `detectportal.firefox.com`, showing how my browser communicates with the server.
- **HTTP Response Example**: The server responded with `HTTP/1.1 200 OK`, successfully delivering the requested resource.

### 3. DNS Traffic:
- I applied a DNS filter (`dns`) to observe the DNS queries and responses as my system resolved domain names like `google.com`.
- **DNS Query**: My computer (`10.0.2.15`) sent a DNS query to my router (`192.168.1.1`) asking for the IP address of `google.com`.
- **DNS Response**: The router responded with the resolved IP address.

## Reflection:
This project gave me hands-on experience with network traffic analysis using Wireshark. I learned how to capture and analyze web traffic, as well as how to identify normal communication patterns. Understanding these basics is essential for detecting anomalies in network security.


