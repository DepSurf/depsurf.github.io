# Function: <code>flush_tlb_local</code>

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
void flush_tlb_local()
```

```json
{
  "name": "flush_tlb_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579412894,
      "name": "flush_tlb_local",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1159",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem",
        "arch/x86/platform/uv/tlb_uv.c:bau_process_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417120,
      "name": "flush_tlb_local",
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
void flush_tlb_local()
```

```json
{
  "name": "flush_tlb_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579413518,
      "name": "flush_tlb_local",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1095",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579417200,
      "name": "flush_tlb_local",
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
void flush_tlb_local()
```

```json
{
  "name": "flush_tlb_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579416366,
      "name": "flush_tlb_local",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1139",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420256,
      "name": "flush_tlb_local",
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
void flush_tlb_local()
```

```json
{
  "name": "flush_tlb_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579479310,
      "name": "flush_tlb_local",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1198",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/mm/mem_encrypt.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483808,
      "name": "flush_tlb_local",
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
void flush_tlb_local()
```

```json
{
  "name": "flush_tlb_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579558071,
      "name": "flush_tlb_local",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1168",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mtrr/generic.c:post_set",
        "arch/x86/kernel/cpu/mtrr/generic.c:prepare_set",
        "arch/x86/mm/mem_encrypt_amd.c:__sme_early_map_unmap_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563024,
      "name": "flush_tlb_local",
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
void flush_tlb_local()
```

```json
{
  "name": "flush_tlb_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579665239,
      "name": "flush_tlb_local",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1192",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:do_flush_tlb_all",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_enable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579670624,
      "name": "flush_tlb_local",
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
void flush_tlb_local()
```

```json
{
  "name": "flush_tlb_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579679376,
      "name": "flush_tlb_local",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1213",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:__flush_tlb_all",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_enable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579684576,
      "name": "flush_tlb_local",
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
void flush_tlb_local()
```

```json
{
  "name": "flush_tlb_local",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579713824,
      "name": "flush_tlb_local",
      "external": true,
      "loc": "arch/x86/mm/tlb.c:1222",
      "file": "arch/x86/mm/tlb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/tlb.c:__flush_tlb_all",
        "arch/x86/mm/tlb.c:flush_tlb_func"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/cacheinfo.c:cache_enable",
        "arch/x86/kernel/cpu/cacheinfo.c:cache_disable",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_unmap_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata",
        "arch/x86/mm/mem_encrypt_amd.c:sme_map_bootdata"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579719088,
      "name": "flush_tlb_local",
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
void flush_tlb_local()
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
