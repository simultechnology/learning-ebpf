

```bash
multipass list

multipass launch --cpus 2 --disk 40G --mem 8G --name my-ebpf-practice 22.04
multipass mount . my-ebpf-practice:/mnt/share

multipass info my-ebpf-practice

# enter 
multipass shell my-ebpf-practice
```


``` 
sudo apt-get -y update
sudo apt-get install -y bpfcc-tools python3-bpfcc

```