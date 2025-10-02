# Task 7 - Monitor System Resources Using Netdata

## Objective
Install Netdata and visualize system and app performance metrics.

## Tools
- Netdata (open-source monitoring tool)
- Docker

## Steps to Run
1. Pull and run Netdata using Docker:
   ```bash
   docker run -d --name=netdata -p 19999:19999 netdata/netdata
   ```
2. Open your browser and access the dashboard at:
   ```
   http://localhost:19999
   ```
3. Explore system metrics such as CPU, memory, disk, and Docker containers.
4. Check alerts, logs, and chart panels for more insights.
   ```bash
   cat /var/log/netdata/error.log
   ```

## Deliverables
- Screenshot of the dashboard showing live monitoring metrics.

## Outcome
Understood lightweight real-time monitoring of system and app performance using Netdata.

## Interview Prep Questions
- What does Netdata monitor?
- How do you view real-time metrics?
- How is Netdata different from Prometheus?
- What is a collector?
- What are some performance KPIs to watch?
- How to deploy Netdata on a VM?
- How does Netdata alerting work?
- What is a dashboard in this context?
