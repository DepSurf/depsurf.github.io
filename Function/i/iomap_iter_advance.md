# Function: <code>iomap_iter_advance</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iomap_iter_advance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583131341,
      "name": "iomap_iter_advance",
      "external": false,
      "loc": "fs/iomap/iter.c:10",
      "file": "fs/iomap/iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/iter.c:iomap_iter"
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
  "name": "iomap_iter_advance",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583595610,
      "name": "iomap_iter_advance",
      "external": false,
      "loc": "fs/iomap/iter.c:10",
      "file": "fs/iomap/iter.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/iomap/iter.c:iomap_iter"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int iomap_iter_advance(struct iomap_iter * iter)
```

```json
{
  "name": "iomap_iter_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584200256,
      "name": "iomap_iter_advance",
      "external": false,
      "loc": "fs/iomap/iter.c:22",
      "file": "fs/iomap/iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/iter.c:iomap_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584200256,
      "name": "iomap_iter_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int iomap_iter_advance(struct iomap_iter * iter)
```

```json
{
  "name": "iomap_iter_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584430336,
      "name": "iomap_iter_advance",
      "external": false,
      "loc": "fs/iomap/iter.c:22",
      "file": "fs/iomap/iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/iter.c:iomap_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584430336,
      "name": "iomap_iter_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int iomap_iter_advance(struct iomap_iter * iter)
```

```json
{
  "name": "iomap_iter_advance",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584651456,
      "name": "iomap_iter_advance",
      "external": false,
      "loc": "fs/iomap/iter.c:22",
      "file": "fs/iomap/iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/iter.c:iomap_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584651456,
      "name": "iomap_iter_advance",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int iomap_iter_advance(struct iomap_iter * iter)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
