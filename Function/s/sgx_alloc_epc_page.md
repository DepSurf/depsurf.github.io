# Function: <code>sgx_alloc_epc_page</code>

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
struct sgx_epc_page * sgx_alloc_epc_page(void * owner, bool reclaim)
```

```json
{
  "name": "sgx_alloc_epc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274256,
      "name": "sgx_alloc_epc_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:563",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274256,
      "name": "sgx_alloc_epc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
struct sgx_epc_page * sgx_alloc_epc_page(void * owner, bool reclaim)
```

```json
{
  "name": "sgx_alloc_epc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275936,
      "name": "sgx_alloc_epc_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:577",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275936,
      "name": "sgx_alloc_epc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
struct sgx_epc_page * sgx_alloc_epc_page(void * owner, bool reclaim)
```

```json
{
  "name": "sgx_alloc_epc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579317728,
      "name": "sgx_alloc_epc_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:577",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579317728,
      "name": "sgx_alloc_epc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
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
struct sgx_epc_page * sgx_alloc_epc_page(void * owner, bool reclaim)
```

```json
{
  "name": "sgx_alloc_epc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579376176,
      "name": "sgx_alloc_epc_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:601",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579376176,
      "name": "sgx_alloc_epc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct sgx_epc_page * sgx_alloc_epc_page(void * owner, bool reclaim)
```

```json
{
  "name": "sgx_alloc_epc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452496,
      "name": "sgx_alloc_epc_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:559",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452496,
      "name": "sgx_alloc_epc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct sgx_epc_page * sgx_alloc_epc_page(void * owner, bool reclaim)
```

```json
{
  "name": "sgx_alloc_epc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579464672,
      "name": "sgx_alloc_epc_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:559",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579464672,
      "name": "sgx_alloc_epc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct sgx_epc_page * sgx_alloc_epc_page(void * owner, bool reclaim)
```

```json
{
  "name": "sgx_alloc_epc_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494736,
      "name": "sgx_alloc_epc_page",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:559",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page",
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494736,
      "name": "sgx_alloc_epc_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct sgx_epc_page * sgx_alloc_epc_page(void * owner, bool reclaim)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
