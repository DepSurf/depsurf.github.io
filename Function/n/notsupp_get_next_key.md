# Function: <code>notsupp_get_next_key</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588621008,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:668",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588621008,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588843040,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:678",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588843040,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589726912,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:682",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589726912,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581078448,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_inode_storage.c:216",
      "file": "kernel/bpf/bpf_inode_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581079520,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_task_storage.c:256",
      "file": "kernel/bpf/bpf_task_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589761584,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:107",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078448,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581079520,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071589761584,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581096672,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_task_storage.c:278",
      "file": "kernel/bpf/bpf_task_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581098096,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_inode_storage.c:216",
      "file": "kernel/bpf/bpf_inode_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589665200,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:107",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581096672,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581098096,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071589665200,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581326080,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_task_storage.c:278",
      "file": "kernel/bpf/bpf_task_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581327504,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_inode_storage.c:216",
      "file": "kernel/bpf/bpf_inode_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590421744,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:107",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581326080,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071581327504,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071590421744,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581630032,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_task_storage.c:284",
      "file": "kernel/bpf/bpf_task_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581631648,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_inode_storage.c:221",
      "file": "kernel/bpf/bpf_inode_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592020560,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:109",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581630032,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071581631648,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071592020560,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582017120,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_task_storage.c:312",
      "file": "kernel/bpf/bpf_task_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582019296,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_inode_storage.c:200",
      "file": "kernel/bpf/bpf_inode_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582144208,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_cgrp_storage.c:152",
      "file": "kernel/bpf/bpf_cgrp_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593836240,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:80",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017120,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582019296,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582144208,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071593836240,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209488,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_task_storage.c:305",
      "file": "kernel/bpf/bpf_task_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582211520,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_inode_storage.c:186",
      "file": "kernel/bpf/bpf_inode_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582341392,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_cgrp_storage.c:145",
      "file": "kernel/bpf/bpf_cgrp_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594210768,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:74",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209488,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582211520,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582341392,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071594210768,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582358576,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_task_storage.c:305",
      "file": "kernel/bpf/bpf_task_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582360608,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_inode_storage.c:186",
      "file": "kernel/bpf/bpf_inode_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582508096,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "kernel/bpf/bpf_cgrp_storage.c:145",
      "file": "kernel/bpf/bpf_cgrp_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595008128,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:74",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582358576,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582360608,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071582508096,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071595008128,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502414992,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:678",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502414992,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235151580,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:678",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235151580,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295967376,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:678",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295967376,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278621996,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:678",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278621996,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588449424,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:678",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588449424,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588162112,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:678",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162112,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588781600,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:678",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588781600,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```

```json
{
  "name": "notsupp_get_next_key",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588922192,
      "name": "notsupp_get_next_key",
      "external": false,
      "loc": "net/core/bpf_sk_storage.c:678",
      "file": "net/core/bpf_sk_storage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922192,
      "name": "notsupp_get_next_key",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int notsupp_get_next_key(struct bpf_map * map, void * key, void * next_key)
```
</details>
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
