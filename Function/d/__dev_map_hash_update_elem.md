# Function: <code>__dev_map_hash_update_elem</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580939635,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:664",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __dev_map_hash_update_elem(struct net * net, struct bpf_map * map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:692",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102928,
      "name": "__dev_map_hash_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
    },
    {
      "addr": 18446744071581104573,
      "name": "__dev_map_hash_update_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int __dev_map_hash_update_elem(struct net * net, struct bpf_map * map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:678",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581130400,
      "name": "__dev_map_hash_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 558
    },
    {
      "addr": 18446744071591323130,
      "name": "__dev_map_hash_update_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __dev_map_hash_update_elem(struct net * net, struct bpf_map * map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:671",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581147808,
      "name": "__dev_map_hash_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    },
    {
      "addr": 18446744071591265018,
      "name": "__dev_map_hash_update_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __dev_map_hash_update_elem(struct net * net, struct bpf_map * map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:943",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581381872,
      "name": "__dev_map_hash_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 538
    },
    {
      "addr": 18446744071592187353,
      "name": "__dev_map_hash_update_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __dev_map_hash_update_elem(struct net * net, struct bpf_map * map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:935",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581704496,
      "name": "__dev_map_hash_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071593961981,
      "name": "__dev_map_hash_update_elem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 12
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
int __dev_map_hash_update_elem(struct net * net, struct bpf_map * map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582110896,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:935",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582110896,
      "name": "__dev_map_hash_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 562
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
long int __dev_map_hash_update_elem(struct net * net, struct bpf_map * map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582307008,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:946",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582307008,
      "name": "__dev_map_hash_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
long int __dev_map_hash_update_elem(struct net * net, struct bpf_map * map, void * key, void * value, u64 map_flags)
```

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582468064,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:954",
      "file": "kernel/bpf/devmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582468064,
      "name": "__dev_map_hash_update_elem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 557
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492282692,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:664",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
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
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226168208,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:664",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
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
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285513112,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:664",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
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
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272414834,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:664",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
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
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580908435,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:664",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
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
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580854499,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:664",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
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
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580899683,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:664",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
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
  "name": "__dev_map_hash_update_elem",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580958403,
      "name": "__dev_map_hash_update_elem",
      "external": false,
      "loc": "kernel/bpf/devmap.c:664",
      "file": "kernel/bpf/devmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/devmap.c:dev_map_hash_update_elem"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __dev_map_hash_update_elem(struct net * net, struct bpf_map * map, void * key, void * value, u64 map_flags)
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
