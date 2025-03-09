# Function: <code>set_cache_qos_cfg</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140096,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1014",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:cdp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140096,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579198672,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1740",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579198672,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211168,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1738",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211168,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213424,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213424,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579241728,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1827",
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
      "addr": 18446744071579241728,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579231648,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1873",
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
      "addr": 18446744071579231648,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579232624,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1873",
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
      "addr": 18446744071579232624,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1836",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272240,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071592069083,
      "name": "set_cache_qos_cfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1836",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325552,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071593835278,
      "name": "set_cache_qos_cfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1841",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393744,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
    },
    {
      "addr": 18446744071595962801,
      "name": "set_cache_qos_cfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2122",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403648,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071596480288,
      "name": "set_cache_qos_cfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2213",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579432544,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071597376367,
      "name": "set_cache_qos_cfg.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212272,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212272,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147104,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579147104,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213344,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213344,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
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
int set_cache_qos_cfg(int level, bool enable)
```

```json
{
  "name": "set_cache_qos_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579218752,
      "name": "set_cache_qos_cfg",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1736",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_disable_all",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:cdp_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579218752,
      "name": "set_cache_qos_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int set_cache_qos_cfg(int level, bool enable)
```
</details>
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
int set_cache_qos_cfg(int level, bool enable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int set_cache_qos_cfg(int level, bool enable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int set_cache_qos_cfg(int level, bool enable)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int set_cache_qos_cfg(int level, bool enable)
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
