# Function: <code>sgx_free_va_slot</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgx_free_va_slot(struct sgx_va_page * va_page, unsigned int offset)
```

```json
{
  "name": "sgx_free_va_slot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579263990,
      "name": "sgx_free_va_slot",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:729",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266032,
      "name": "sgx_free_va_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgx_free_va_slot(struct sgx_va_page * va_page, unsigned int offset)
```

```json
{
  "name": "sgx_free_va_slot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579265718,
      "name": "sgx_free_va_slot",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:721",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265456,
      "name": "sgx_free_va_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgx_free_va_slot(struct sgx_va_page * va_page, unsigned int offset)
```

```json
{
  "name": "sgx_free_va_slot",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579307382,
      "name": "sgx_free_va_slot",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:762",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307056,
      "name": "sgx_free_va_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
void sgx_free_va_slot(struct sgx_va_page * va_page, unsigned int offset)
```

```json
{
  "name": "sgx_free_va_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579364304,
      "name": "sgx_free_va_slot",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:958",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579364304,
      "name": "sgx_free_va_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void sgx_free_va_slot(struct sgx_va_page * va_page, unsigned int offset)
```

```json
{
  "name": "sgx_free_va_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436080,
      "name": "sgx_free_va_slot",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1266",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436080,
      "name": "sgx_free_va_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void sgx_free_va_slot(struct sgx_va_page * va_page, unsigned int offset)
```

```json
{
  "name": "sgx_free_va_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448160,
      "name": "sgx_free_va_slot",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1268",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448160,
      "name": "sgx_free_va_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void sgx_free_va_slot(struct sgx_va_page * va_page, unsigned int offset)
```

```json
{
  "name": "sgx_free_va_slot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579477968,
      "name": "sgx_free_va_slot",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1288",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477968,
      "name": "sgx_free_va_slot",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void sgx_free_va_slot(struct sgx_va_page * va_page, unsigned int offset)
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
