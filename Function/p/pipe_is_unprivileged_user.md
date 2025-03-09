# Function: <code>pipe_is_unprivileged_user</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pipe_is_unprivileged_user()
```

```json
{
  "name": "pipe_is_unprivileged_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582124763,
      "name": "pipe_is_unprivileged_user",
      "external": true,
      "loc": "fs/pipe.c:761",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120512,
      "name": "pipe_is_unprivileged_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pipe_is_unprivileged_user()
```

```json
{
  "name": "pipe_is_unprivileged_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582171197,
      "name": "pipe_is_unprivileged_user",
      "external": true,
      "loc": "fs/pipe.c:761",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582166912,
      "name": "pipe_is_unprivileged_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pipe_is_unprivileged_user()
```

```json
{
  "name": "pipe_is_unprivileged_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582195837,
      "name": "pipe_is_unprivileged_user",
      "external": true,
      "loc": "fs/pipe.c:775",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582191504,
      "name": "pipe_is_unprivileged_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pipe_is_unprivileged_user()
```

```json
{
  "name": "pipe_is_unprivileged_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582513165,
      "name": "pipe_is_unprivileged_user",
      "external": true,
      "loc": "fs/pipe.c:776",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582508816,
      "name": "pipe_is_unprivileged_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pipe_is_unprivileged_user()
```

```json
{
  "name": "pipe_is_unprivileged_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583037814,
      "name": "pipe_is_unprivileged_user",
      "external": true,
      "loc": "fs/pipe.c:777",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033248,
      "name": "pipe_is_unprivileged_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool pipe_is_unprivileged_user()
```

```json
{
  "name": "pipe_is_unprivileged_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583602550,
      "name": "pipe_is_unprivileged_user",
      "external": true,
      "loc": "fs/pipe.c:777",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597712,
      "name": "pipe_is_unprivileged_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool pipe_is_unprivileged_user()
```

```json
{
  "name": "pipe_is_unprivileged_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583819428,
      "name": "pipe_is_unprivileged_user",
      "external": true,
      "loc": "fs/pipe.c:779",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583814560,
      "name": "pipe_is_unprivileged_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool pipe_is_unprivileged_user()
```

```json
{
  "name": "pipe_is_unprivileged_user",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584025408,
      "name": "pipe_is_unprivileged_user",
      "external": true,
      "loc": "fs/pipe.c:795",
      "file": "fs/pipe.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/pipe.c:pipe_fcntl",
        "fs/pipe.c:alloc_pipe_info",
        "fs/pipe.c:alloc_pipe_info"
      ],
      "caller_func": [
        "kernel/watch_queue.c:watch_queue_set_size"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584020544,
      "name": "pipe_is_unprivileged_user",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
bool pipe_is_unprivileged_user()
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
