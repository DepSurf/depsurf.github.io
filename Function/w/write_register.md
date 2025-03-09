# Function: <code>write_register</code>

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
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586514703,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:201",
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586693424,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:135",
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
      "addr": 18446744071586693424,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586819200,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:135",
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
      "addr": 18446744071586819200,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587303520,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:134",
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
      "addr": 18446744071587303520,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587606192,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:134",
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
      "addr": 18446744071587606192,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587734288,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:134",
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
      "addr": 18446744071587734288,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588018528,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071588018528,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588226176,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071588226176,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589101296,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071589101296,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589100992,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071589100992,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588990208,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071588990208,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589704208,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071589704208,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591210675,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:135",
      "file": "drivers/mailbox/pcc.c",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592953459,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:135",
      "file": "drivers/mailbox/pcc.c",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593403827,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:135",
      "file": "drivers/mailbox/pcc.c",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594149395,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:148",
      "file": "drivers/mailbox/pcc.c",
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501671808,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446603336501671808,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587837872,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071587837872,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587544240,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071587544240,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588180656,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071588180656,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```

```json
{
  "name": "write_register",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588298544,
      "name": "write_register",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:125",
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
      "addr": 18446744071588298544,
      "name": "write_register",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
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
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int write_register(void * vaddr, u64 val, unsigned int bit_width)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int write_register(void * vaddr, u64 val, unsigned int bit_width)
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
