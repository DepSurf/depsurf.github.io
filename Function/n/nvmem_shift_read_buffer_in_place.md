# Function: <code>nvmem_shift_read_buffer_in_place</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586862790,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:948",
      "file": "drivers/nvmem/core.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587350585,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:951",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587653913,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1024",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587784601,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1160",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588088923,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:910",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588294747,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:907",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589175369,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1167",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void nvmem_shift_read_buffer_in_place(struct nvmem_cell * cell, void * buf)
```

```json
{
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589170560,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1345",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_cell_read",
        "drivers/nvmem/core.c:nvmem_cell_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589170560,
      "name": "nvmem_shift_read_buffer_in_place",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
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
void nvmem_shift_read_buffer_in_place(struct nvmem_cell * cell, void * buf)
```

```json
{
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589064416,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1348",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_cell_read",
        "drivers/nvmem/core.c:nvmem_cell_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589064416,
      "name": "nvmem_shift_read_buffer_in_place",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void nvmem_shift_read_buffer_in_place(struct nvmem_cell * cell, void * buf)
```

```json
{
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1359",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_cell_read",
        "drivers/nvmem/core.c:nvmem_cell_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589783744,
      "name": "nvmem_shift_read_buffer_in_place",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    },
    {
      "addr": 18446744071592690607,
      "name": "nvmem_shift_read_buffer_in_place.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591295365,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1376",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593046181,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1379",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593498568,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1552",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594246232,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:1595",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501817852,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:907",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234336632,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:907",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295215312,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:907",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278164658,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:907",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587898507,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:907",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587617787,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:907",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588231803,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:907",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "nvmem_shift_read_buffer_in_place",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588367131,
      "name": "nvmem_shift_read_buffer_in_place",
      "external": false,
      "loc": "drivers/nvmem/core.c:907",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void nvmem_shift_read_buffer_in_place(struct nvmem_cell * cell, void * buf)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void nvmem_shift_read_buffer_in_place(struct nvmem_cell * cell, void * buf)
```
</details>
</li>
</ul>
