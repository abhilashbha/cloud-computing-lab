# EC2 Connection Notes

## Example SSH Command

```bash
ssh -i "YOUR_KEY.pem" USERNAME@YOUR_PUBLIC_DNS
```

Replace the placeholders with values from your own AWS instance. Do not commit the private key.

## Basic Verification

```bash
whoami
uname -a
pwd
ls
```
