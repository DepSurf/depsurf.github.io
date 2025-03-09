# Function: <code>bpf_cgroup_storage_unlink</code>

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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780640,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:561",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/bpf/cgroup.c:cgroup_bpf_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780640,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865360,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865360,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580916384,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580916384,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063440,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063440,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581072908,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075216,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581087900,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:583",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581090208,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581316812,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:589",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319392,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581618380,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:589",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621552,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582002860,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:588",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582006720,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582193997,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:595",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582197568,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582342893,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:595",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582346512,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492250336,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492250336,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226142824,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226142824,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285479120,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285479120,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272392476,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272392476,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580885184,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580885184,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831248,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831248,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580876432,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876432,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_unlink",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580935072,
      "name": "bpf_cgroup_storage_unlink",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:582",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580935072,
      "name": "bpf_cgroup_storage_unlink",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage * storage)
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
