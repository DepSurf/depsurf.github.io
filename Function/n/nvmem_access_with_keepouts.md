# Function: <code>nvmem_access_with_keepouts</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int nvmem_access_with_keepouts(struct nvmem_device * nvmem, unsigned int offset, void * val, size_t bytes, int write)
```

```json
{
  "name": "nvmem_access_with_keepouts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589174336,
      "name": "nvmem_access_with_keepouts",
      "external": false,
      "loc": "drivers/nvmem/core.c:95",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_read",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589174336,
      "name": "nvmem_access_with_keepouts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
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
int nvmem_access_with_keepouts(struct nvmem_device * nvmem, unsigned int offset, void * val, size_t bytes, int write)
```

```json
{
  "name": "nvmem_access_with_keepouts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589067664,
      "name": "nvmem_access_with_keepouts",
      "external": false,
      "loc": "drivers/nvmem/core.c:95",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_read",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589067664,
      "name": "nvmem_access_with_keepouts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int nvmem_access_with_keepouts(struct nvmem_device * nvmem, unsigned int offset, void * val, size_t bytes, int write)
```

```json
{
  "name": "nvmem_access_with_keepouts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589786240,
      "name": "nvmem_access_with_keepouts",
      "external": false,
      "loc": "drivers/nvmem/core.c:95",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_read",
        "drivers/nvmem/core.c:nvmem_cell_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589786240,
      "name": "nvmem_access_with_keepouts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
int nvmem_access_with_keepouts(struct nvmem_device * nvmem, unsigned int offset, void * val, size_t bytes, int write)
```

```json
{
  "name": "nvmem_access_with_keepouts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591298160,
      "name": "nvmem_access_with_keepouts",
      "external": false,
      "loc": "drivers/nvmem/core.c:100",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_read",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591298160,
      "name": "nvmem_access_with_keepouts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int nvmem_access_with_keepouts(struct nvmem_device * nvmem, unsigned int offset, void * val, size_t bytes, int write)
```

```json
{
  "name": "nvmem_access_with_keepouts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593049104,
      "name": "nvmem_access_with_keepouts",
      "external": false,
      "loc": "drivers/nvmem/core.c:100",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_read",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593049104,
      "name": "nvmem_access_with_keepouts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int nvmem_access_with_keepouts(struct nvmem_device * nvmem, unsigned int offset, void * val, size_t bytes, int write)
```

```json
{
  "name": "nvmem_access_with_keepouts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593501312,
      "name": "nvmem_access_with_keepouts",
      "external": false,
      "loc": "drivers/nvmem/core.c:108",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_read",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593501312,
      "name": "nvmem_access_with_keepouts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
int nvmem_access_with_keepouts(struct nvmem_device * nvmem, unsigned int offset, void * val, size_t bytes, int write)
```

```json
{
  "name": "nvmem_access_with_keepouts",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594247856,
      "name": "nvmem_access_with_keepouts",
      "external": false,
      "loc": "drivers/nvmem/core.c:82",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_write",
        "drivers/nvmem/core.c:nvmem_device_read",
        "drivers/nvmem/core.c:__nvmem_cell_entry_write",
        "drivers/nvmem/core.c:bin_attr_nvmem_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594247856,
      "name": "nvmem_access_with_keepouts",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int nvmem_access_with_keepouts(struct nvmem_device * nvmem, unsigned int offset, void * val, size_t bytes, int write)
```
</details>
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
