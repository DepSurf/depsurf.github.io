# Function: <code>sgx_encl_put_backing</code>

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
void sgx_encl_put_backing(struct sgx_backing * backing, bool do_write)
```

```json
{
  "name": "sgx_encl_put_backing",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579263660,
      "name": "sgx_encl_put_backing",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:617",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265136,
      "name": "sgx_encl_put_backing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void sgx_encl_put_backing(struct sgx_backing * backing, bool do_write)
```

```json
{
  "name": "sgx_encl_put_backing",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579264771,
      "name": "sgx_encl_put_backing",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:609",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265040,
      "name": "sgx_encl_put_backing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
void sgx_encl_put_backing(struct sgx_backing * backing, bool do_write)
```

```json
{
  "name": "sgx_encl_put_backing",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306188,
      "name": "sgx_encl_put_backing",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:650",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579306656,
      "name": "sgx_encl_put_backing",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgx_encl_put_backing(struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_put_backing",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579361019,
      "name": "sgx_encl_put_backing",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:851",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363744,
      "name": "sgx_encl_put_backing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sgx_encl_put_backing(struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_put_backing",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579431907,
      "name": "sgx_encl_put_backing",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1082",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434960,
      "name": "sgx_encl_put_backing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void sgx_encl_put_backing(struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_put_backing",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579443939,
      "name": "sgx_encl_put_backing",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1084",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447008,
      "name": "sgx_encl_put_backing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
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
void sgx_encl_put_backing(struct sgx_backing * backing)
```

```json
{
  "name": "sgx_encl_put_backing",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579473667,
      "name": "sgx_encl_put_backing",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1104",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476768,
      "name": "sgx_encl_put_backing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void sgx_encl_put_backing(struct sgx_backing * backing, bool do_write)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool do_write</code>
</li>
</ul>
</details>
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
