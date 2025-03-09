# Function: <code>nvmem_cell_entry_drop</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void nvmem_cell_entry_drop(struct nvmem_cell_entry * cell)
```

```json
{
  "name": "nvmem_cell_entry_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591294768,
      "name": "nvmem_cell_entry_drop",
      "external": false,
      "loc": "drivers/nvmem/core.c:432",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_release",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_add_cells"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591294768,
      "name": "nvmem_cell_entry_drop",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void nvmem_cell_entry_drop(struct nvmem_cell_entry * cell)
```

```json
{
  "name": "nvmem_cell_entry_drop",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593045520,
      "name": "nvmem_cell_entry_drop",
      "external": false,
      "loc": "drivers/nvmem/core.c:432",
      "file": "drivers/nvmem/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvmem/core.c:nvmem_device_release",
        "drivers/nvmem/core.c:nvmem_register",
        "drivers/nvmem/core.c:nvmem_add_cells"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593045520,
      "name": "nvmem_cell_entry_drop",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "nvmem_cell_entry_drop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593497992,
      "name": "nvmem_cell_entry_drop",
      "external": false,
      "loc": "drivers/nvmem/core.c:440",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_device_remove_all_cells"
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
  "name": "nvmem_cell_entry_drop",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594244920,
      "name": "nvmem_cell_entry_drop",
      "external": false,
      "loc": "drivers/nvmem/core.c:524",
      "file": "drivers/nvmem/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvmem/core.c:nvmem_device_remove_all_cells"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void nvmem_cell_entry_drop(struct nvmem_cell_entry * cell)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void nvmem_cell_entry_drop(struct nvmem_cell_entry * cell)
```
</details>
</li>
</ul>
