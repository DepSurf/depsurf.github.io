# Function: <code>native_smp_prepare_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595030284,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1277",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595030284,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 747
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595195914,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1289",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595195914,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 720
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595438682,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1291",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595438682,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 754
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596359390,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1298",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596359390,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 780
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602677361,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1199",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602677361,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 605
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602848823,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1252",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602848823,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 608
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604645628,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1253",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604645628,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 624
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604743359,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1315",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604743359,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 638
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604756754,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1310",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604756754,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 646
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609103137,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1323",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609103137,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 538
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612168053,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1317",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612168053,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 540
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614308243,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1318",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614308243,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 662
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615235863,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1320",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615235863,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 801
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617012204,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1404",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617012204,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627643712,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1402",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627643712,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619400336,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1297",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619400336,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621695360,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1210",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621695360,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604683038,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1310",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604683038,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 641
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604650592,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1310",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604650592,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 641
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604760622,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1310",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604760622,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 641
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```

```json
{
  "name": "native_smp_prepare_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604760853,
      "name": "native_smp_prepare_cpus",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1310",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus",
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_cpus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604760853,
      "name": "native_smp_prepare_cpus",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 667
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void native_smp_prepare_cpus(unsigned int max_cpus)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
