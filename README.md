# packer-examples
# Packer Examples

## Sample HTTPD AMI Creation using packer
```bash
 # httpd.json
 # export your AWS Keys
 $ export AWS_ACCESS_KEY_ID=**********
 $ export AWS_SECRET_ACCESS_KEY=************
 # Build AMI from nginx.json
 $ packer build nginx.json
```