**AWS Global Infrastructure:**

1. **Regions:**
    - A region is a physical location in the world (e.g., Northern Virginia, Ohio).
    - AWS groups regions into larger geographical areas for management.
    - Choose a region closest to your users for improved performance.
    - Regions are resource and service-specific.
    - Regions are fully independent and isolated from each other.
2. **Availability Zones (AZs):**
    - Availability Zones are one or more physically separated data centers.
    - AZs are isolated, using different power grids.
    - AZs are connected within a single region through low-latency links.
    - They provide fault tolerance and high availability.
    - Distributing applications across multiple AZs ensures continuity in case of AZ failure.
    - Exact numbers of data centers within an AZ are not officially disclosed.
3. **Edge Locations:**
    - Edge locations are mini data centers used for caching content.
    - They improve content delivery speed and reduce latency.
    - Edge locations are part of Amazon CloudFront, AWS's content delivery network.
    - They do not launch EC2 instances or run primary infrastructure.

**Terminology:**

- **Latency:** The time it takes for a website to load. Lower latency means faster website loading.
- **High Availability:** Systems that operate continuously without failure and provide dependable services.

**Key Takeaways:**

- Regions are physical locations that contain availability zones.
- Availability Zones are collections of one or more data centers, isolated and fault-tolerant.
- Deploy resources in regions closest to your users for improved performance.
- Edge locations cache content to reduce latency, and they are part of Amazon CloudFront.