# Function: <code>__sgx_encl_ewb</code>

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
int __sgx_encl_ewb(struct sgx_epc_page * epc_page, void * va_slot, struct sgx_backing * backing)
```

```json
{
  "name": "__sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270944,
      "name": "__sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:141",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270944,
      "name": "__sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
int __sgx_encl_ewb(struct sgx_epc_page * epc_page, void * va_slot, struct sgx_backing * backing)
```

```json
{
  "name": "__sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579272336,
      "name": "__sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:160",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579272336,
      "name": "__sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __sgx_encl_ewb(struct sgx_epc_page * epc_page, void * va_slot, struct sgx_backing * backing)
```

```json
{
  "name": "__sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579314496,
      "name": "__sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:159",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314496,
      "name": "__sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int __sgx_encl_ewb(struct sgx_epc_page * epc_page, void * va_slot, struct sgx_backing * backing)
```

```json
{
  "name": "__sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579372672,
      "name": "__sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:180",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579372672,
      "name": "__sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int __sgx_encl_ewb(struct sgx_epc_page * epc_page, void * va_slot, struct sgx_backing * backing)
```

```json
{
  "name": "__sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448512,
      "name": "__sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:159",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448512,
      "name": "__sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int __sgx_encl_ewb(struct sgx_epc_page * epc_page, void * va_slot, struct sgx_backing * backing)
```

```json
{
  "name": "__sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579460640,
      "name": "__sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:159",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579460640,
      "name": "__sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int __sgx_encl_ewb(struct sgx_epc_page * epc_page, void * va_slot, struct sgx_backing * backing)
```

```json
{
  "name": "__sgx_encl_ewb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490704,
      "name": "__sgx_encl_ewb",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/main.c:159",
      "file": "arch/x86/kernel/cpu/sgx/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490704,
      "name": "__sgx_encl_ewb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int __sgx_encl_ewb(struct sgx_epc_page * epc_page, void * va_slot, struct sgx_backing * backing)
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
