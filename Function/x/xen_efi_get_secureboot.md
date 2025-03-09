# Function: <code>xen_efi_get_secureboot</code>

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
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602800290,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:124",
      "file": "arch/x86/xen/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init"
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
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604594401,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:112",
      "file": "arch/x86/xen/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init"
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
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604690055,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:112",
      "file": "arch/x86/xen/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init"
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
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604702351,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:100",
      "file": "arch/x86/xen/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init"
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
enum efi_secureboot_mode xen_efi_get_secureboot()
```

```json
{
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579039890,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:100",
      "file": "arch/x86/xen/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/efi.c:xen_efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579039890,
      "name": "xen_efi_get_secureboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
enum efi_secureboot_mode xen_efi_get_secureboot()
```

```json
{
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591243152,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:97",
      "file": "arch/x86/xen/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/efi.c:xen_efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591243152,
      "name": "xen_efi_get_secureboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
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
enum efi_secureboot_mode xen_efi_get_secureboot()
```

```json
{
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591186655,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:97",
      "file": "arch/x86/xen/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/efi.c:xen_efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591186655,
      "name": "xen_efi_get_secureboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
enum efi_secureboot_mode xen_efi_get_secureboot()
```

```json
{
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592049745,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:97",
      "file": "arch/x86/xen/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/efi.c:xen_efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592049745,
      "name": "xen_efi_get_secureboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
enum efi_secureboot_mode xen_efi_get_secureboot()
```

```json
{
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593816171,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:97",
      "file": "arch/x86/xen/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/efi.c:xen_efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593816171,
      "name": "xen_efi_get_secureboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
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
enum efi_secureboot_mode xen_efi_get_secureboot()
```

```json
{
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579126544,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:97",
      "file": "arch/x86/xen/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/efi.c:xen_efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126544,
      "name": "xen_efi_get_secureboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
enum efi_secureboot_mode xen_efi_get_secureboot()
```

```json
{
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579126864,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:99",
      "file": "arch/x86/xen/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/efi.c:xen_efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126864,
      "name": "xen_efi_get_secureboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
enum efi_secureboot_mode xen_efi_get_secureboot()
```

```json
{
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579152768,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:99",
      "file": "arch/x86/xen/efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/xen/efi.c:xen_efi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579152768,
      "name": "xen_efi_get_secureboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604628639,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:100",
      "file": "arch/x86/xen/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604706447,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:100",
      "file": "arch/x86/xen/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init"
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
  "name": "xen_efi_get_secureboot",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604706463,
      "name": "xen_efi_get_secureboot",
      "external": false,
      "loc": "arch/x86/xen/efi.c:100",
      "file": "arch/x86/xen/efi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/xen/efi.c:xen_efi_init"
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
enum efi_secureboot_mode xen_efi_get_secureboot()
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
