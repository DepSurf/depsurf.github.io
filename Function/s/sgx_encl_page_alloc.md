# Function: <code>sgx_encl_page_alloc</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sgx_encl_page_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579268875,
      "name": "sgx_encl_page_alloc",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:170",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
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
  "name": "sgx_encl_page_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579269118,
      "name": "sgx_encl_page_alloc",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:171",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sgx_encl_page_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579311070,
      "name": "sgx_encl_page_alloc",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:171",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sgx_encl_page_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579369291,
      "name": "sgx_encl_page_alloc",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:171",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct sgx_encl_page * sgx_encl_page_alloc(struct sgx_encl * encl, long unsigned int offset, u64 secinfo_flags)
```

```json
{
  "name": "sgx_encl_page_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579437808,
      "name": "sgx_encl_page_alloc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1136",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435472,
      "name": "sgx_encl_page_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct sgx_encl_page * sgx_encl_page_alloc(struct sgx_encl * encl, long unsigned int offset, u64 secinfo_flags)
```

```json
{
  "name": "sgx_encl_page_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579449888,
      "name": "sgx_encl_page_alloc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1138",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447520,
      "name": "sgx_encl_page_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
struct sgx_encl_page * sgx_encl_page_alloc(struct sgx_encl * encl, long unsigned int offset, u64 secinfo_flags)
```

```json
{
  "name": "sgx_encl_page_alloc",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479693,
      "name": "sgx_encl_page_alloc",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1158",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477280,
      "name": "sgx_encl_page_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct sgx_encl_page * sgx_encl_page_alloc(struct sgx_encl * encl, long unsigned int offset, u64 secinfo_flags)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
