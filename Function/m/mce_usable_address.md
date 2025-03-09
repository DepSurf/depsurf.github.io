# Function: <code>mce_usable_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579128749,
      "name": "mce_usable_address",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:940",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll",
        "arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579128469,
      "name": "mce_usable_address",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:527",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579135671,
      "name": "mce_usable_address",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:552",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
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
  "name": "mce_usable_address",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579131568,
      "name": "mce_usable_address",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:482",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579131568,
      "name": "mce_usable_address.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579145936,
      "name": "mce_usable_address",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:491",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145936,
      "name": "mce_usable_address.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579156256,
      "name": "mce_usable_address",
      "external": false,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:488",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579156256,
      "name": "mce_usable_address.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579145728,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:486",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145728,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579157952,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:486",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579157952,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160448,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:486",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160448,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579181472,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:468",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181472,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579177680,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:534",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177680,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183680,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:534",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183680,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579217920,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:543",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217920,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579269904,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:468",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "drivers/ras/cec.c:cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269904,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579332752,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:468",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "drivers/ras/cec.c:cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579332752,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579341472,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:462",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "drivers/ras/cec.c:cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341472,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579370816,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:487",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:do_machine_check",
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll",
        "drivers/ras/cec.c:cec_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579370816,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160816,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:486",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160816,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579092336,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:486",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579092336,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579160368,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:486",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579160368,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mce_usable_address(struct mce * m)
```

```json
{
  "name": "mce_usable_address",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579165504,
      "name": "mce_usable_address",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:486",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:machine_check_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579165504,
      "name": "mce_usable_address",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int mce_usable_address(struct mce * m)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int mce_usable_address(struct mce * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int mce_usable_address(struct mce * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mce_usable_address(struct mce * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int mce_usable_address(struct mce * m)
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
