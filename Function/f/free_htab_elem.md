# Function: <code>free_htab_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580445200,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:407",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580445200,
      "name": "free_htab_elem.constprop.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580497776,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:539",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580497776,
      "name": "free_htab_elem.constprop.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580526048,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:618",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580526048,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580589552,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:650",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580589552,
      "name": "free_htab_elem",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580685200,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:664",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    },
    {
      "addr": 18446744071580746530,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/sockmap.c:287",
      "file": "kernel/bpf/sockmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/sockmap.c:sock_hash_delete_elem",
        "kernel/bpf/sockmap.c:sock_hash_free",
        "kernel/bpf/sockmap.c:bpf_tcp_close"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685200,
      "name": "free_htab_elem",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580756976,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580756976,
      "name": "free_htab_elem",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580840768,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580840768,
      "name": "free_htab_elem",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580891808,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580891808,
      "name": "free_htab_elem",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581041104,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:793",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041104,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581048032,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:814",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581048032,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581063584,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:814",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063584,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581289152,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:855",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581289152,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581584992,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:874",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581584992,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
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
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581963648,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:903",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581963648,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582152032,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:918",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152032,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
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
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582301168,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:934",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch",
        "kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582301168,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492220512,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492220512,
      "name": "free_htab_elem",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226116676,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226116676,
      "name": "free_htab_elem",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285441200,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285441200,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272365930,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272365930,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580860608,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580860608,
      "name": "free_htab_elem",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580806736,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806736,
      "name": "free_htab_elem",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580851856,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580851856,
      "name": "free_htab_elem",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```

```json
{
  "name": "free_htab_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580910176,
      "name": "free_htab_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:678",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:htab_map_delete_elem",
        "kernel/bpf/hashtab.c:htab_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910176,
      "name": "free_htab_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void free_htab_elem(struct bpf_htab * htab, struct htab_elem * l)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
