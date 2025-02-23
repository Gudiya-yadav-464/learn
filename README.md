# learn
Learning Python, SQL, Linux.
 

linux prompts--

mkdir -  creates a directory
rm - to go a file
rm dir - r = remove drectory

pwd - check present working dir



## Prompt History

```bash

Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ mkdir
mkdir: missing operand
Try 'mkdir --help' for more information.
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ mk dir Linux things
bash: mk: command not found
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ mkdir Linux
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ mkdir linux
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ rm Linux
rm: cannot remove 'Linux': Is a directory
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ rm Linux -r
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ touch text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ cat README.md
# learn
Learning Python, SQL, Linux.
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ pwd
/workspaces/learn
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ touch linux/ReadME.md
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls -l
total 8
-rw-rw-rw-  1 codespace root        37 Feb 15 11:01 README.md
drwxrwxrwx+ 2 codespace codespace 4096 Feb 15 11:40 linux
-rw-rw-rw-  1 codespace codespace    0 Feb 15 11:35 text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ date
Sat Feb 15 11:45:00 UTC 2025
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ git add README.md 
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ git commit
[main 4967659] add basic linux prompts
 1 file changed, 11 insertions(+)
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 405 bytes | 405.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Gudiya-yadav-464/learn
   02804b2..4967659  main -> main
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls linux 
ReadME.md
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ touch linux/test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ pwd
/workspaces/learn
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls linux
ReadME.md  test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls /workspaces/learn/
README.md  linux  text
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls /workspaces/learn/linux
ReadME.md  test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls linux
ReadME.md  test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ ls linux -l
total 0
-rw-rw-rw- 1 codespace codespace 0 Feb 15 11:40 ReadME.md
-rw-rw-rw- 1 codespace codespace 0 Feb 15 12:00 test.sh
@Gudiya-yadav-464 ➜ /workspaces/learn (main) $ 

```


### CPU & Memory

```bash

$ lscpu

Architecture:                       x86_64
CPU op-mode(s):                     32-bit, 64-bit
Byte Order:                         Little Endian
Address sizes:                      48 bits physical, 48 bits virtual
CPU(s):                             2
On-line CPU(s) list:                0,1
Thread(s) per core:                 2
Core(s) per socket:                 1
Socket(s):                          1
NUMA node(s):                       1
Vendor ID:                          AuthenticAMD
CPU family:                         25
Model:                              1
Model name:                         AMD EPYC 7763 64-Core Processor
Stepping:                           1
CPU MHz:                            3242.026
BogoMIPS:                           4890.86
Virtualization:                     AMD-V
Hypervisor vendor:                  Microsoft
Virtualization type:                full
L1d cache:                          32 KiB
L1i cache:                          32 KiB
L2 cache:                           512 KiB
L3 cache:                           32 MiB
NUMA node0 CPU(s):                  0,1
Vulnerability Gather data sampling: Not affected
Vulnerability Itlb multihit:        Not affected
Vulnerability L1tf:                 Not affected
Vulnerability Mds:                  Not affected
Vulnerability Meltdown:             Not affected
Vulnerability Mmio stale data:      Not affected
Vulnerability Retbleed:             Not affected
Vulnerability Spec rstack overflow: Vulnerable: Safe RET, no microcode
Vulnerability Spec store bypass:    Vulnerable
Vulnerability Spectre v1:           Mitigation; usercopy/swapgs barriers and __user pointer sanitization
Vulnerability Spectre v2:           Mitigation; Retpolines; STIBP disabled; RSB filling; PBRSB-eIBRS Not affected; BHI Not affected
Vulnerability Srbds:                Not affected
Vulnerability Tsx async abort:      Not affected
Flags:                              fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdt
                                    scp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 mov
                                    be popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_s
                                    ingle vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsavee
                                    rptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq r
                                    dpid fsrm


```



### Memory


```
$ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.2Gi       172Mi        58Mi       6.4Gi       6.2Gi
Swap:            0B          0B          0B

```

### disk space

```

$ df -kh
Filesystem      Size  Used Avail Use% Mounted on
overlay          32G   18G   13G  59% /
tmpfs            64M     0   64M   0% /dev
shm              64M     0   64M   0% /dev/shm
/dev/root        29G   13G   17G  44% /vscode
/dev/sda1        44G   24G   19G  56% /tmp
/dev/loop4       32G   18G   13G  59% /workspaces

```


```


$ df -kh .
Filesystem      Size  Used Avail Use% Mounted on
/dev/loop4       32G   18G   13G  59% /workspaces

```











