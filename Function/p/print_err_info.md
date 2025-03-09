# Function: <code>print_err_info</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587539051,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:183",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
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
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587723083,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:183",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
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
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588003769,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:183",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
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
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588211337,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:183",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
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
void print_err_info(const char * pfx, u8 err_type, u64 check)
```

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589077887,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:183",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589077887,
      "name": "print_err_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
void print_err_info(const char * pfx, u8 err_type, u64 check)
```

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591611547,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:184",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591611547,
      "name": "print_err_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
void print_err_info(const char * pfx, u8 err_type, u64 check)
```

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591554761,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:184",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591554761,
      "name": "print_err_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 669
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
void print_err_info(const char * pfx, u8 err_type, u64 check)
```

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592674498,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:184",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592674498,
      "name": "print_err_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
void print_err_info(const char * pfx, u8 err_type, u64 check)
```

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594559743,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:184",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594559743,
      "name": "print_err_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
void print_err_info(const char * pfx, u8 err_type, u64 check)
```

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592905072,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:184",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592905072,
      "name": "print_err_info",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void print_err_info(const char * pfx, u8 err_type, u64 check)
```

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593343904,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:184",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593343904,
      "name": "print_err_info",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void print_err_info(const char * pfx, u8 err_type, u64 check)
```

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594097584,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:184",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594097584,
      "name": "print_err_info",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1094
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587533081,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:183",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
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
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588165817,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:183",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
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
  "name": "print_err_info",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588283689,
      "name": "print_err_info",
      "external": false,
      "loc": "drivers/firmware/efi/cper-x86.c:183",
      "file": "drivers/firmware/efi/cper-x86.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/cper-x86.c:cper_print_proc_ia"
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
void print_err_info(const char * pfx, u8 err_type, u64 check)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
