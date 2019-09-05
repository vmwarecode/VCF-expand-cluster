Expand a cluster:

The following data is required

	->ID of the cluster

For each host

	->ID of the host (UUID)

	->List of VDS names to associate with host

	->ID of the vmNic, host is associated to

License key of ESXi

The cluster in a domain to which hosts are to be added must exist.

There must be a host available in the VMware Cloud Foundation inventory.

The hosts to be added must have been commissioned.

Ensure that the host you want to add is in an active state.

You must have a valid ESXi license specified with adequate sockets available for the host to be added.

Ensure that the host to be added to the cluster matches the configuration of the hosts already in the cluster. This ensures a balanced configuration of the cluster.


The expand_cluster_spec.json is sample input file.



Usage:
    python expand_cluster.py <hostname> <username> <password> <cluster_id>

expand_cluster_spec.json is the sample input file.