# Initial Setup

## Initial Setup

This section provides the key prerequisites and installation steps to assist you get started with the A10 Control platform hassle-free.

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

Follow the steps to install the A10 Control platform and get started.

1. Access the Installer
2. Log in to the [A10 Networks Support Portal](https://support.a10networks.com/).
3. Enter the credentials.
4. Navigate to the **Software Downloads and Documentation** page. \
   &#xNAN;_&#x53;uggested Screenshot: Software Downloads and Documentation page_
5. Under the **Software** tab, locate the **A10 Control** section.
6. Download the A10 Control ISO, OVA, or QCOW2 installer file as required.
7. Run the Installer file and follow the on-screen instructions.&#x20;
8. Choose the default settings unless the custom configuration deployment is required.
9. Launch the A10 Control application and access the dashboard.
