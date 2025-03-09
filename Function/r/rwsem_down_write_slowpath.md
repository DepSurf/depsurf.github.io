# Function: <code>rwsem_down_write_slowpath</code>

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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579861536,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1127",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579861536,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579910224,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1139",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579910224,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579954272,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1136",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579954272,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1169
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579942512,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1016",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579942512,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1096
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579950224,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1016",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579950224,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1133
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1058",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580079232,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
    },
    {
      "addr": 18446744071592121768,
      "name": "rwsem_down_write_slowpath.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594726944,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1108",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594726944,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1455
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596478480,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1115",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596478480,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1424
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597020112,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1107",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597020112,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1359
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597949456,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1107",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597949456,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1359
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491112568,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1139",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491112568,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1452
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225115516,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1139",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225115516,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1252
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284004384,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1139",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284004384,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1724
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271690754,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1139",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271690754,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579882336,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1139",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579882336,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579817328,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1139",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579817328,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1203
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870496,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1139",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870496,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1231
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_write_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579915952,
      "name": "rwsem_down_write_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1139",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_write_killable",
        "kernel/locking/rwsem.c:down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579915952,
      "name": "rwsem_down_write_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1283
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
struct rw_semaphore * rwsem_down_write_slowpath(struct rw_semaphore * sem, int state)
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
