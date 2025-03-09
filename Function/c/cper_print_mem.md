# Function: <code>cper_print_mem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586005113,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:308",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586413113,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:308",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586622425,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:308",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586746567,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:431",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587232505,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:431",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587232505,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587531338,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:313",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531338,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587712186,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:326",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587712186,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587991277,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:314",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587991277,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588198637,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:314",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588198637,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589066569,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:314",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591609569,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:328",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591552862,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:326",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592671844,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:324",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592671844,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 357
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
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594556749,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:350",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594556749,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592889808,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:354",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592889808,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593328384,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:354",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593328384,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594085424,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:354",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594085424,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501554204,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:314",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501554204,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587520493,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:314",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587520493,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588153165,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:314",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588153165,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```

```json
{
  "name": "cper_print_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588270573,
      "name": "cper_print_mem",
      "external": false,
      "loc": "drivers/firmware/efi/cper.c:314",
      "file": "drivers/firmware/efi/cper.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper.c:cper_estatus_print_section"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270573,
      "name": "cper_print_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void cper_print_mem(const char * pfx, const struct cper_sec_mem_err * mem, int len)
```
</details>
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
