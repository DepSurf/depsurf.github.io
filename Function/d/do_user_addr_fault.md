# Function: <code>do_user_addr_fault</code>

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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579353671,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1318",
      "file": "arch/x86/mm/fault.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/fault.c:__do_page_fault",
        "arch/x86/mm/fault.c:__do_page_fault"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579352464,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1098
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579367424,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1282",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367424,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1092
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579371664,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1304",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579371664,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1092
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400304,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1270",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400304,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1094
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402192,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1241",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402192,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void do_user_addr_fault(struct pt_regs * regs, long unsigned int error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1213",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579404928,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1608
    },
    {
      "addr": 18446744071591212513,
      "name": "do_user_addr_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1220",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467440,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1635
    },
    {
      "addr": 18446744071592086707,
      "name": "do_user_addr_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1220",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579544304,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1661
    },
    {
      "addr": 18446744071593853505,
      "name": "do_user_addr_fault.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1251",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579650016,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1824
    },
    {
      "addr": 18446744071595969033,
      "name": "do_user_addr_fault.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void do_user_addr_fault(struct pt_regs * regs, long unsigned int error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1225",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664352,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1707
    },
    {
      "addr": 18446744071596486679,
      "name": "do_user_addr_fault.cold",
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1230",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:exc_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698352,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1712
    },
    {
      "addr": 18446744071597383301,
      "name": "do_user_addr_fault.cold",
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579367568,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1304",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367568,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1092
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298048,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1304",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298048,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1079
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579367488,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1304",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367488,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1092
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```

```json
{
  "name": "do_user_addr_fault",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579375920,
      "name": "do_user_addr_fault",
      "external": false,
      "loc": "arch/x86/mm/fault.c:1304",
      "file": "arch/x86/mm/fault.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__do_page_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579375920,
      "name": "do_user_addr_fault",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1103
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
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
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int hw_error_code</code>
</li>
</ul>
</details>
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
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void do_user_addr_fault(struct pt_regs * regs, long unsigned int hw_error_code, long unsigned int address)
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
