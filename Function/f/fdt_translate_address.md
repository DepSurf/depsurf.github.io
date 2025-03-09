# Function: <code>fdt_translate_address</code>

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
u64 fdt_translate_address(const void * blob, int node_offset)
```

```json
{
  "name": "fdt_translate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511306996,
      "name": "fdt_translate_address",
      "external": false,
      "loc": "drivers/of/fdt_address.c:163",
      "file": "drivers/of/fdt_address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt_address.c:of_flat_dt_translate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511306996,
      "name": "fdt_translate_address",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 672
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "fdt_translate_address",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243967636,
      "name": "fdt_translate_address",
      "external": false,
      "loc": "drivers/of/fdt_address.c:163",
      "file": "drivers/of/fdt_address.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/fdt_address.c:of_flat_dt_translate_address"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
u64 fdt_translate_address(const void * blob, int node_offset)
```

```json
{
  "name": "fdt_translate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302856192,
      "name": "fdt_translate_address",
      "external": false,
      "loc": "drivers/of/fdt_address.c:163",
      "file": "drivers/of/fdt_address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt_address.c:of_flat_dt_translate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302856192,
      "name": "fdt_translate_address",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1332
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
u64 fdt_translate_address(const void * blob, int node_offset)
```

```json
{
  "name": "fdt_translate_address",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270843438,
      "name": "fdt_translate_address",
      "external": false,
      "loc": "drivers/of/fdt_address.c:163",
      "file": "drivers/of/fdt_address.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/fdt_address.c:of_flat_dt_translate_address"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270843438,
      "name": "fdt_translate_address",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 932
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
u64 fdt_translate_address(const void * blob, int node_offset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
u64 fdt_translate_address(const void * blob, int node_offset)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
u64 fdt_translate_address(const void * blob, int node_offset)
```
</details>
</li>
</ul>
