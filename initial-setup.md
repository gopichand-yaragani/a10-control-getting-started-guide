# Initial Setup

This section provides the key prerequisites and installation steps to assist you get started with the A10 Control platform effectively.

### Prerequisites

**Deployment Mode** \
A10 Control supports installation on large scale and small scale environments.

* A10 Control Lite (small-scale)
* A10 Control Standard (large-scale)

**Hypervisor Compatibility**

* VMware ESXi 8.0 U2 or higher
* KVM (Red Hat 9.3 or higher)
* vCenter or vSphere Host client access required&#x20;

**Time Synchronization**

* Enable Network Time Protocol (NTP) on the hypervisor
* Ensure accurate and synchronized system time&#x20;

**System Sizing**

* CPU, RAM, and disk capacity based on deployment scale
* Only IPv4 supported in version 1.0.0&#x20;

**Network Configuration**

* Assign IP address, subnet prefix, gateway, and DNS for each interface
* Configure floating IP for multi-node or multi-interface setups

### Installation Steps

Follow the steps to install the A10 Control platform:

1. Log in to the [A10 Networks Support Portal](https://support.a10networks.com/).
2. Enter the credentials.
3. Navigate to the **Software Downloads and Documentation** page. \
   &#xNAN;_&#x53;uggested Screenshot: Software Downloads and Documentation page_
4. Under the **Software** tab, locate the **A10 Control** section.
5. Download the required A10 Control ISO, OVA, or QCOW2 installer file.
6. Run the Installer file and follow the on-screen instructions.
7. Choose the default settings unless the custom configuration deployment is required.
8. Launch the A10 Control application and access the dashboard.
