# Packer examples

**These examples require:**

- Packer 
- QEMU/Kvm 

**Crashcourse**

The building process takes some time : expect around 10 minutes for the SSH server to be available

```

$ packer build  -on-error=ask -force -timestamp-ui debian11.pkr.hcl


```




Based on the [goffinet/packer-kvm](https://github.com/goffinet/packer-kvm) project
