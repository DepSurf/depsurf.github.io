# Function: <code>rwsem_down_read_slowpath</code>

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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589965696,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:983",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589965696,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1175
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590193360,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:995",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590193360,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1175
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591209456,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:992",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591209456,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1090
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, long int count, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591704752,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:892",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read_interruptible",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591704752,
      "name": "rwsem_down_read_slowpath",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, long int count, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591646944,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:892",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read_interruptible",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591646944,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 925
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, long int count, unsigned int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592820480,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:938",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read_interruptible",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592820480,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 890
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, long int count, unsigned int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594725248,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:997",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read_interruptible",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594725248,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1201
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, long int count, unsigned int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596476576,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:1004",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read_interruptible",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596476576,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1223
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, long int count, unsigned int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597018160,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:996",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read_interruptible",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597018160,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1226
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, long int count, unsigned int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597947504,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:996",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read_interruptible",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597947504,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1226
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503938512,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:995",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503938512,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1356
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236548256,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:995",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236548256,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1292
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297791072,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:995",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297791072,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1628
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279804912,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:995",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279804912,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589795648,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:995",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589795648,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1175
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589518128,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:995",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589518128,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1145
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590239056,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:995",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590239056,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1175
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
```

```json
{
  "name": "rwsem_down_read_slowpath",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590289408,
      "name": "rwsem_down_read_slowpath",
      "external": false,
      "loc": "kernel/locking/rwsem.c:995",
      "file": "kernel/locking/rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/rwsem.c:down_read_killable",
        "kernel/locking/rwsem.c:down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590289408,
      "name": "rwsem_down_read_slowpath",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1218
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
struct rw_semaphore * rwsem_down_read_slowpath(struct rw_semaphore * sem, int state)
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int count</code>
</li>
<li>
<b>Param reordered. </b>
<code>sem, state</code> ➡️ <code>sem, count, state</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int state</code> ➡️ <code>unsigned int state</code>
</li>
</ul>
</details>
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
