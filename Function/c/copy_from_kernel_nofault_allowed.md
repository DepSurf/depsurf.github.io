# Function: <code>copy_from_kernel_nofault_allowed</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
bool copy_from_kernel_nofault_allowed(const void * unsafe_src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417536,
      "name": "copy_from_kernel_nofault_allowed",
      "external": true,
      "loc": "arch/x86/mm/maccess.c:12",
      "file": "arch/x86/mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/maccess.c:strncpy_from_kernel_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417536,
      "name": "copy_from_kernel_nofault_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool copy_from_kernel_nofault_allowed(const void * unsafe_src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579417568,
      "name": "copy_from_kernel_nofault_allowed",
      "external": true,
      "loc": "arch/x86/mm/maccess.c:12",
      "file": "arch/x86/mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/maccess.c:strncpy_from_kernel_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417568,
      "name": "copy_from_kernel_nofault_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
bool copy_from_kernel_nofault_allowed(const void * unsafe_src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420656,
      "name": "copy_from_kernel_nofault_allowed",
      "external": true,
      "loc": "arch/x86/mm/maccess.c:12",
      "file": "arch/x86/mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/maccess.c:strncpy_from_kernel_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420656,
      "name": "copy_from_kernel_nofault_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool copy_from_kernel_nofault_allowed(const void * unsafe_src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613392,
      "name": "copy_from_kernel_nofault_allowed",
      "external": true,
      "loc": "arch/x86/mm/maccess.c:12",
      "file": "arch/x86/mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/maccess.c:strncpy_from_kernel_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592088089,
      "name": "copy_from_kernel_nofault_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579484208,
      "name": "copy_from_kernel_nofault_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
bool copy_from_kernel_nofault_allowed(const void * unsafe_src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581973920,
      "name": "copy_from_kernel_nofault_allowed",
      "external": true,
      "loc": "arch/x86/mm/maccess.c:7",
      "file": "arch/x86/mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/maccess.c:strncpy_from_kernel_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593855013,
      "name": "copy_from_kernel_nofault_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579563552,
      "name": "copy_from_kernel_nofault_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool copy_from_kernel_nofault_allowed(const void * unsafe_src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582408608,
      "name": "copy_from_kernel_nofault_allowed",
      "external": true,
      "loc": "arch/x86/mm/maccess.c:7",
      "file": "arch/x86/mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/maccess.c:strncpy_from_kernel_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595969706,
      "name": "copy_from_kernel_nofault_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
    },
    {
      "addr": 18446744071579671216,
      "name": "copy_from_kernel_nofault_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
bool copy_from_kernel_nofault_allowed(const void * unsafe_src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582614592,
      "name": "copy_from_kernel_nofault_allowed",
      "external": true,
      "loc": "arch/x86/mm/maccess.c:7",
      "file": "arch/x86/mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/maccess.c:strncpy_from_kernel_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596487295,
      "name": "copy_from_kernel_nofault_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579685152,
      "name": "copy_from_kernel_nofault_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
bool copy_from_kernel_nofault_allowed(const void * unsafe_src, size_t size)
```

```json
{
  "name": "copy_from_kernel_nofault_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582786112,
      "name": "copy_from_kernel_nofault_allowed",
      "external": true,
      "loc": "arch/x86/mm/maccess.c:9",
      "file": "arch/x86/mm/maccess.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/maccess.c:strncpy_from_kernel_nofault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597383917,
      "name": "copy_from_kernel_nofault_allowed.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071579719664,
      "name": "copy_from_kernel_nofault_allowed",
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool copy_from_kernel_nofault_allowed(const void * unsafe_src, size_t size)
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
