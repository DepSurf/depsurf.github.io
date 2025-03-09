# Function: <code>mq_create_mount</code>

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
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583202016,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:395",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583202016,
      "name": "mq_create_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583307792,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583307792,
      "name": "mq_create_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583648959,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:454",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:mq_init_ns"
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
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583770143,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:454",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:mq_init_ns"
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
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583794319,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:454",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:mq_init_ns"
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
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584156863,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:457",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:mq_init_ns"
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
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584755391,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:468",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:mq_init_ns"
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
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585450527,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:468",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:mq_init_ns"
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
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585681791,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:468",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:mq_init_ns"
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
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585928607,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:468",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:mq_init_ns"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495047208,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495047208,
      "name": "mq_create_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228452340,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228452340,
      "name": "mq_create_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288947008,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288947008,
      "name": "mq_create_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
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
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274319498,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274319498,
      "name": "mq_create_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583276528,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583276528,
      "name": "mq_create_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213664,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213664,
      "name": "mq_create_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583260560,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260560,
      "name": "mq_create_mount",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```

```json
{
  "name": "mq_create_mount",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583364192,
      "name": "mq_create_mount",
      "external": false,
      "loc": "ipc/mqueue.c:394",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:init_mqueue_fs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583364192,
      "name": "mq_create_mount",
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct vfsmount * mq_create_mount(struct ipc_namespace * ns)
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
