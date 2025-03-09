# Function: <code>uv_bios_call_irqsave</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579468016,
      "name": "uv_bios_call_irqsave",
      "external": true,
      "loc": "arch/x86/platform/uv/bios_uv.c:59",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579468016,
      "name": "uv_bios_call_irqsave",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579490112,
      "name": "uv_bios_call_irqsave",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:62",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490112,
      "name": "uv_bios_call_irqsave.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579472000,
      "name": "uv_bios_call_irqsave",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:54",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472000,
      "name": "uv_bios_call_irqsave.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579474080,
      "name": "uv_bios_call_irqsave",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:54",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474080,
      "name": "uv_bios_call_irqsave.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579539648,
      "name": "uv_bios_call_irqsave",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:54",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539648,
      "name": "uv_bios_call_irqsave.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579627984,
      "name": "uv_bios_call_irqsave",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:54",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627984,
      "name": "uv_bios_call_irqsave.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579741984,
      "name": "uv_bios_call_irqsave",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:54",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579741984,
      "name": "uv_bios_call_irqsave.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579788464,
      "name": "uv_bios_call_irqsave",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:54",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579788464,
      "name": "uv_bios_call_irqsave.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822128,
      "name": "uv_bios_call_irqsave",
      "external": false,
      "loc": "arch/x86/platform/uv/bios_uv.c:54",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579822128,
      "name": "uv_bios_call_irqsave.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```

```json
{
  "name": "uv_bios_call_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473344,
      "name": "uv_bios_call_irqsave",
      "external": true,
      "loc": "arch/x86/platform/uv/bios_uv.c:59",
      "file": "arch/x86/platform/uv/bios_uv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc",
        "arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473344,
      "name": "uv_bios_call_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
