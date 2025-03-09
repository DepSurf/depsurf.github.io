# Function: <code>get_rdt_alloc_resources</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596337162,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:719",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602655333,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:722",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602826513,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:792",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604633008,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:843",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604730250,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:835",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604743363,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:835",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool get_rdt_alloc_resources()
```

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609089268,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:837",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609089268,
      "name": "get_rdt_alloc_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 573
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
bool get_rdt_alloc_resources()
```

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612153031,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:841",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612153031,
      "name": "get_rdt_alloc_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 441
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
bool get_rdt_alloc_resources()
```

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614292653,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:841",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614292653,
      "name": "get_rdt_alloc_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 626
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
bool get_rdt_alloc_resources()
```

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615218880,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:784",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615218880,
      "name": "get_rdt_alloc_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 618
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
bool get_rdt_alloc_resources()
```

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616992695,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:784",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616992695,
      "name": "get_rdt_alloc_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 632
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627617958,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:737",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool get_rdt_alloc_resources()
```

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619373488,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:779",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619373488,
      "name": "get_rdt_alloc_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 641
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
bool get_rdt_alloc_resources()
```

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621668768,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:783",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621668768,
      "name": "get_rdt_alloc_resources",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 888
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604669666,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:835",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604637253,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:835",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604747429,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:835",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_rdt_alloc_resources",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604747475,
      "name": "get_rdt_alloc_resources",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:835",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool get_rdt_alloc_resources()
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool get_rdt_alloc_resources()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool get_rdt_alloc_resources()
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
