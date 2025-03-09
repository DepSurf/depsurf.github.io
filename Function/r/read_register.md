# Function: <code>read_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586514646,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:175",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_send_data"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586693312,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:109",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586693312,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586819088,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:109",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586819088,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587303392,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:108",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587303392,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587606064,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:108",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587606064,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587734160,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:108",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587734160,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588018416,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588018416,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588226064,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588226064,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589101184,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589101184,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589100880,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589100880,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588990096,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588990096,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589704096,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589704096,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591211470,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:117",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_send_data"
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
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592954318,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:117",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_send_data"
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
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593404682,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:117",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_send_data"
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
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594149982,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:130",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mailbox/pcc.c:pcc_send_data"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501671496,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501671496,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    }
  ]
}
```
</details>
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587837760,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587837760,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587544128,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587544128,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588180544,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588180544,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```

```json
{
  "name": "read_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588298432,
      "name": "read_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:99",
      "file": "drivers/mailbox/pcc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588298432,
      "name": "read_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int read_register(void * vaddr, u64 * val, unsigned int bit_width)
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
