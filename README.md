# Vagrant Chest
An easy-to-use Vagrant Box repository server that runs on your private (organisational) network.

Constituted by just a single binary file, deployment and maintenance of the repository server is quick and simple.

# NABC Breakdown
For those interested, the following constitutes an NABC-based breakdown of the motivation for building Vagrant Chest, inspired by the [NABC method](http://www.sri.com/engage/innovation-programs/five-disciplines-innovation) pioneered by Stanford Research Institute (SRI).

### Need
Vagrant is excellent for building reproducible _Virtualized Development Environments_ (VDEs) containing all the applications, compilers and libraries etc. needed for coding, building and testing software for specific software stacks. 

Using VDEs, well-designed development environments can thus easily be replicated and bootstrapped similarly across developer workstations and build servers, making it trivial and efficient to develop and build against any and all stacks in use within an organisation.

However, Vagrant lacks a smart way of discovering, uploading, maintaining and sharing Vagrant Boxes between stakeholders on private networks within an organisation.

### Approach
We'll develop a Vagrant Box repository server, called Vagrant Chest, that makes it easy to discover, upload, maintain and share Vagrant Boxes, such as VDEs, on private networks. 

We'll develop the repository server using the Go language to be able to build a single binary application that can easily be deployed across operating systems, making it dead-easy for Ops to get the thing up and running, and to keep it running with little ongoing maintenance.

### Benefit
Vagrant Chest will make Vagrant and the concept of VDEs more appealing and usable for organisations who (for privacy and/or performance reasons) prefer to host their VDEs in-house. Making such more appealing and usable could 

### Competition
- [Vagrant Atlas](https://atlas.hashicorp.com/): A cloud-based catalog/repository server
- [Vagrant Catalog](https://github.com/vube/vagrant-catalog): A PHP-based catalog/repository server
