# Function: <code>__unflatten_device_tree</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * __unflatten_device_tree(const void * blob, struct device_node * dad, struct device_node * * mynodes, void * (*)(u64, u64) dt_alloc, bool detached)
```

```json
{
  "name": "__unflatten_device_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501632960,
      "name": "__unflatten_device_tree",
      "external": true,
      "loc": "drivers/of/fdt.c:367",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:unflatten_device_tree",
        "drivers/of/fdt.c:of_fdt_unflatten_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501632960,
      "name": "__unflatten_device_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
void * __unflatten_device_tree(const void * blob, struct device_node * dad, struct device_node * * mynodes, void * (*)(u64, u64) dt_alloc, bool detached)
```

```json
{
  "name": "__unflatten_device_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234153920,
      "name": "__unflatten_device_tree",
      "external": true,
      "loc": "drivers/of/fdt.c:367",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:unflatten_device_tree",
        "drivers/of/fdt.c:of_fdt_unflatten_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234153920,
      "name": "__unflatten_device_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 688
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
void * __unflatten_device_tree(const void * blob, struct device_node * dad, struct device_node * * mynodes, void * (*)(u64, u64) dt_alloc, bool detached)
```

```json
{
  "name": "__unflatten_device_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295067184,
      "name": "__unflatten_device_tree",
      "external": true,
      "loc": "drivers/of/fdt.c:367",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:unflatten_device_tree",
        "drivers/of/fdt.c:of_fdt_unflatten_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295067184,
      "name": "__unflatten_device_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 924
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
void * __unflatten_device_tree(const void * blob, struct device_node * dad, struct device_node * * mynodes, void * (*)(u64, u64) dt_alloc, bool detached)
```

```json
{
  "name": "__unflatten_device_tree",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278092924,
      "name": "__unflatten_device_tree",
      "external": true,
      "loc": "drivers/of/fdt.c:367",
      "file": "drivers/of/fdt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt.c:unflatten_device_tree",
        "drivers/of/fdt.c:of_fdt_unflatten_tree"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278092924,
      "name": "__unflatten_device_tree",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 780
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void * __unflatten_device_tree(const void * blob, struct device_node * dad, struct device_node * * mynodes, void * (*)(u64, u64) dt_alloc, bool detached)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * __unflatten_device_tree(const void * blob, struct device_node * dad, struct device_node * * mynodes, void * (*)(u64, u64) dt_alloc, bool detached)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void * __unflatten_device_tree(const void * blob, struct device_node * dad, struct device_node * * mynodes, void * (*)(u64, u64) dt_alloc, bool detached)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void * __unflatten_device_tree(const void * blob, struct device_node * dad, struct device_node * * mynodes, void * (*)(u64, u64) dt_alloc, bool detached)
```
</details>
</li>
</ul>
