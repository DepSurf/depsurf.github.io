# Function: <code>flush_tlb_one_user</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void flush_tlb_one_user(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579416629,
      "name": "flush_tlb_one_user",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1102",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_one_kernel"
      ],
      "caller_func": [
        "arch/x86/platform/uv/tlb_uv.c:bau_process_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416864,
      "name": "flush_tlb_one_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void flush_tlb_one_user(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579416709,
      "name": "flush_tlb_one_user",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1038",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_one_kernel"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416944,
      "name": "flush_tlb_one_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void flush_tlb_one_user(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579419797,
      "name": "flush_tlb_one_user",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1082",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_one_kernel",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420016,
      "name": "flush_tlb_one_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void flush_tlb_one_user(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579483349,
      "name": "flush_tlb_one_user",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1141",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_one_kernel",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483568,
      "name": "flush_tlb_one_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
void flush_tlb_one_user(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579562453,
      "name": "flush_tlb_one_user",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1115",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_one_kernel",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579562720,
      "name": "flush_tlb_one_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void flush_tlb_one_user(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579669957,
      "name": "flush_tlb_one_user",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1139",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_one_kernel",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670272,
      "name": "flush_tlb_one_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void flush_tlb_one_user(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579683909,
      "name": "flush_tlb_one_user",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1160",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_one_kernel",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684224,
      "name": "flush_tlb_one_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void flush_tlb_one_user(long unsigned int addr)
```

```json
{
  "name": "flush_tlb_one_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579718405,
      "name": "flush_tlb_one_user",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1169",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:flush_tlb_one_kernel",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718736,
      "name": "flush_tlb_one_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void flush_tlb_one_user(long unsigned int addr)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
