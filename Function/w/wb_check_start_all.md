# Function: <code>wb_check_start_all</code>

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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581628691,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:1872",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581787322,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:1873",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581874106,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:1899",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581998840,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:1914",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582076920,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2002",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
long int wb_check_start_all(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582308880,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2010",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_do_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582308880,
      "name": "wb_check_start_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
long int wb_check_start_all(struct bdi_writeback * wb)
```

```json
{
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582361776,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2006",
      "file": "fs/fs-writeback.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fs-writeback.c:wb_do_writeback"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582361776,
      "name": "wb_check_start_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582389716,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2021",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_do_writeback"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582710836,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2161",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_do_writeback"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583254452,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2147",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_do_writeback"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583836052,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2171",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_do_writeback"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584054100,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2182",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_do_writeback"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584268964,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2204",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_do_writeback"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493609500,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2002",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227153904,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2002",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287197048,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2002",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273256578,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2002",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582045656,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2002",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581983208,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2002",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582036936,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2002",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
  "name": "wb_check_start_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582108552,
      "name": "wb_check_start_all",
      "external": false,
      "loc": "fs/fs-writeback.c:2002",
      "file": "fs/fs-writeback.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fs-writeback.c:wb_workfn"
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
long int wb_check_start_all(struct bdi_writeback * wb)
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
long int wb_check_start_all(struct bdi_writeback * wb)
```
</details>
</li>
</ul>
