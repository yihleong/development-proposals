https://etherpad.openstack.org/p/BOS-forum-101: 32: * You can use ##<tag> to highlight anything that needs to be shared with a team not present in the session (e.g. ##uservoice, ##ironic) and a group of people will share it in a mailing list summary after the event

https://etherpad.openstack.org/p/BOS-forum-ironic-feedback: 43: * - Port selection on multi physical switches. ##ironic ##painpoint

https://etherpad.openstack.org/p/BOS-forum-ironic-feedback: 51: * no concept of locality ##ironic ##painpoint

https://etherpad.openstack.org/p/BOS-forum-ironic-feedback: 52: * I would like to see this happen for per rack (leaf) etc conductors ##ironic ##painpoint

https://etherpad.openstack.org/p/BOS-forum-ironic-feedback: 55: *  https://specs.openstack.org/openstack/ironic-specs/priorities/pike-priorities.html#deploy-steps ##ironic ##painpoint

https://etherpad.openstack.org/p/BOS-forum-ironic-feedback: 71: * Sync power state against 50,000 nodes takes a while. I'm all the way back on Juno though, so there are probably some changes that've happened that i've missed. ##ironic ##painpoint

https://etherpad.openstack.org/p/BOS-forum-ironic-feedback: 73: * Running DHCP/HTTP/etc for instance provisioning out of the Ironic Conductor machines provides some large security holes. This means that datacenter nodes have logical access to one of the most crucial pieces of the OpenStack control plane. We've moved DHCP, TFTP, HTTP for provisioning to another set of nodes. However the conductor expects to write this to local disk. A driver based interface with an API to write these files remotely is necessary. ##ironic ##painpoint

https://etherpad.openstack.org/p/BOS-forum-ironic-feedback: 74: * Need a reference architecture and best practises on how to deploy Ironic in 100/200/1000/5000 nodes ##ironic ##painpoint

