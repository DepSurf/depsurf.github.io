# Function: <code>sgx_vepc_free_page</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int sgx_vepc_free_page(struct sgx_epc_page * epc_page)
```

```json
{
  "name": "sgx_vepc_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276560,
      "name": "sgx_vepc_free_page",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/virt.c:114",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276560,
      "name": "sgx_vepc_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int sgx_vepc_free_page(struct sgx_epc_page * epc_page)
```

```json
{
  "name": "sgx_vepc_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_vepc_free_page",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/virt.c:114",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579319344,
      "name": "sgx_vepc_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
    },
    {
      "addr": 18446744071592070853,
      "name": "sgx_vepc_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int sgx_vepc_free_page(struct sgx_epc_page * epc_page)
```

```json
{
  "name": "sgx_vepc_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_vepc_free_page",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/virt.c:128",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579379360,
      "name": "sgx_vepc_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071593837145,
      "name": "sgx_vepc_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sgx_vepc_free_page(struct sgx_epc_page * epc_page)
```

```json
{
  "name": "sgx_vepc_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_vepc_free_page",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/virt.c:128",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455776,
      "name": "sgx_vepc_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071595964619,
      "name": "sgx_vepc_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sgx_vepc_free_page(struct sgx_epc_page * epc_page)
```

```json
{
  "name": "sgx_vepc_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_vepc_free_page",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/virt.c:128",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579467936,
      "name": "sgx_vepc_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071596482231,
      "name": "sgx_vepc_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int sgx_vepc_free_page(struct sgx_epc_page * epc_page)
```

```json
{
  "name": "sgx_vepc_free_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_vepc_free_page",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/virt.c:128",
      "file": "arch/x86/kernel/cpu/sgx/virt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release",
        "arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498048,
      "name": "sgx_vepc_free_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071597378331,
      "name": "sgx_vepc_free_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int sgx_vepc_free_page(struct sgx_epc_page * epc_page)
```
</details>
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
