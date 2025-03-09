# Function: <code>aio_setup_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581321974,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:436",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_setup"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581486128,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:441",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581486128,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581568576,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:444",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581568576,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623600,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:444",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623600,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1030
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768304,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:453",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768304,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1023
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936960,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:447",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936960,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1054
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582022320,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:463",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582022320,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 963
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582171808,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171808,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582249200,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582249200,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480128,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480128,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1057
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582535776,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:462",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535776,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1094
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582563856,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:459",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563856,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1088
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880704,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880704,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1094
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446128,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:487",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446128,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1082
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584032096,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:491",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584032096,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1082
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584256400,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:491",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584256400,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1054
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584473184,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:490",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473184,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1055
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493805752,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493805752,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227321336,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227321336,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 940
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287439280,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287439280,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1236
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273394132,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273394132,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217936,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217936,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155776,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155776,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582208416,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582208416,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int aio_setup_ring(struct kioctx * ctx, unsigned int nr_events)
```

```json
{
  "name": "aio_setup_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582286224,
      "name": "aio_setup_ring",
      "external": false,
      "loc": "fs/aio.c:460",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582286224,
      "name": "aio_setup_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1009
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int aio_setup_ring(struct kioctx * ctx)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_events</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
