# Function: <code>sync_timeline_create</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585318580,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:87",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585406024,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:87",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585834605,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:87",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586081661,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:87",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586225549,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:87",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586469277,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586617117,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct sync_timeline * sync_timeline_create(const char * name)
```

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587412336,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587412336,
      "name": "sync_timeline_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
struct sync_timeline * sync_timeline_create(const char * name)
```

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587481552,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587481552,
      "name": "sync_timeline_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587363613,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587930589,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589284365,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590846061,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct sync_timeline * sync_timeline_create(const char * name)
```

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591187824,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591187824,
      "name": "sync_timeline_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
struct sync_timeline * sync_timeline_create(const char * name)
```

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591533920,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:99",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591533920,
      "name": "sync_timeline_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499506788,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231976996,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292795928,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276718564,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586307597,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586148973,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586565085,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
  "name": "sync_timeline_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586677373,
      "name": "sync_timeline_create",
      "external": false,
      "loc": "drivers/dma-buf/sw_sync.c:78",
      "file": "drivers/dma-buf/sw_sync.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/dma-buf/sw_sync.c:sw_sync_debugfs_open"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct sync_timeline * sync_timeline_create(const char * name)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
struct sync_timeline * sync_timeline_create(const char * name)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
struct sync_timeline * sync_timeline_create(const char * name)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
