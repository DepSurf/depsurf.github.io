# Function: <code>nvmem_cell_read_common</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int nvmem_cell_read_common(struct device * dev, const char * cell_id, void * val, size_t count)
```

```json
{
  "name": "nvmem_cell_read_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589181040,
      "name": "nvmem_cell_read_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1343",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589181040,
      "name": "nvmem_cell_read_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int nvmem_cell_read_common(struct device * dev, const char * cell_id, void * val, size_t count)
```

```json
{
  "name": "nvmem_cell_read_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178416,
      "name": "nvmem_cell_read_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1521",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178416,
      "name": "nvmem_cell_read_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int nvmem_cell_read_common(struct device * dev, const char * cell_id, void * val, size_t count)
```

```json
{
  "name": "nvmem_cell_read_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589071056,
      "name": "nvmem_cell_read_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1524",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589071056,
      "name": "nvmem_cell_read_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int nvmem_cell_read_common(struct device * dev, const char * cell_id, void * val, size_t count)
```

```json
{
  "name": "nvmem_cell_read_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589789872,
      "name": "nvmem_cell_read_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1536",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589789872,
      "name": "nvmem_cell_read_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
int nvmem_cell_read_common(struct device * dev, const char * cell_id, void * val, size_t count)
```

```json
{
  "name": "nvmem_cell_read_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591304112,
      "name": "nvmem_cell_read_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1566",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591304112,
      "name": "nvmem_cell_read_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int nvmem_cell_read_common(struct device * dev, const char * cell_id, void * val, size_t count)
```

```json
{
  "name": "nvmem_cell_read_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593055616,
      "name": "nvmem_cell_read_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1569",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593055616,
      "name": "nvmem_cell_read_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int nvmem_cell_read_common(struct device * dev, const char * cell_id, void * val, size_t count)
```

```json
{
  "name": "nvmem_cell_read_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593508112,
      "name": "nvmem_cell_read_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1751",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593508112,
      "name": "nvmem_cell_read_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int nvmem_cell_read_common(struct device * dev, const char * cell_id, void * val, size_t count)
```

```json
{
  "name": "nvmem_cell_read_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594252064,
      "name": "nvmem_cell_read_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1794",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_u32",
        "drivers/nvmem/core.c:nvmem_cell_read_u16",
        "drivers/nvmem/core.c:nvmem_cell_read_u8"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594252064,
      "name": "nvmem_cell_read_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
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
int nvmem_cell_read_common(struct device * dev, const char * cell_id, void * val, size_t count)
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
