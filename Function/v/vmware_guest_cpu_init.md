# Function: <code>vmware_guest_cpu_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmware_guest_cpu_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579269152,
      "name": "vmware_guest_cpu_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:268",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmware_guest_cpu_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579276768,
      "name": "vmware_guest_cpu_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:269",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vmware_guest_cpu_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579279472,
      "name": "vmware_guest_cpu_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:270",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void vmware_guest_cpu_init()
```

```json
{
  "name": "vmware_guest_cpu_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmware_guest_cpu_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:270",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321808,
      "name": "vmware_guest_cpu_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
    },
    {
      "addr": 18446744071592070873,
      "name": "vmware_guest_cpu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void vmware_guest_cpu_init()
```

```json
{
  "name": "vmware_guest_cpu_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmware_guest_cpu_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:270",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381328,
      "name": "vmware_guest_cpu_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071593837166,
      "name": "vmware_guest_cpu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void vmware_guest_cpu_init()
```

```json
{
  "name": "vmware_guest_cpu_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmware_guest_cpu_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:270",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579457904,
      "name": "vmware_guest_cpu_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071595964640,
      "name": "vmware_guest_cpu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void vmware_guest_cpu_init()
```

```json
{
  "name": "vmware_guest_cpu_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmware_guest_cpu_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:270",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470256,
      "name": "vmware_guest_cpu_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071596482294,
      "name": "vmware_guest_cpu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void vmware_guest_cpu_init()
```

```json
{
  "name": "vmware_guest_cpu_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vmware_guest_cpu_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/vmware.c:270",
      "file": "arch/x86/kernel/cpu/vmware.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/vmware.c:vmware_cpu_online",
        "arch/x86/kernel/cpu/vmware.c:vmware_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500368,
      "name": "vmware_guest_cpu_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
    },
    {
      "addr": 18446744071597378394,
      "name": "vmware_guest_cpu_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void vmware_guest_cpu_init()
```
</details>
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
