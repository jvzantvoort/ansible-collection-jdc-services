# Ansible Collection - jvzantvoort.services

This is for testing demo purposes only it uses molecule together
with GCE to run simple tests.

## Testing

create a file ``extensions/.env.yml``

```yaml
---
gcp_cred_kind: serviceaccount
gcp_cred_file: /home/USERNAME/service.json
gcp_region: europe-west4
gcp_zone: europe-west4-a
gcp_machine_type: e2-small
gcp_project: PROJECT
rocky8_name: rhel8
rocky8_image: projects/rocky-linux-cloud/global/images/rocky-linux-8-v20241009
rocky9_name: rhel9
rocky9_image: projects/rocky-linux-cloud/global/images/rocky-linux-9-v20241009
...
```
