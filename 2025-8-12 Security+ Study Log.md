---
tags:
  - Domain3
---
# Security+ Study Log

**Date:** August 12, 2025
**Section/Module:** Cyber Resilience and Redundancy
**Duration:** N/A
**Course Progress:** Objective 3.4
**Domain:** 3 - Security Architecture

-----

## 📚 Today's Material Covered

- [x] High Availability Concepts
- [x] Load Balancing vs Clustering
- [x] Redundancy Implementation
- [x] Multi-Cloud Systems
- [x] Data Redundancy and RAID Arrays
- [x] RAID Configuration (Practical Demo)
- [x] Capacity Planning
- [x] Power Systems for Data Centers
- [x] Data Backup Strategies
- [x] Business Continuity Planning
- [x] Redundant Site Considerations
- [x] Resilience Testing Methods

| Term                                                 | Definition                                                                                                    |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Cyber Resilience**                                 | Entity's ability to continuously deliver intended outcome despite adverse cyber events                        |
| **Redundancy**                                       | Having additional systems, equipment, or processes to ensure continued functionality if primary ones fail     |
| **High Availability**                                | Ability of service to be continuously available by minimizing downtime to lowest amount possible              |
| **Uptime**                                           | Number of minutes/hours system remains online over given period, expressed as percentage                      |
| **Five Nines Availability**                          | 99.999% uptime, maximum ~5 minutes downtime per year                                                          |
| **Six Nines Availability**                           | 99.9999% uptime, maximum ~31 seconds downtime per year                                                        |
| **Load Balancing**                                   | Process of distributing workloads across multiple computing resources to optimize use and prevent overloading |
| **Clustering**                                       | Use of multiple computers/storage devices/network connections working together as single system               |
| **RAID (Redundant Array of Independent Disks)**      | Combining multiple physical storage devices into single logical storage device                                |
| **RAID 0**                                           | Data striping across multiple disks for increased performance, no redundancy                                  |
| **RAID 1**                                           | Data mirroring identically onto two drives for redundancy                                                     |
| **RAID 5**                                           | Striping with parity across minimum three drives, can lose one drive                                          |
| **RAID 6**                                           | Striping with double parity across minimum four drives, can lose two drives                                   |
| **RAID 10 (RAID 1+0)**                               | Striped array of mirrored arrays combining RAID 1 and RAID 0 benefits                                         |
| **Failure-Resistant**                                | Systems designed to withstand hardware malfunctions without data loss                                         |
| **Fault-Tolerant**                                   | Systems maintaining operations during hardware failure through mirroring or parity                            |
| **Disaster-Tolerant**                                | Systems protecting against catastrophic events with independent zones                                         |
| **Capacity Planning**                                | Strategic planning ensuring organization equipped to meet future demands cost-effectively                     |
| **Multi-Cloud**                                      | Distributing data/applications/services across multiple cloud environments                                    |
| **Power Surge**                                      | Small unexpected increase in voltage (120V to 125-130V)                                                       |
| **Power Spike**                                      | Short transient voltage caused by short circuit, lightning, or power outage                                   |
| **Power Sag**                                        | Small unexpected decrease in voltage for short period                                                         |
| **Undervoltage Event (Brownout)**                    | Voltage reduced to lower levels for longer period                                                             |
| **Power Loss Event (Blackout)**                      | Total loss of power for given period                                                                          |
| **Line Conditioner**                                 | Device overcoming minor power fluctuations, provides clean power                                              |
| **UPS (Uninterruptible Power Supply)**               | Device providing emergency power and line conditioning during power failure                                   |
| **Generator**                                        | Machine converting mechanical energy to electrical energy through electromagnetic induction                   |
| **Power Distribution Center (PDC)**                  | Centralized hub receiving and distributing power throughout data center                                       |
| **Hot Site**                                         | Fully operational backup facility ready for immediate use                                                     |
| **Cold Site**                                        | Basic backup facility requiring equipment installation and configuration                                      |
| **Warm Site**                                        | Partially equipped backup facility with some infrastructure in place                                          |
| **Geographic Dispersion**                            | Spreading resources across different physical locations                                                       |
| **Tabletop Exercise**                                | Discussion-based simulation of emergency scenarios                                                            |
| **Failover**                                         | Switching to backup system when primary system fails                                                          |
| **Business Continuity and Disaster Recovery (BCDR)** | Plan ensuring smooth operations during unforeseen events                                                      |

### Important Points

**High Availability Architecture:**
- **Load Balancing**: Distributes requests using complex algorithms, prevents server overloading, handles traffic spikes
- **Clustering**: Provides redundancy for hardware failures, maintains application availability, eliminates single points of failure
- **Combined Approach**: Load balancing manages normal traffic, clustering ensures service continuity during failures
- **Performance vs Reliability**: Balance between handling excess traffic and maintaining service during component failures

**Redundancy Implementation:**
- **Power Supplies**: Dual power supplies in servers, UPS systems, backup generators, multiple power grid connections
- **Network Connections**: Multiple cabled connections, cable + wireless backup, prevents connectivity single points of failure
- **Servers and Services**: Load balanced or clustered architecture, seamless workload shifting, backup instances ready
- **Service Providers**: Multiple ISPs, credit card processors, domain controllers, provider diversity for continuity
- **Cost Considerations**: Hardware redundancy expensive, evaluate software/cloud alternatives, strategic redundancy placement

