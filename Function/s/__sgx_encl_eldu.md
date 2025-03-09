# Function: <code>__sgx_encl_eldu</code>

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
int __sgx_encl_eldu(struct sgx_encl_page * encl_page, struct sgx_epc_page * epc_page, struct sgx_epc_page * secs_page)
```

```json
{
  "name": "__sgx_encl_eldu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579263216,
      "name": "__sgx_encl_eldu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:19",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579263216,
      "name": "__sgx_encl_eldu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 699
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
int __sgx_encl_eldu(struct sgx_encl_page * encl_page, struct sgx_epc_page * epc_page, struct sgx_epc_page * secs_page)
```

```json
{
  "name": "__sgx_encl_eldu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579264336,
      "name": "__sgx_encl_eldu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:19",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264336,
      "name": "__sgx_encl_eldu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 690
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
int __sgx_encl_eldu(struct sgx_encl_page * encl_page, struct sgx_epc_page * epc_page, struct sgx_epc_page * secs_page)
```

```json
{
  "name": "__sgx_encl_eldu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sgx_encl_eldu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:43",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305584,
      "name": "__sgx_encl_eldu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1072
    },
    {
      "addr": 18446744071592070634,
      "name": "__sgx_encl_eldu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int __sgx_encl_eldu(struct sgx_encl_page * encl_page, struct sgx_epc_page * epc_page, struct sgx_epc_page * secs_page)
```

```json
{
  "name": "__sgx_encl_eldu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sgx_encl_eldu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:129",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579360224,
      "name": "__sgx_encl_eldu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1876
    },
    {
      "addr": 18446744071593836898,
      "name": "__sgx_encl_eldu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
int __sgx_encl_eldu(struct sgx_encl_page * encl_page, struct sgx_epc_page * epc_page, struct sgx_epc_page * secs_page)
```

```json
{
  "name": "__sgx_encl_eldu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sgx_encl_eldu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:132",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431296,
      "name": "__sgx_encl_eldu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1682
    },
    {
      "addr": 18446744071595964274,
      "name": "__sgx_encl_eldu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int __sgx_encl_eldu(struct sgx_encl_page * encl_page, struct sgx_epc_page * epc_page, struct sgx_epc_page * secs_page)
```

```json
{
  "name": "__sgx_encl_eldu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sgx_encl_eldu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:132",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443328,
      "name": "__sgx_encl_eldu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1691
    },
    {
      "addr": 18446744071596481893,
      "name": "__sgx_encl_eldu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int __sgx_encl_eldu(struct sgx_encl_page * encl_page, struct sgx_epc_page * epc_page, struct sgx_epc_page * secs_page)
```

```json
{
  "name": "__sgx_encl_eldu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__sgx_encl_eldu",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:132",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473056,
      "name": "__sgx_encl_eldu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1679
    },
    {
      "addr": 18446744071597377993,
      "name": "__sgx_encl_eldu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int __sgx_encl_eldu(struct sgx_encl_page * encl_page, struct sgx_epc_page * epc_page, struct sgx_epc_page * secs_page)
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
