# Function: <code>bpf_obj_memcpy</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bpf_obj_memcpy(struct btf_field_offs * foffs, void * dst, void * src, u32 size, bool long_memcpy)
```

```json
{
  "name": "bpf_obj_memcpy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581751632,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:378",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    },
    {
      "addr": 18446744071581935776,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:378",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ]
    },
    {
      "addr": 18446744071581960368,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:378",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    },
    {
      "addr": 18446744071581980768,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:378",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "kernel/bpf/arraymap.c:bpf_percpu_array_update",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/arraymap.c:bpf_percpu_array_copy"
      ]
    },
    {
      "addr": 18446744071582013072,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:378",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_selem_alloc"
      ]
    },
    {
      "addr": 18446744071593838352,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:378",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581751632,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581935776,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581960368,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071581980768,
      "name": "bpf_obj_memcpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071582013072,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    },
    {
      "addr": 18446744071593838352,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bpf_obj_memcpy(struct btf_record * rec, void * dst, void * src, u32 size, bool long_memcpy)
```

```json
{
  "name": "bpf_obj_memcpy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581911664,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:432",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    },
    {
      "addr": 18446744071582119104,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:432",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ]
    },
    {
      "addr": 18446744071582148208,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:432",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:__bpf_hash_map_seq_show",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    },
    {
      "addr": 18446744071582172336,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:432",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "kernel/bpf/arraymap.c:bpf_percpu_array_update",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/arraymap.c:bpf_percpu_array_copy"
      ]
    },
    {
      "addr": 18446744071582203904,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:432",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_selem_alloc"
      ]
    },
    {
      "addr": 18446744071594212912,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:432",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911664,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071582119104,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071582148208,
      "name": "bpf_obj_memcpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071582172336,
      "name": "bpf_obj_memcpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071582203904,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071594212912,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
void bpf_obj_memcpy(struct btf_record * rec, void * dst, void * src, u32 size, bool long_memcpy)
```

```json
{
  "name": "bpf_obj_memcpy",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582036512,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:463",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    },
    {
      "addr": 18446744071582259440,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:463",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ]
    },
    {
      "addr": 18446744071582297264,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:463",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_copy",
        "kernel/bpf/hashtab.c:__bpf_hash_map_seq_show",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    },
    {
      "addr": 18446744071582321136,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:463",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:__bpf_array_map_seq_show",
        "kernel/bpf/arraymap.c:bpf_percpu_array_update",
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/arraymap.c:bpf_percpu_array_copy"
      ]
    },
    {
      "addr": 18446744071582353136,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:463",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_local_storage.c:bpf_selem_alloc"
      ]
    },
    {
      "addr": 18446744071595010272,
      "name": "bpf_obj_memcpy",
      "external": false,
      "loc": "include/linux/bpf.h:463",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582036512,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071582259440,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071582297264,
      "name": "bpf_obj_memcpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071582321136,
      "name": "bpf_obj_memcpy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 229
    },
    {
      "addr": 18446744071582353136,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
    },
    {
      "addr": 18446744071595010272,
      "name": "bpf_obj_memcpy.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
void bpf_obj_memcpy(struct btf_field_offs * foffs, void * dst, void * src, u32 size, bool long_memcpy)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct btf_record * rec</code>
</li>
<li>
<b>Param removed. </b>
<code>struct btf_field_offs * foffs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
