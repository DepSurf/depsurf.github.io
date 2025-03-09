# Function: <code>percpu_rwsem_wait</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore * sem, bool reader)
```

```json
{
  "name": "percpu_rwsem_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579955696,
      "name": "percpu_rwsem_wait",
      "external": false,
      "loc": "kernel/locking/percpu-rwsem.c:139",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955696,
      "name": "percpu_rwsem_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void percpu_rwsem_wait(struct percpu_rw_semaphore * sem, bool reader)
```

```json
{
  "name": "percpu_rwsem_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579943856,
      "name": "percpu_rwsem_wait",
      "external": false,
      "loc": "kernel/locking/percpu-rwsem.c:139",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579943856,
      "name": "percpu_rwsem_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
void percpu_rwsem_wait(struct percpu_rw_semaphore * sem, bool reader)
```

```json
{
  "name": "percpu_rwsem_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579951600,
      "name": "percpu_rwsem_wait",
      "external": false,
      "loc": "kernel/locking/percpu-rwsem.c:139",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579951600,
      "name": "percpu_rwsem_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void percpu_rwsem_wait(struct percpu_rw_semaphore * sem, bool reader)
```

```json
{
  "name": "percpu_rwsem_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080448,
      "name": "percpu_rwsem_wait",
      "external": false,
      "loc": "kernel/locking/percpu-rwsem.c:139",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080448,
      "name": "percpu_rwsem_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 335
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
void percpu_rwsem_wait(struct percpu_rw_semaphore * sem, bool reader)
```

```json
{
  "name": "percpu_rwsem_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580216064,
      "name": "percpu_rwsem_wait",
      "external": false,
      "loc": "kernel/locking/percpu-rwsem.c:141",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580216064,
      "name": "percpu_rwsem_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void percpu_rwsem_wait(struct percpu_rw_semaphore * sem, bool reader)
```

```json
{
  "name": "percpu_rwsem_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409008,
      "name": "percpu_rwsem_wait",
      "external": false,
      "loc": "kernel/locking/percpu-rwsem.c:141",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409008,
      "name": "percpu_rwsem_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void percpu_rwsem_wait(struct percpu_rw_semaphore * sem, bool reader)
```

```json
{
  "name": "percpu_rwsem_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580477776,
      "name": "percpu_rwsem_wait",
      "external": false,
      "loc": "kernel/locking/percpu-rwsem.c:141",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477776,
      "name": "percpu_rwsem_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
void percpu_rwsem_wait(struct percpu_rw_semaphore * sem, bool reader)
```

```json
{
  "name": "percpu_rwsem_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537600,
      "name": "percpu_rwsem_wait",
      "external": false,
      "loc": "kernel/locking/percpu-rwsem.c:141",
      "file": "kernel/locking/percpu-rwsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/locking/percpu-rwsem.c:percpu_down_write",
        "kernel/locking/percpu-rwsem.c:__percpu_down_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537600,
      "name": "percpu_rwsem_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void percpu_rwsem_wait(struct percpu_rw_semaphore * sem, bool reader)
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
