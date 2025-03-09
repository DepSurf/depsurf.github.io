# Function: <code>__htab_percpu_map_update_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580444272,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:574",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580444272,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 893
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580501312,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:778",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501312,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 713
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580529760,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:873",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580529760,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580593312,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:906",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580593312,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580689088,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:926",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580689088,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760720,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:940",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760720,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845968,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845968,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580897008,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897008,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581040736,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1083",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581040736,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050928,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1135",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050928,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581065776,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1135",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581065776,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581297952,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1188",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581297952,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581595296,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1207",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581595296,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581967072,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1229",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581967072,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 498
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
long int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582157072,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1242",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582157072,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 607
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
long int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582308160,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:1261",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308160,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492225032,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492225032,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226121792,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226121792,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285448832,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285448832,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1012
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272372466,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272372466,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865808,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865808,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811936,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811936,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857056,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857056,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```

```json
{
  "name": "__htab_percpu_map_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915424,
      "name": "__htab_percpu_map_update_elem",
      "external": false,
      "loc": "kernel/bpf/hashtab.c:975",
      "file": "kernel/bpf/hashtab.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/hashtab.c:bpf_percpu_hash_update",
        "kernel/bpf/hashtab.c:htab_percpu_map_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915424,
      "name": "__htab_percpu_map_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 719
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __htab_percpu_map_update_elem(struct bpf_map * map, void * key, void * value, u64 map_flags, bool onallcpus)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
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
