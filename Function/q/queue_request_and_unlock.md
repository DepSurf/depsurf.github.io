# Function: <code>queue_request_and_unlock</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583166752,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583166752,
      "name": "queue_request_and_unlock",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583489264,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583489264,
      "name": "queue_request_and_unlock",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583597728,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:225",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:__fuse_request_send",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597728,
      "name": "queue_request_and_unlock",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583620752,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:225",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583620752,
      "name": "queue_request_and_unlock",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583979776,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:225",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583979776,
      "name": "queue_request_and_unlock",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584561680,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:225",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584561680,
      "name": "queue_request_and_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585239136,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:225",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585239136,
      "name": "queue_request_and_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585468704,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:225",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585468704,
      "name": "queue_request_and_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585703728,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:225",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585703728,
      "name": "queue_request_and_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494879656,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494879656,
      "name": "queue_request_and_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228295224,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_retrieve",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228295224,
      "name": "queue_request_and_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288739632,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288739632,
      "name": "queue_request_and_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274196986,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274196986,
      "name": "queue_request_and_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583135488,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583135488,
      "name": "queue_request_and_unlock",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583072640,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583072640,
      "name": "queue_request_and_unlock",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583119520,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583119520,
      "name": "queue_request_and_unlock",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```

```json
{
  "name": "queue_request_and_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583213264,
      "name": "queue_request_and_unlock",
      "external": false,
      "loc": "fs/fuse/dev.c:221",
      "file": "fs/fuse/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_notify",
        "fs/fuse/dev.c:fuse_simple_request",
        "fs/fuse/dev.c:flush_bg_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583213264,
      "name": "queue_request_and_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue * fiq, struct fuse_req * req)
```
</details>
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
