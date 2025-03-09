# Function: <code>sgx_encl_ewb</code>

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
void sgx_encl_ewb(struct sgx_epc_page * epc_page, struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271392,
      "name": "sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:206",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_write",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271392,
      "name": "sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 536
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
void sgx_encl_ewb(struct sgx_epc_page * epc_page, struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272784,
      "name": "sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:225",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272784,
      "name": "sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 534
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
void sgx_encl_ewb(struct sgx_epc_page * epc_page, struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:224",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579315072,
      "name": "sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
    },
    {
      "addr": 18446744071592070794,
      "name": "sgx_encl_ewb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sgx_encl_ewb(struct sgx_epc_page * epc_page, struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:247",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579373600,
      "name": "sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    },
    {
      "addr": 18446744071593837086,
      "name": "sgx_encl_ewb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sgx_encl_ewb(struct sgx_epc_page * epc_page, struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:197",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449072,
      "name": "sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    },
    {
      "addr": 18446744071595964528,
      "name": "sgx_encl_ewb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sgx_encl_ewb(struct sgx_epc_page * epc_page, struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:197",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461232,
      "name": "sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    },
    {
      "addr": 18446744071596482139,
      "name": "sgx_encl_ewb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sgx_encl_ewb(struct sgx_epc_page * epc_page, struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:197",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579491296,
      "name": "sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 677
    },
    {
      "addr": 18446744071597378239,
      "name": "sgx_encl_ewb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void sgx_encl_ewb(struct sgx_epc_page * epc_page, struct sgx_backing * backing)
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
