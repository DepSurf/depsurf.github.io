# Function: <code>kmalloc_size_roundup</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
size_t kmalloc_size_roundup(size_t size)
```

```json
{
  "name": "kmalloc_size_roundup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582654725,
      "name": "kmalloc_size_roundup",
      "external": true,
      "loc": "mm/slab_common.c:744",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:push_jmp_history",
        "kernel/bpf/verifier.c:realloc_array",
        "kernel/bpf/verifier.c:copy_array",
        "fs/coredump.c:cn_vprintf",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:devm_kmalloc",
        "drivers/base/devres.c:__devres_alloc_node",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:pskb_carve_inside_nonlinear",
        "net/core/skbuff.c:pskb_carve_inside_header",
        "net/core/skbuff.c:pskb_expand_head",
        "net/core/skbuff.c:__alloc_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596028976,
      "name": "kmalloc_size_roundup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071582654688,
      "name": "kmalloc_size_roundup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 171
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
size_t kmalloc_size_roundup(size_t size)
```

```json
{
  "name": "kmalloc_size_roundup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582862282,
      "name": "kmalloc_size_roundup",
      "external": true,
      "loc": "mm/slab_common.c:741",
      "file": "mm/slab_common.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:push_jmp_history",
        "kernel/bpf/verifier.c:realloc_array",
        "kernel/bpf/verifier.c:copy_array",
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/audit.c:tomoyo_write_log2",
        "security/tomoyo/audit.c:tomoyo_write_log2",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:devm_kmalloc",
        "drivers/base/devres.c:__devres_alloc_node",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:kmalloc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596550769,
      "name": "kmalloc_size_roundup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071582862240,
      "name": "kmalloc_size_roundup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
size_t kmalloc_size_roundup(size_t size)
```

```json
{
  "name": "kmalloc_size_roundup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "kmalloc_size_roundup",
      "external": true,
      "loc": "mm/slab_common.c:695",
      "file": "mm/slab_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:push_jmp_history",
        "kernel/bpf/verifier.c:realloc_array",
        "kernel/bpf/verifier.c:copy_array",
        "fs/coredump.c:cn_vprintf",
        "security/tomoyo/audit.c:tomoyo_write_log2",
        "security/tomoyo/audit.c:tomoyo_write_log2",
        "security/tomoyo/audit.c:tomoyo_init_log",
        "security/tomoyo/common.c:tomoyo_supervisor",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:devm_krealloc",
        "drivers/base/devres.c:devm_kmalloc",
        "drivers/base/devres.c:__devres_alloc_node",
        "drivers/dma-buf/dma-resv.c:dma_resv_list_alloc",
        "net/core/skbuff.c:kmalloc_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597454402,
      "name": "kmalloc_size_roundup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071583034384,
      "name": "kmalloc_size_roundup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
size_t kmalloc_size_roundup(size_t size)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
