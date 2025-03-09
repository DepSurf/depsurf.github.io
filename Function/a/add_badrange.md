# Function: <code>add_badrange</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585802023,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:56",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586047719,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:56",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586188439,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:56",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586425607,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586572247,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
int add_badrange(struct badrange * badrange, u64 addr, u64 length)
```

```json
{
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587357408,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/badrange.c:badrange_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357408,
      "name": "add_badrange",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
int add_badrange(struct badrange * badrange, u64 addr, u64 length)
```

```json
{
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587418720,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/badrange.c:badrange_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587418720,
      "name": "add_badrange",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587300279,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587867111,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589216551,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590772263,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591113671,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591458999,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336499461912,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055292726124,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936276683410,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586262727,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586081095,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586520215,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
  "name": "add_badrange",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586630903,
      "name": "add_badrange",
      "external": false,
      "loc": "drivers/nvdimm/badrange.c:48",
      "file": "drivers/nvdimm/badrange.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/badrange.c:badrange_add"
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
int add_badrange(struct badrange * badrange, u64 addr, u64 length)
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
int add_badrange(struct badrange * badrange, u64 addr, u64 length)
```
</details>
</li>
</ul>