**RAID Classifications:**
- **RAID 0 (Striping)**: Performance focus, no fault tolerance, minimum 2 disks, data split across drives
- **RAID 1 (Mirroring)**: Redundancy focus, complete data copy, minimum 2 disks, fastest recovery time
- **RAID 5 (Striping with Parity)**: Balance of performance and redundancy, minimum 3 disks, can lose 1 drive
- **RAID 6 (Striping with Double Parity)**: Enhanced redundancy, minimum 4 disks, can lose 2 drives
- **RAID 10 (Striped Mirrors)**: High performance and redundancy, minimum 4 disks, can lose 1 drive per mirror set

**RAID Resilience Levels:**
- **Failure-Resistant**: Mirrored systems (RAID 1, RAID 10) withstanding hardware malfunctions
- **Fault-Tolerant**: Systems continuing operation during failure (RAID 1, 5, 6, 10) through rebuilding capability
- **Disaster-Tolerant**: Independent zones with full data access (RAID 1, RAID 10) for catastrophic protection
- **Hot Swap Capability**: Replace failed drives without downtime, automatic rebuild processes

**Capacity Planning Framework:**
- **People**: Workforce analysis, skill assessment, hiring/training/downsizing planning, seasonal staffing strategies
- **Technology**: Current resource utilization, future demand projection, cloud scaling capabilities, platform assessment
- **Infrastructure**: Physical space planning, power/cooling requirements, data center constraints, equipment installation limits
- **Processes**: Workflow optimization, automation implementation, bottleneck elimination, scalability design

**Power System Architecture:**
- **Line Conditioners**: Handle surges, sags, undervoltage events, provide clean stable power, protect against degradation
- **UPS Systems**: 15-60 minute battery backup, line conditioning, prevent data loss during short outages
- **Generators**: Long-term power during extended outages, portable/permanent/battery types, fuel considerations
- **Power Distribution**: Centralized distribution hubs, circuit protection, load balancing, seamless backup integration

**Generator Types:**
- **Portable Gas Engine**: Least expensive, limited power, high noise/maintenance, manual startup, extension cord connection
- **Permanently Installed**: Diesel/propane/natural gas, whole building power, automatic startup, hours/days/weeks operation
- **Battery Inverter**: Quiet operation, low maintenance, limited wattage/duration, bridging solution until main backup online

**Multi-Cloud Strategy:**
- **Risk Mitigation**: Eliminates single cloud provider failure point, rapid workload transition capabilities
- **Cost Optimization**: Different pricing structures comparison, primary/secondary provider cost strategies
- **Vendor Lock-in Avoidance**: Multiple options for negotiations, migration flexibility during outages
- **Management Complexity**: Unified data management, consistent policy enforcement, security/compliance across platforms

**Data Center Power Redundancy:**
- **Rack-Level**: UPS units per server rack, 10-15 minute battery backup, individual rack protection
- **Facility-Level**: Power distribution units, load balancing, line conditioning, multiple power sources
- **Backup Integration**: Generator startup time 30-60 seconds, automatic switchover, seamless power transition
- **Layered Protection**: Multiple redundancy levels, surge/spike/sag/loss protection, comprehensive power architecture

**Practical RAID Configuration:**
- **RAID 0 Setup**: Two 800GB drives creating 1.57TB logical drive, performance for video editing
- **RAID 1 Setup**: Two drives mirrored, single drive capacity, redundancy for finished work storage
- **Dynamic Disk Management**: Windows disk management tool, drive letter assignment, formatting options
- **Use Case Strategy**: Scratch drive for performance, redundant drive for critical data storage

**Capacity Planning Examples:**
- **Retail Staffing**: Seasonal hiring (October), holiday demand surge (November-December), post-holiday downsizing (January)
- **E-commerce Scaling**: Traffic capacity planning, cloud resource scaling, promotional period preparation
- **Healthcare Telemedicine**: Staff training, technology investment, infrastructure modification, process development
- **Call Center Expansion**: 500 user account creation, manual vs automated workflow, bottleneck elimination

**Power Condition Protection:**
- **Surge Protection**: Voltage increase above normal (120V to 125-130V), surge protector/line conditioner protection
- **Spike Mitigation**: Transient voltage from lightning/short circuits, surge protector essential for protection
- **Sag Compensation**: Voltage decrease (120V to 115-117V), line conditioner brings voltage back to standard
- **Undervoltage Handling**: Significant voltage drop (70-80V), system shutdown protection, line conditioner restoration
- **Power Loss Recovery**: Complete power failure, UPS battery backup, generator automatic startup, spike protection on restoration

## 🏷️ Domain Tags

**#Domain3** - Security Architecture
- Importance of resilience and recovery in security architecture
- High availability through load balancing and clustering
- Redundancy for power, connections, servers, services, providers
- Multi-cloud system benefits and implementation
- Data redundancy through RAID configurations
- Capacity planning for people, technology, infrastructure, processes
- Power system design for data center continuity
- Backup strategies and business continuity planning
- Site redundancy and geographic dispersion
- Resilience testing methodologies