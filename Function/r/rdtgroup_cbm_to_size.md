# Function: <code>rdtgroup_cbm_to_size</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579206000,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1262",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579206000,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219728,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1260",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219728,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579222048,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222048,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246768,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1349",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246768,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579239936,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1371",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579239936,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240208,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1371",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240208,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579277600,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1329",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579277600,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331568,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1329",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331568,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399936,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1326",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399936,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579412064,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1341",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579412064,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441024,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1409",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441024,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579220896,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579220896,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579155824,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579155824,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221968,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221968,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```

```json
{
  "name": "rdtgroup_cbm_to_size",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579227360,
      "name": "rdtgroup_cbm_to_size",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227360,
      "name": "rdtgroup_cbm_to_size",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```
</details>
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource * r, struct rdt_domain * d, long unsigned int cbm)
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
