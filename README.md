# Ansible Collection - jdc.services

This is for testing demo purposes only it uses molecule together
with GCE to run simple tests.

## Testing

* Install ``libvirt-python``.
* create a file ``extensions/.env.yml``

```yaml
---
pool: /var/lib/libvirt/images
network: default
memory: "2097152"
machine: pc-q35-rhel9.4.0
rocky8_name: rhel8
rocky8_image: /var/lib/libvirt/images/rocky8_ansible/rocky8.10-minimal-1.qcow2
rocky9_name: rhel9
rocky9_image: /var/lib/libvirt/images/rocky9_ansible/rocky9.04-minimal-1.qcow2
...
```

Note: you must be able to login through ansible
