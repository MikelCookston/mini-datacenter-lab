# Mini Data Center Infrastructure Lab

## Overview

This project simulates a small data center environment using virtual machines.  
The goal was to build and monitor a multi-server infrastructure similar to what is used in cloud and enterprise environments.

## Technologies Used

- VMware Workstation Pro
- Ubuntu Server
- NGINX
- MySQL
- Prometheus
- Grafana
- Node Exporter

## Infrastructure Architecture

The environment consists of three servers:

server01 – Web Server (NGINX)  
server02 – Database Server (MySQL)  
server03 – Monitoring Server (Prometheus + Grafana)

All servers run Node Exporter for monitoring.

## Network

server01 – 192.168.159.130  
server02 – 192.168.159.132  
server03 – 192.168.159.131  

## Monitoring

Prometheus collects metrics from all servers.  
Grafana visualizes system metrics including:

- CPU usage
- memory usage
- disk I/O
- network traffic

## Screenshots

See the screenshots folder for:

- VM infrastructure
- NGINX web server
- Prometheus monitoring targets
- Grafana dashboards

## Skills Demonstrated

- Linux server deployment
- Virtualization using VMware
- Infrastructure monitoring with Prometheus and Grafana
- Network configuration and troubleshooting
- Multi-server system architecture
