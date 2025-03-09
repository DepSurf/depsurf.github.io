# Function: <code>bpf_cgroup_storage_free</code>

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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580780272,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:520",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "kernel/bpf/cgroup.c:cgroup_bpf_put",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580780272,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580864960,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864960,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915984,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915984,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581063056,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581063056,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581073010,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:545",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581074848,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581088002,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:546",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089840,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581316914,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:552",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581319024,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581618482,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:552",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621008,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582002962,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:551",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582006144,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582194099,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:558",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582197024,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582342995,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:558",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_map_free",
        "kernel/bpf/local_storage.c:cgroup_storage_map_free"
      ],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345968,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492249824,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492249824,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226142424,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226142424,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285478560,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285478560,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272392154,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272392154,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580884784,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884784,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580830848,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580830848,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580876032,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876032,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
```

```json
{
  "name": "bpf_cgroup_storage_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934672,
      "name": "bpf_cgroup_storage_free",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:541",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_detach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "kernel/bpf/cgroup.c:cgroup_bpf_release",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run",
        "net/bpf/test_run.c:bpf_test_run"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934672,
      "name": "bpf_cgroup_storage_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void bpf_cgroup_storage_free(struct bpf_cgroup_storage * storage)
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
