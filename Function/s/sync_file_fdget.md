# Function: <code>sync_file_fdget</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585125979,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:107",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585313664,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:100",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585313664,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585401696,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:87",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585401696,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585831136,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:87",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585831136,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586078192,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:87",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586078192,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586222464,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:87",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586222464,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586466096,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466096,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586613984,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586613984,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587410562,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
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
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587479554,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl_merge",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
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
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587362240,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
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
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587929184,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
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
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589282237,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:79",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
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
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590843693,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:79",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
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
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591185775,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:79",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
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
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591532137,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:79",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499502504,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499502504,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231973024,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231973024,
      "name": "sync_file_fdget",
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292790144,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292790144,
      "name": "sync_file_fdget",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276715430,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276715430,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586304464,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586304464,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586145840,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586145840,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586561952,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586561952,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
struct sync_file * sync_file_fdget(int fd)
```

```json
{
  "name": "sync_file_fdget",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586674240,
      "name": "sync_file_fdget",
      "external": false,
      "loc": "drivers/dma-buf/sync_file.c:78",
      "file": "drivers/dma-buf/sync_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sync_file.c:sync_file_ioctl",
        "drivers/dma-buf/sync_file.c:sync_file_get_fence"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674240,
      "name": "sync_file_fdget",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct sync_file * sync_file_fdget(int fd)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct sync_file * sync_file_fdget(int fd)
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
