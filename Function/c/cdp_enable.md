# Function: <code>cdp_enable</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579121894,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:625",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579117562,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:958",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579130975,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1026",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int cdp_enable(int level, int data_type, int code_type)
```

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141152,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1072",
      "file": "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141152,
      "name": "cdp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int cdp_enable(int level, int data_type, int code_type)
```

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579199072,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1798",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579199072,
      "name": "cdp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 139
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
int cdp_enable(int level, int data_type, int code_type)
```

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211568,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1796",
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
      "addr": 18446744071579211568,
      "name": "cdp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int cdp_enable(int level, int data_type, int code_type)
```

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213824,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794",
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
      "addr": 18446744071579213824,
      "name": "cdp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579242948,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1898",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
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
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579235771,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1949",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
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
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579237375,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1949",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579278513,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1917",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579332573,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1917",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579401005,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1957",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579413131,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2234",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579442171,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:2325",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int cdp_enable(int level, int data_type, int code_type)
```

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212672,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794",
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
      "addr": 18446744071579212672,
      "name": "cdp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int cdp_enable(int level, int data_type, int code_type)
```

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579147504,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794",
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
      "addr": 18446744071579147504,
      "name": "cdp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int cdp_enable(int level, int data_type, int code_type)
```

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213744,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794",
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
      "addr": 18446744071579213744,
      "name": "cdp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int cdp_enable(int level, int data_type, int code_type)
```

```json
{
  "name": "cdp_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219168,
      "name": "cdp_enable",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794",
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
      "addr": 18446744071579219168,
      "name": "cdp_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
int cdp_enable(int level, int data_type, int code_type)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int cdp_enable(int level, int data_type, int code_type)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int cdp_enable(int level, int data_type, int code_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int cdp_enable(int level, int data_type, int code_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int cdp_enable(int level, int data_type, int code_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cdp_enable(int level, int data_type, int code_type)
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
