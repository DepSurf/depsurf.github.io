# Function: <code>resctrl_arch_set_cdp_enabled</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int resctrl_arch_set_cdp_enabled(enum resctrl_res_level l, bool enable)
```

```json
{
  "name": "resctrl_arch_set_cdp_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_arch_set_cdp_enabled",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1942",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592069473,
      "name": "resctrl_arch_set_cdp_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071579278352,
      "name": "resctrl_arch_set_cdp_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
int resctrl_arch_set_cdp_enabled(enum resctrl_res_level l, bool enable)
```

```json
{
  "name": "resctrl_arch_set_cdp_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_arch_set_cdp_enabled",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1942",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593835666,
      "name": "resctrl_arch_set_cdp_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579332416,
      "name": "resctrl_arch_set_cdp_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int resctrl_arch_set_cdp_enabled(enum resctrl_res_level l, bool enable)
```

```json
{
  "name": "resctrl_arch_set_cdp_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_arch_set_cdp_enabled",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1982",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595963146,
      "name": "resctrl_arch_set_cdp_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579400848,
      "name": "resctrl_arch_set_cdp_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
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
int resctrl_arch_set_cdp_enabled(enum resctrl_res_level l, bool enable)
```

```json
{
  "name": "resctrl_arch_set_cdp_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_arch_set_cdp_enabled",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2259",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596480812,
      "name": "resctrl_arch_set_cdp_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579412976,
      "name": "resctrl_arch_set_cdp_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int resctrl_arch_set_cdp_enabled(enum resctrl_res_level l, bool enable)
```

```json
{
  "name": "resctrl_arch_set_cdp_enabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "resctrl_arch_set_cdp_enabled",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2350",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597376911,
      "name": "resctrl_arch_set_cdp_enabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071579442016,
      "name": "resctrl_arch_set_cdp_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int resctrl_arch_set_cdp_enabled(enum resctrl_res_level l, bool enable)
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
