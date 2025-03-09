# Function: <code>htab_map_lookup_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580383792,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:141",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580383792,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580446016,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:316",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580446016,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580499648,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:408",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580499648,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580528445,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:461",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580528384,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580591997,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:470",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580591936,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580687813,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:480",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687760,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580758997,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:494",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580758800,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580844293,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580844096,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580895333,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895136,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581044965,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:594",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581044736,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581055488,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:612",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055360,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581070464,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:612",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581070096,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581294000,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:643",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581293760,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581592432,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:659",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581592288,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581971680,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:674",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581971376,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582162480,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:681",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582162160,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582305488,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:692",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582305024,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492223020,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492222744,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226120268,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226120048,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285446448,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285446064,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272370600,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272370340,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580864133,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580863936,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580810261,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580810064,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580855381,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855184,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
void * htab_map_lookup_elem(struct bpf_map * map, void * key)
```

```json
{
  "name": "htab_map_lookup_elem",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580913733,
      "name": "htab_map_lookup_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:482",
      "file": "kernel/bpf/hashtab.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/hashtab.c:htab_of_map_lookup_elem",
        "kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem",
        "kernel/bpf/hashtab.c:htab_map_seq_show_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913520,
      "name": "htab_map_lookup_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
