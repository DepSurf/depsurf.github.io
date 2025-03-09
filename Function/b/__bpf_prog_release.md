# Function: <code>__bpf_prog_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586389104,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:869",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/filter.c:bpf_prog_destroy",
        "net/core/filter.c:sk_attach_filter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586389104,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586828416,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:893",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__reuseport_attach_prog",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586828416,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587015472,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:895",
      "file": "net/core/filter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__reuseport_attach_prog",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015472,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587142832,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:913",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__reuseport_attach_prog",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587142832,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587648288,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:932",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__reuseport_attach_prog",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587648288,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587966656,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1141",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__reuseport_attach_prog",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587966656,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588117920,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588117920,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588436032,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588436032,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588641904,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588641904,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589537341,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1132",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create",
        "net/core/filter.c:bpf_prog_create",
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/filter.c:sk_filter_release_rcu"
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
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589546365,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1162",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:__get_filter",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create_from_user",
        "net/core/filter.c:bpf_prog_create",
        "net/core/filter.c:bpf_prog_create",
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:bpf_migrate_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/filter.c:sk_filter_release_rcu"
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
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589444077,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1162",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/filter.c:sk_filter_release_rcu"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590179021,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1163",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/filter.c:sk_filter_release_rcu"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591741388,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1164",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/filter.c:sk_filter_release_rcu"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593530812,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1166",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/filter.c:sk_filter_release_rcu"
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
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593996412,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1166",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/filter.c:sk_filter_release_rcu"
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
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594780668,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1171",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:bpf_prepare_filter",
        "net/core/filter.c:sk_filter_release_rcu",
        "net/core/filter.c:sk_filter_release_rcu"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502186664,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502186664,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234934484,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234934484,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295665744,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295665744,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278442646,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278442646,
      "name": "__bpf_prog_release",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588248640,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588248640,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587961456,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587961456,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588580464,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588580464,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __bpf_prog_release(struct bpf_prog * prog)
```

```json
{
  "name": "__bpf_prog_release",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588717952,
      "name": "__bpf_prog_release",
      "external": false,
      "loc": "net/core/filter.c:1143",
      "file": "net/core/filter.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/core/filter.c:sk_reuseport_prog_free",
        "net/core/filter.c:sk_reuseport_attach_filter",
        "net/core/filter.c:sk_attach_filter",
        "net/core/filter.c:sk_filter_release_rcu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717952,
      "name": "__bpf_prog_release",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __bpf_prog_release(struct bpf_prog * prog)
```
</details>
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
