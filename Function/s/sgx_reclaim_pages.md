# Function: <code>sgx_reclaim_pages</code>

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
void sgx_reclaim_pages()
```

```json
{
  "name": "sgx_reclaim_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579273408,
      "name": "sgx_reclaim_pages",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:304",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273408,
      "name": "sgx_reclaim_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 842
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
void sgx_reclaim_pages()
```

```json
{
  "name": "sgx_reclaim_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274000,
      "name": "sgx_reclaim_pages",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:323",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274000,
      "name": "sgx_reclaim_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
void sgx_reclaim_pages()
```

```json
{
  "name": "sgx_reclaim_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579315936,
      "name": "sgx_reclaim_pages",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:322",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315936,
      "name": "sgx_reclaim_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1325
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
void sgx_reclaim_pages()
```

```json
{
  "name": "sgx_reclaim_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374896,
      "name": "sgx_reclaim_pages",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:346",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374896,
      "name": "sgx_reclaim_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1268
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
void sgx_reclaim_pages()
```

```json
{
  "name": "sgx_reclaim_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_reclaim_pages",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:296",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450896,
      "name": "sgx_reclaim_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1495
    },
    {
      "addr": 18446744071595964587,
      "name": "sgx_reclaim_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
void sgx_reclaim_pages()
```

```json
{
  "name": "sgx_reclaim_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_reclaim_pages",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:296",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579463072,
      "name": "sgx_reclaim_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
    },
    {
      "addr": 18446744071596482198,
      "name": "sgx_reclaim_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void sgx_reclaim_pages()
```

```json
{
  "name": "sgx_reclaim_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_reclaim_pages",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:296",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page",
        "arch/x86/kernel/cpu/sgx/main.c:ksgxd",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_direct"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493136,
      "name": "sgx_reclaim_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1491
    },
    {
      "addr": 18446744071597378298,
      "name": "sgx_reclaim_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void sgx_reclaim_pages()
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
