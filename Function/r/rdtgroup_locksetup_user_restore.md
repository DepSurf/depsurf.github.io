# Function: <code>rdtgroup_locksetup_user_restore</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579222944,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:606",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579222944,
      "name": "rdtgroup_locksetup_user_restore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579236144,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236144,
      "name": "rdtgroup_locksetup_user_restore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579238384,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238384,
      "name": "rdtgroup_locksetup_user_restore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579265792,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261632,
      "name": "rdtgroup_locksetup_user_restore.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579258192,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579254128,
      "name": "rdtgroup_locksetup_user_restore.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579259760,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255824,
      "name": "rdtgroup_locksetup_user_restore.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579300943,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:599",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296768,
      "name": "rdtgroup_locksetup_user_restore.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
    },
    {
      "addr": 18446744071592070500,
      "name": "rdtgroup_locksetup_user_restore.part.0.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579356317,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:599",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579352144,
      "name": "rdtgroup_locksetup_user_restore.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071593836736,
      "name": "rdtgroup_locksetup_user_restore.part.0.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579426813,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:601",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422832,
      "name": "rdtgroup_locksetup_user_restore.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071595964150,
      "name": "rdtgroup_locksetup_user_restore.part.0.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579438765,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:601",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434752,
      "name": "rdtgroup_locksetup_user_restore.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071596481769,
      "name": "rdtgroup_locksetup_user_restore.part.0.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579468397,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:615",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464336,
      "name": "rdtgroup_locksetup_user_restore.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 189
    },
    {
      "addr": 18446744071597377869,
      "name": "rdtgroup_locksetup_user_restore.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579237232,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237232,
      "name": "rdtgroup_locksetup_user_restore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579172512,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579172512,
      "name": "rdtgroup_locksetup_user_restore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579238304,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238304,
      "name": "rdtgroup_locksetup_user_restore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```

```json
{
  "name": "rdtgroup_locksetup_user_restore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579243776,
      "name": "rdtgroup_locksetup_user_restore",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595",
      "file": "arch/x86/kernel/cpu/resctrl/pseudo_lock.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit",
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243776,
      "name": "rdtgroup_locksetup_user_restore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
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
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup * rdtgrp)
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
