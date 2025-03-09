# Function: <code>__bitmap_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583012656,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:358",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583012656,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583303504,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:360",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583303504,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583422544,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:360",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583422544,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583444688,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:360",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:store_xps_map",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583444688,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583624672,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:362",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583624672,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583840832,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:359",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583840832,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583924496,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:356",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583924496,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103888,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:356",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103888,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584226672,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:376",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584226672,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496100904,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:376",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496100904,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 820
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229426080,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:376",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229426080,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290346560,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:376",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290346560,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 784
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275167760,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:376",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275167760,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584195408,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:376",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584195408,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584130624,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:376",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584130624,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584179168,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:376",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584179168,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```

```json
{
  "name": "__bitmap_parse",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584283504,
      "name": "__bitmap_parse",
      "external": true,
      "loc": "lib/bitmap.c:376",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write",
        "kernel/workqueue.c:wq_unbound_cpumask_store",
        "kernel/workqueue.c:wq_cpumask_store",
        "kernel/padata.c:store_cpumask",
        "lib/bitmap.c:bitmap_parse_user",
        "net/core/net-sysfs.c:xps_rxqs_store",
        "net/core/net-sysfs.c:xps_cpus_store",
        "net/core/net-sysfs.c:store_rps_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584283504,
      "name": "__bitmap_parse",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 467
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int __bitmap_parse(const char * buf, unsigned int buflen, int is_user, long unsigned int * maskp, int nmaskbits)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
