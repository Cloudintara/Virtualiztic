# Virtualiztic
Opensource Indonesian Virtualization Platform by Cloudintara Teknologi Anak Bangsa.

Welcome to the Virtualiztic wiki!
Virtualiztic adalah solusi komplit virtualisasi skala enterprise karya anak bangsa yang mengintegrasikan hypervisor KVM dan linux containers (LXC), fungsi software defined storage and networking pada single platform. Menggunakan sentralisasi user interface dengan mudah dapat menjalankan VMs dan linux containers, me-manage resources software-defined storage dan networking, cluster, dan fungsi lainnya seperti backup/restore, live migration, storage replication, dan integrated firewall. Virtualiztic meng-enables anda untuk mem-virtualisasikan sistem operasi Linux and Windows. Virtualiztic dapat me-maximumkan flexibility pada data center. mencakup high-availability (HA) tanpa single point of failure (SPOF). 

Enterprise Virtualization
Virtualiztic menggunakan dua basis teknologi virtualisasi, full virtualization atau teknologi virtualisasi berbasis VM dengan KVM sebagai hypervisor-nya, dan teknologi virtualisasi berbasis linux container dengan LXC sebagai container engine. Virtualiztic mendukung fitur clone, snapshot, restore, migration, failover dengan beberapa kondisi seperti power redundacy fail, read-only file system dll.

Multiple Storage Protocol
Virtualiztic mendukung multiple storage protocol yaitu NFS (Network File System), iSCSI (Internet Small Computer System Interface), dan FCP (Fiber Channel Protocol) sebagai protocol komunikasi dengan eksternal storage server sebagai data store. Virtualiztic mendukung multipath sebagai metode mitigasi failover pada level block. Dilengkapi dengan dukungan fitur cluster, sehingga sentralisasi management dapat di-implementasikan, pada mode cluster Virtualiztic dapat menjalankan cluster file system OCFS2 sehingga block sharing pada suatu pool cluster dapat di-implementasikan.

Software Defined Network
Virtualiztic dilengkapi dengan virtual switch yang mendukung konfigurasi VLAN pada level VM atau container, terdapat internal firewall yang dapat digunakan untuk mengatur network policy untuk VM dan host.

Cluster Management
Didukung dengan fitur clustering dengan konsep sharing storage menggunakan IP based storage protocol (NFS, iSCSI) maupun FC based storage protocol (FCP)

Mitigation Method
Virtualiztic didukung dengan beberapa fitur metode mitigasi yaitu live clone, snapshot - restore dan failover dengan meng-implementasikan hot migration untuk meg-cover fungsi High Availibility (HA) pada instance VM dan container.

Migration - High Availibility (HA)
Virtualiztic dilengkapi dengan fitur migration maupun hot atau live migration, fungsi dimana VM instance ataupun container dapat berpindah secara live - no downtime - antar host dalam satu cluster yang sama, kondisi failover dapat diinisialisasikan dengan beberapa kondisi seperti power redundacy fail, read-only file system dan lain-lain.

Multipath
Multipath adalah sebuah fitur standard pada teknologi virtualisasi untuk failover storage path pada level client, Virtualiztic telah mendukung fitur multipath yang sesuai dengan standard enterprise teknologi virtualisasi.

Cluster File System
Virtualiztic didukung dengan fitur cluster file system yang terintegrasi dengan cluster heartbeat untuk mengimplementasikan storage block share.visit us:
http://cloudintara.com
Call us for the installation ISO files.
bestimuh@cloudintara.com
