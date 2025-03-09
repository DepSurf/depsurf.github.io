# Function: <code>nvmem_add_cells</code>

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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586865072,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:356",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587352905,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:356",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587655840,
      "name": "nvmem_add_cells",
      "external": true,
      "loc": "drivers/nvmem/core.c:365",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587655840,
      "name": "nvmem_add_cells",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587787348,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:385",
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588090939,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:173",
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588296763,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:170",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589178304,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:395",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589178304,
      "name": "nvmem_add_cells",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589173872,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:500",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173872,
      "name": "nvmem_add_cells",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589066192,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:500",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589066192,
      "name": "nvmem_add_cells",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589784608,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:506",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589784608,
      "name": "nvmem_add_cells",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591296112,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:512",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591296112,
      "name": "nvmem_add_cells",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593047056,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:512",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593047056,
      "name": "nvmem_add_cells",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593504023,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:553",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_register"
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594253705,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:637",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_register"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501820548,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:170",
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234338320,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:170",
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295218528,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:170",
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278166894,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:170",
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587900523,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:170",
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587619803,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:170",
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588233819,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:170",
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
  "name": "nvmem_add_cells",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588369147,
      "name": "nvmem_add_cells",
      "external": false,
      "loc": "drivers/nvmem/core.c:170",
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int nvmem_add_cells(struct nvmem_device * nvmem, const struct nvmem_cell_info * info, int ncells)
```
</details>
</li>
</ul>
