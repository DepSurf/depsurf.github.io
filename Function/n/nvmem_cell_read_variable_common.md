# Function: <code>nvmem_cell_read_variable_common</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void * nvmem_cell_read_variable_common(struct device * dev, const char * cell_id, size_t max_len, size_t * len)
```

```json
{
  "name": "nvmem_cell_read_variable_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589071536,
      "name": "nvmem_cell_read_variable_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1612",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589071536,
      "name": "nvmem_cell_read_variable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
const void * nvmem_cell_read_variable_common(struct device * dev, const char * cell_id, size_t max_len, size_t * len)
```

```json
{
  "name": "nvmem_cell_read_variable_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589790352,
      "name": "nvmem_cell_read_variable_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1624",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589790352,
      "name": "nvmem_cell_read_variable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
const void * nvmem_cell_read_variable_common(struct device * dev, const char * cell_id, size_t max_len, size_t * len)
```

```json
{
  "name": "nvmem_cell_read_variable_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591303360,
      "name": "nvmem_cell_read_variable_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1654",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591303360,
      "name": "nvmem_cell_read_variable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
const void * nvmem_cell_read_variable_common(struct device * dev, const char * cell_id, size_t max_len, size_t * len)
```

```json
{
  "name": "nvmem_cell_read_variable_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593054800,
      "name": "nvmem_cell_read_variable_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1657",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593054800,
      "name": "nvmem_cell_read_variable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
const void * nvmem_cell_read_variable_common(struct device * dev, const char * cell_id, size_t max_len, size_t * len)
```

```json
{
  "name": "nvmem_cell_read_variable_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593506944,
      "name": "nvmem_cell_read_variable_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1839",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593506944,
      "name": "nvmem_cell_read_variable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
const void * nvmem_cell_read_variable_common(struct device * dev, const char * cell_id, size_t max_len, size_t * len)
```

```json
{
  "name": "nvmem_cell_read_variable_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594251424,
      "name": "nvmem_cell_read_variable_common",
      "external": false,
      "loc": "drivers/nvmem/core.c:1882",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64",
        "drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594251424,
      "name": "nvmem_cell_read_variable_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void * nvmem_cell_read_variable_common(struct device * dev, const char * cell_id, size_t max_len, size_t * len)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>const void *</code>
</li>
</ul>
</details>
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
