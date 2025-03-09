# Function: <code>io_submit_state_end</code>

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
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582176144,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2185",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582176144,
      "name": "io_submit_state_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582253840,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582253840,
      "name": "io_submit_state_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582550982,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:5930",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_submit_sqes"
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
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582619740,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:6734",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_submit_sqes"
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
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582649060,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:6676",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_submit_sqes"
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
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582972628,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:7260",
      "file": "fs/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/io_uring.c:io_submit_sqes"
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
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586013769,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "io_uring/io_uring.c:8561",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586780867,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "io_uring/io_uring.c:2297",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587047760,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "io_uring/io_uring.c:2321",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587322986,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "io_uring/io_uring.c:2349",
      "file": "io_uring/io_uring.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "io_uring/io_uring.c:io_submit_sqes"
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
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493827144,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493827144,
      "name": "io_submit_state_end",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227330464,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227330464,
      "name": "io_submit_state_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287446416,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287446416,
      "name": "io_submit_state_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273402704,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273402704,
      "name": "io_submit_state_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582222576,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582222576,
      "name": "io_submit_state_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582160416,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582160416,
      "name": "io_submit_state_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582213056,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582213056,
      "name": "io_submit_state_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void io_submit_state_end(struct io_submit_state * state)
```

```json
{
  "name": "io_submit_state_end",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582291088,
      "name": "io_submit_state_end",
      "external": false,
      "loc": "fs/io_uring.c:2590",
      "file": "fs/io_uring.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/io_uring.c:io_ring_submit",
        "fs/io_uring.c:io_submit_sqes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291088,
      "name": "io_submit_state_end",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void io_submit_state_end(struct io_submit_state * state)
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
void io_submit_state_end(struct io_submit_state * state)
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
