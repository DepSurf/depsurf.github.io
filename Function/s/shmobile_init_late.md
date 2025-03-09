# Function: <code>shmobile_init_late</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate ❓</summary>

```c
void shmobile_init_late()
```

```json
{
  "name": "shmobile_init_late",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243349912,
      "name": "shmobile_init_late",
      "external": false,
      "loc": "arch/arm/mach-shmobile/common.h:34",
      "file": "arch/arm/mach-shmobile/setup-sh73a0.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243349972,
      "name": "shmobile_init_late",
      "external": false,
      "loc": "arch/arm/mach-shmobile/common.h:34",
      "file": "arch/arm/mach-shmobile/setup-r8a7740.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243350296,
      "name": "shmobile_init_late",
      "external": false,
      "loc": "arch/arm/mach-shmobile/common.h:34",
      "file": "arch/arm/mach-shmobile/setup-r8a7778.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243350424,
      "name": "shmobile_init_late",
      "external": false,
      "loc": "arch/arm/mach-shmobile/common.h:34",
      "file": "arch/arm/mach-shmobile/setup-r8a7779.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243350592,
      "name": "shmobile_init_late",
      "external": false,
      "loc": "arch/arm/mach-shmobile/common.h:34",
      "file": "arch/arm/mach-shmobile/setup-emev2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243350612,
      "name": "shmobile_init_late",
      "external": false,
      "loc": "arch/arm/mach-shmobile/common.h:34",
      "file": "arch/arm/mach-shmobile/setup-r7s72100.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243350632,
      "name": "shmobile_init_late",
      "external": false,
      "loc": "arch/arm/mach-shmobile/common.h:34",
      "file": "arch/arm/mach-shmobile/setup-r7s9210.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243351736,
      "name": "shmobile_init_late",
      "external": false,
      "loc": "arch/arm/mach-shmobile/common.h:34",
      "file": "arch/arm/mach-shmobile/setup-rcar-gen2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3243349912,
      "name": "shmobile_init_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3243349972,
      "name": "shmobile_init_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3243350296,
      "name": "shmobile_init_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3243350424,
      "name": "shmobile_init_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3243350592,
      "name": "shmobile_init_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3243350612,
      "name": "shmobile_init_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3243350632,
      "name": "shmobile_init_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 3243351736,
      "name": "shmobile_init_late",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void shmobile_init_late()
```
</details>
</li>
</ul>
