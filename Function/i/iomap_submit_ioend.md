# Function: <code>iomap_submit_ioend</code>

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
int iomap_submit_ioend(struct iomap_writepage_ctx * wpc, struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_submit_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582687296,
      "name": "iomap_submit_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1223",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepages",
        "fs/iomap/buffered-io.c:iomap_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582687296,
      "name": "iomap_submit_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int iomap_submit_ioend(struct iomap_writepage_ctx * wpc, struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_submit_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758544,
      "name": "iomap_submit_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1193",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepages",
        "fs/iomap/buffered-io.c:iomap_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758544,
      "name": "iomap_submit_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int iomap_submit_ioend(struct iomap_writepage_ctx * wpc, struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_submit_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582787504,
      "name": "iomap_submit_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1190",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepages",
        "fs/iomap/buffered-io.c:iomap_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582787504,
      "name": "iomap_submit_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int iomap_submit_ioend(struct iomap_writepage_ctx * wpc, struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_submit_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583113424,
      "name": "iomap_submit_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1159",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepages",
        "fs/iomap/buffered-io.c:iomap_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583113424,
      "name": "iomap_submit_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
int iomap_submit_ioend(struct iomap_writepage_ctx * wpc, struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_submit_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583596576,
      "name": "iomap_submit_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1186",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepages",
        "fs/iomap/buffered-io.c:iomap_writepage",
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583596576,
      "name": "iomap_submit_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int iomap_submit_ioend(struct iomap_writepage_ctx * wpc, struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_submit_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584201856,
      "name": "iomap_submit_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1447",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepages",
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201856,
      "name": "iomap_submit_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int iomap_submit_ioend(struct iomap_writepage_ctx * wpc, struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_submit_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584432016,
      "name": "iomap_submit_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1467",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepages",
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432016,
      "name": "iomap_submit_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int iomap_submit_ioend(struct iomap_writepage_ctx * wpc, struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_submit_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584653168,
      "name": "iomap_submit_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1635",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepages",
        "fs/iomap/buffered-io.c:iomap_writepage_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653168,
      "name": "iomap_submit_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int iomap_submit_ioend(struct iomap_writepage_ctx * wpc, struct iomap_ioend * ioend, int error)
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
