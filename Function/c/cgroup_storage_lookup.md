# Function: <code>cgroup_storage_lookup</code>

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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580778384,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580778384,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862896,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862896,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580913920,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580913920,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581061941,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581061008,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, void * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581073136,
      "name": "cgroup_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:67",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073136,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, void * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581088128,
      "name": "cgroup_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:68",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581088128,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, void * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317040,
      "name": "cgroup_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:66",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317040,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, void * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581618624,
      "name": "cgroup_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:67",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581618624,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, void * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582003120,
      "name": "cgroup_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:67",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    },
    {
      "addr": 18446744071582144701,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/bpf_cgrp_storage.c:71",
      "file": "kernel/bpf/bpf_cgrp_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582003120,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, void * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582194256,
      "name": "cgroup_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:67",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    },
    {
      "addr": 18446744071582341901,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/bpf_cgrp_storage.c:64",
      "file": "kernel/bpf/bpf_cgrp_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582194256,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, void * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582343152,
      "name": "cgroup_storage_lookup",
      "external": true,
      "loc": "kernel/bpf/local_storage.c:67",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem",
        "kernel/bpf/cgroup.c:__cgroup_bpf_attach"
      ]
    },
    {
      "addr": 18446744071582508605,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/bpf_cgrp_storage.c:64",
      "file": "kernel/bpf/bpf_cgrp_storage.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem",
        "kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582343152,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492246968,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492246968,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226139944,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226139944,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285474960,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285474960,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272389876,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272389876,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580882720,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882720,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580828784,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580828784,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580873968,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580873968,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
```

```json
{
  "name": "cgroup_storage_lookup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580932544,
      "name": "cgroup_storage_lookup",
      "external": false,
      "loc": "kernel/bpf/local_storage.c:48",
      "file": "kernel/bpf/local_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_get_next_key",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update",
        "kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_update_elem",
        "kernel/bpf/local_storage.c:cgroup_storage_lookup_elem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580932544,
      "name": "cgroup_storage_lookup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
struct bpf_cgroup_storage * cgroup_storage_lookup(struct bpf_cgroup_storage_map * map, struct bpf_cgroup_storage_key * key, bool locked)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_cgroup_storage_key * key</code> ➡️ <code>void * key</code>
</li>
</ul>
</details>
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
