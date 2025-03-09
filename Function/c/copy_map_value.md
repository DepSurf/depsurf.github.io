# Function: <code>copy_map_value</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580765431,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:119",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580837814,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:119",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580841505,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:119",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580852215,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:119",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580816401,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580888838,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580892545,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580903255,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588846872,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580938864,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:153",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581028038,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:153",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581043348,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:153",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581048135,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:153",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589729085,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:153",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580935679,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:195",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581035190,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:195",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581052335,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:195",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581059464,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:195",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589764141,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:195",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580938383,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:206",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581046774,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:206",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581067853,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:206",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581074600,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:206",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589668509,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:206",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
void copy_map_value(struct bpf_map * map, void * dst, void * src)
```

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126304,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:215",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    },
    {
      "addr": 18446744071581268704,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:215",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ]
    },
    {
      "addr": 18446744071581285056,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:215",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    },
    {
      "addr": 18446744071581301392,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:215",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ]
    },
    {
      "addr": 18446744071590421920,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:215",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126304,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071581268704,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071581285056,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071581301392,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    },
    {
      "addr": 18446744071590421920,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
void copy_map_value(struct bpf_map * map, void * dst, void * src)
```

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397792,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:277",
      "file": "kernel/bpf/syscall.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ]
    },
    {
      "addr": 18446744071581560624,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:277",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ]
    },
    {
      "addr": 18446744071581581216,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:277",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ]
    },
    {
      "addr": 18446744071581599488,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:277",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ]
    },
    {
      "addr": 18446744071592020736,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:277",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397792,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071581560624,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071581581216,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071581599488,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071592020736,
      "name": "copy_map_value",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581773874,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:403",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581936717,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:403",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581974879,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:403",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581981200,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:403",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582013432,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:403",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593839939,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:403",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581936144,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:457",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582120333,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:457",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582165472,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:457",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582172688,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:457",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582204340,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:457",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071594214498,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:457",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582062729,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:488",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:bpf_map_copy_value"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582260861,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:488",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582314006,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:488",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_lru_map_update_elem",
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582321488,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:488",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem",
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582353572,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:488",
      "file": "kernel/bpf/bpf_local_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_local_storage.c:bpf_selem_alloc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595011874,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:488",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:diag_get",
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492138640,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492214812,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492221384,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336492232448,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336502420388,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226035844,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226112016,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 3226117568,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3226128224,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 3235155448,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285346156,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285436340,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285442352,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055285457924,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055295973168,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272302574,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272362890,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272366618,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936272378828,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936278625550,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580785201,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580857638,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580861345,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580872055,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588453256,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580731377,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580803785,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580807473,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580818183,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588165944,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580776449,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580848886,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580852593,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580863303,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588785432,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "copy_map_value",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580834756,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:map_lookup_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580907181,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/helpers.c:copy_map_value_locked"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580910929,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/hashtab.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:alloc_htab_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580921831,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "kernel/bpf/arraymap.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/arraymap.c:array_map_update_elem"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588926077,
      "name": "copy_map_value",
      "external": false,
      "loc": "include/linux/bpf.h:122",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "net/core/bpf_sk_storage.c:bpf_sk_storage_clone"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void copy_map_value(struct bpf_map * map, void * dst, void * src)
```
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void copy_map_value(struct bpf_map * map, void * dst, void * src)
```
</details>
</li>
</ul>
