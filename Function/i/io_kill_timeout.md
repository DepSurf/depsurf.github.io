# Function: <code>io_kill_timeout</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582271531,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258304,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582536809,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:1130",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582522768,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582583313,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:1597",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_flush_timeouts",
        "fs/io_uring.c:io_flush_timeouts",
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_kill_timeouts"
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
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582609794,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:1304",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_commit_cqring",
        "fs/io_uring.c:io_commit_cqring"
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
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582932312,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:1514",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:io_kill_timeouts",
        "fs/io_uring.c:__io_commit_cqring_flush",
        "fs/io_uring.c:__io_commit_cqring_flush"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void io_kill_timeout(struct io_kiocb * req, int status)
```

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594113695,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "io_uring/io_uring.c:1888",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "io_uring/io_uring.c:io_kill_timeouts",
        "io_uring/io_uring.c:__io_commit_cqring_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594113695,
      "name": "io_kill_timeout",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586815801,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "io_uring/timeout.c:52",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_kill_timeouts",
        "io_uring/timeout.c:io_kill_timeouts",
        "io_uring/timeout.c:io_flush_timeouts",
        "io_uring/timeout.c:io_flush_timeouts"
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
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587082236,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "io_uring/timeout.c:92",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_kill_timeouts",
        "io_uring/timeout.c:io_flush_timeouts",
        "io_uring/timeout.c:io_flush_timeouts"
      ],
      "caller_func": [
        "io_uring/timeout.c:io_kill_timeouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077888,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587361516,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "io_uring/timeout.c:92",
      "file": "io_uring/timeout.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/timeout.c:io_kill_timeouts",
        "io_uring/timeout.c:io_flush_timeouts",
        "io_uring/timeout.c:io_flush_timeouts"
      ],
      "caller_func": [
        "io_uring/timeout.c:io_kill_timeouts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357168,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493837240,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493831456,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227345084,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227333812,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287469152,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287451904,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273417176,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273405960,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582240267,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227040,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582178011,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164880,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582230747,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217520,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_kill_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582309019,
      "name": "io_kill_timeout",
      "external": false,
      "loc": "fs/io_uring.c:507",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ],
      "caller_func": [
        "fs/io_uring.c:io_ring_ctx_wait_and_kill",
        "fs/io_uring.c:io_commit_cqring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582296240,
      "name": "io_kill_timeout.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void io_kill_timeout(struct io_kiocb * req, int status)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void io_kill_timeout(struct io_kiocb * req, int status)
```
</details>
</li>
</ul>
