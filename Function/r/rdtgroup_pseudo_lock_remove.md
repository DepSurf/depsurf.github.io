# Function: <code>rdtgroup_pseudo_lock_remove</code>

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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228464,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1411",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228464,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579241696,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1400",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579241696,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579243920,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1400",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243920,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267376,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1400",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267376,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579259744,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1400",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579259744,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579261488,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1400",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261488,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302736,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1406",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302736,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 361
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579358176,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1406",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579358176,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579429088,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1412",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579429088,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441056,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1412",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441056,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470704,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1426",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rmdir_all_sub"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470704,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 366
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579242768,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1400",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579242768,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579178352,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1400",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178352,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579243840,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1400",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243840,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_pseudo_lock_remove",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249392,
      "name": "rdtgroup_pseudo_lock_remove",
      "external": true,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:1400",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_kill_sb",
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_kn_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249392,
      "name": "rdtgroup_pseudo_lock_remove",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
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
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void rdtgroup_pseudo_lock_remove(struct rdtgroup * rdtgrp)
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
