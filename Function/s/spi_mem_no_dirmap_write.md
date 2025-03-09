# Function: <code>spi_mem_no_dirmap_write</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586542320,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586790314,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586936570,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587751023,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:465",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
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
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587809759,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:470",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:487",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587689280,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:488",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588279984,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:501",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589663440,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:501",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591273712,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:501",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591628688,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:501",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592361504,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499900896,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232449860,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293226896,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276998668,
      "name": "spi_mem_no_dirmap_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586693594,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586561930,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586891130,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_mem_no_dirmap_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586997514,
      "name": "spi_mem_no_dirmap_write",
      "external": false,
      "loc": "drivers/spi/spi-mem.c:462",
      "file": "drivers/spi/spi-mem.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-mem.c:spi_mem_dirmap_write"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```
</details>
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
ssize_t spi_mem_no_dirmap_write(struct spi_mem_dirmap_desc * desc, u64 offs, size_t len, const void * buf)
```
</details>
</li>
</ul>
