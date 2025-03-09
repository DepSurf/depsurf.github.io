# Function: <code>hv_call_deposit_pages</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages)
```

```json
{
  "name": "hv_call_deposit_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579059715,
      "name": "hv_call_deposit_pages",
      "external": true,
      "loc": "arch/x86/hyperv/hv_proc.c:24",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058240,
      "name": "hv_call_deposit_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 843
    },
    {
      "addr": 18446744071591187323,
      "name": "hv_call_deposit_pages.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579059088,
      "name": "hv_call_deposit_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages)
```

```json
{
  "name": "hv_call_deposit_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579080867,
      "name": "hv_call_deposit_pages",
      "external": true,
      "loc": "arch/x86/hyperv/hv_proc.c:24",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579079392,
      "name": "hv_call_deposit_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 841
    },
    {
      "addr": 18446744071592050587,
      "name": "hv_call_deposit_pages.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579080240,
      "name": "hv_call_deposit_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages)
```

```json
{
  "name": "hv_call_deposit_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579109248,
      "name": "hv_call_deposit_pages",
      "external": true,
      "loc": "arch/x86/hyperv/hv_proc.c:24",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579107680,
      "name": "hv_call_deposit_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 872
    },
    {
      "addr": 18446744071593817121,
      "name": "hv_call_deposit_pages.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579108560,
      "name": "hv_call_deposit_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages)
```

```json
{
  "name": "hv_call_deposit_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579146819,
      "name": "hv_call_deposit_pages",
      "external": true,
      "loc": "arch/x86/hyperv/hv_proc.c:24",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145152,
      "name": "hv_call_deposit_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 916
    },
    {
      "addr": 18446744071579146096,
      "name": "hv_call_deposit_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages)
```

```json
{
  "name": "hv_call_deposit_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579147379,
      "name": "hv_call_deposit_pages",
      "external": true,
      "loc": "arch/x86/hyperv/hv_proc.c:24",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145760,
      "name": "hv_call_deposit_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 873
    },
    {
      "addr": 18446744071596475517,
      "name": "hv_call_deposit_pages.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579146656,
      "name": "hv_call_deposit_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages)
```

```json
{
  "name": "hv_call_deposit_pages",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579176722,
      "name": "hv_call_deposit_pages",
      "external": true,
      "loc": "arch/x86/hyperv/hv_proc.c:24",
      "file": "arch/x86/hyperv/hv_proc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ],
      "caller_func": [
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_create_vp",
        "arch/x86/hyperv/hv_proc.c:hv_call_add_logical_proc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579175392,
      "name": "hv_call_deposit_pages.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 808
    },
    {
      "addr": 18446744071597371282,
      "name": "hv_call_deposit_pages.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071579176224,
      "name": "hv_call_deposit_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int hv_call_deposit_pages(int node, u64 partition_id, u32 num_pages)
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
