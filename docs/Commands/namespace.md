# Useful Namespace Commands

## List current namespaces and PID's

    lsns -l
    
## Enter the network interface from the namespace

    nsenter -t <pid> -n
