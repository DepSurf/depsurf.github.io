# Function: <code>sock_hash_lookup_elem_raw</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588222912,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:540",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588222912,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588559936,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:544",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588559936,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588777008,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:552",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777008,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589649920,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:730",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589649920,
      "name": "sock_hash_lookup_elem_raw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589674480,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:870",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674480,
      "name": "sock_hash_lookup_elem_raw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589656832,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:862",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589656832,
      "name": "sock_hash_lookup_elem_raw.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct bpf_shtab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590412400,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:853",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590412400,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
struct bpf_shtab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592009360,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:855",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592009360,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
struct bpf_shtab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593823712,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:857",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593823712,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
struct bpf_shtab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594198272,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:862",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594198272,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
struct bpf_shtab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594995488,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:866",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594995488,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502343672,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:552",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502343672,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235083236,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:552",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235083236,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295867008,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:552",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295867008,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278565192,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:552",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278565192,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588383392,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:552",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588383392,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588096080,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:552",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588096080,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588715568,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:552",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588715568,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```

```json
{
  "name": "sock_hash_lookup_elem_raw",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588855888,
      "name": "sock_hash_lookup_elem_raw",
      "external": false,
      "loc": "net/core/sock_map.c:552",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_get_next_key",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:__sock_hash_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588855888,
      "name": "sock_hash_lookup_elem_raw",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct bpf_htab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
struct bpf_shtab_elem * sock_hash_lookup_elem_raw(struct hlist_head * head, u32 hash, void * key, u32 key_size)
```
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
