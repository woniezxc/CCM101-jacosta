# Mission Reflection

1. **Checking host resources when containers run perfectly:** Even if a containerized application appears healthy, checking the underlying host server's resources is essential because containers share the host's kernel and physical hardware. If the host runs out of disk space or memory at the system level, all running containers will destabilize or crash regardless of their internal status.

2. **Solving login issues using `docker logs`:** When a user reports login failures, the `docker logs` command allows an engineer to inspect real-time server-side events, error traces, and HTTP request codes. This reveals whether requests are reaching the application container at all, or if internal database connection failures and script errors are causing the authentication breakdown.

3. **Difference between logs and metrics:** Monitoring logs (Checkpoint 4) involves reading discrete historical event entries and text records of specific actions or errors[cite: 3]. Monitoring metrics (Checkpoint 5) tracks continuous, aggregate numerical time-series data such as real-time CPU percentages, memory consumption rates, and network bandwidth usage[cite: 3].

4. **Enterprise monitoring of thousands of containers:** Large enterprise companies manage thousands of containers simultaneously by deploying centralized observability stacks like Prometheus to automatically scrape metric data and Grafana to visualize telemetry across clusters on unified dashboards[cite: 4].

5. **Growth in troubleshooting Linux environments:** Hands-on practice with CLI tools like `top`, `free`, `df`, and Docker diagnostic commands has significantly improved my confidence in isolating performance bottlenecks and verifying system health systematically.
