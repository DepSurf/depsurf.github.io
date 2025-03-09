# Function: <code>sock_map_unref</code>

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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588223856,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:137",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588223856,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588560912,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588560912,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588777984,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777984,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589652046,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:173",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free"
      ],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_delete_elem",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589652352,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589676590,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:170",
      "file": "net/core/sock_map.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/sock_map.c:sock_hash_free"
      ],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_delete_elem",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589676896,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589658576,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:176",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_delete_elem",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589658576,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590415280,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:179",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_delete_elem",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590415280,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592012768,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:179",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_delete_elem",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592012768,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593827680,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:179",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_delete_elem",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593827680,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594202160,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:175",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_delete_elem",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594202160,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594999536,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:175",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_map_remove_links",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_delete_elem",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594999536,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502345064,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502345064,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235084244,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235084244,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295867360,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295867360,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 560
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278564530,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:sock_map_delete_elem",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278564530,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588384368,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384368,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588097056,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097056,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588716544,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588716544,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void sock_map_unref(struct sock * sk, void * link_raw)
```

```json
{
  "name": "sock_map_unref",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588856864,
      "name": "sock_map_unref",
      "external": false,
      "loc": "net/core/sock_map.c:132",
      "file": "net/core/sock_map.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/sock_map.c:sk_psock_unlink",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_free",
        "net/core/sock_map.c:sock_hash_update_common",
        "net/core/sock_map.c:sock_hash_delete_elem",
        "net/core/sock_map.c:sock_map_update_common",
        "net/core/sock_map.c:__sock_map_delete",
        "net/core/sock_map.c:sock_map_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588856864,
      "name": "sock_map_unref",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void sock_map_unref(struct sock * sk, void * link_raw)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
