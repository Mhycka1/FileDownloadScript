# FileDownloadScript

These three scripts work together within an lxc container to rig download commands to make a copy of the downloads retrived through the curl and wget commands. A container name is taken as input and if it's started then a new directory is created at /var/log/.downloads and all download copys are stored there within the container
