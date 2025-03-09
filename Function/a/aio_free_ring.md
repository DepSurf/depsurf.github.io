# Function: <code>aio_free_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317120,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:285",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:free_ioctx",
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:SyS_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317120,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581483856,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:290",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_setup",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581483856,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581564944,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:293",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581564944,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581623200,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:293",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581623200,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767840,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:294",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767840,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581936480,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:288",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581936480,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582021840,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:304",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582021840,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 339
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582159808,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159808,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582236784,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582236784,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582479584,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582479584,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582535264,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:300",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582535264,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582563344,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:300",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582563344,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582880192,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582880192,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583441120,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:328",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583441120,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584031408,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:328",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584031408,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255728,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:328",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255728,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584472528,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:327",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584472528,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493805280,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493805280,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227317580,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227317580,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287423120,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287423120,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273393700,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_setup",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273393700,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 278
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582205520,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582205520,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142432,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142432,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582196000,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196000,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
void aio_free_ring(struct kioctx * ctx)
```

```json
{
  "name": "aio_free_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582271088,
      "name": "aio_free_ring",
      "external": false,
      "loc": "fs/aio.c:301",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:ioctx_alloc",
        "fs/aio.c:free_ioctx",
        "fs/aio.c:aio_setup_ring",
        "fs/aio.c:aio_setup_ring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582271088,
      "name": "aio_free_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 331
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
