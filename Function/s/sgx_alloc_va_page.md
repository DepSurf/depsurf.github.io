# Function: <code>sgx_alloc_va_page</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct sgx_epc_page * sgx_alloc_va_page()
```

```json
{
  "name": "sgx_alloc_va_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579265808,
      "name": "sgx_alloc_va_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:685",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265808,
      "name": "sgx_alloc_va_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
struct sgx_epc_page * sgx_alloc_va_page()
```

```json
{
  "name": "sgx_alloc_va_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267632,
      "name": "sgx_alloc_va_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:677",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267632,
      "name": "sgx_alloc_va_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct sgx_epc_page * sgx_alloc_va_page()
```

```json
{
  "name": "sgx_alloc_va_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_alloc_va_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:718",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592070688,
      "name": "sgx_alloc_va_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071579309424,
      "name": "sgx_alloc_va_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct sgx_epc_page * sgx_alloc_va_page()
```

```json
{
  "name": "sgx_alloc_va_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_alloc_va_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:914",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593836987,
      "name": "sgx_alloc_va_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071579366656,
      "name": "sgx_alloc_va_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct sgx_epc_page * sgx_alloc_va_page(bool reclaim)
```

```json
{
  "name": "sgx_alloc_va_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_alloc_va_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1222",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595964336,
      "name": "sgx_alloc_va_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071579439984,
      "name": "sgx_alloc_va_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct sgx_epc_page * sgx_alloc_va_page(bool reclaim)
```

```json
{
  "name": "sgx_alloc_va_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_alloc_va_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1224",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596481947,
      "name": "sgx_alloc_va_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071579452080,
      "name": "sgx_alloc_va_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
struct sgx_epc_page * sgx_alloc_va_page(bool reclaim)
```

```json
{
  "name": "sgx_alloc_va_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_alloc_va_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1244",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597378047,
      "name": "sgx_alloc_va_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071579482000,
      "name": "sgx_alloc_va_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct sgx_epc_page * sgx_alloc_va_page()
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reclaim</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
