# Function: <code>iomap_swapfile_fail</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int iomap_swapfile_fail(struct iomap_swapfile_info * isi, const char * str)
```

```json
{
  "name": "iomap_swapfile_fail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_swapfile_fail",
      "external": false,
      "loc": "fs/iomap/swapfile.c:74",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804000,
      "name": "iomap_swapfile_fail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071591287777,
      "name": "iomap_swapfile_fail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
int iomap_swapfile_fail(struct iomap_swapfile_info * isi, const char * str)
```

```json
{
  "name": "iomap_swapfile_fail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_swapfile_fail",
      "external": false,
      "loc": "fs/iomap/swapfile.c:80",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583132464,
      "name": "iomap_swapfile_fail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071592246212,
      "name": "iomap_swapfile_fail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int iomap_swapfile_fail(struct iomap_swapfile_info * isi, const char * str)
```

```json
{
  "name": "iomap_swapfile_fail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_swapfile_fail",
      "external": false,
      "loc": "fs/iomap/swapfile.c:80",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621440,
      "name": "iomap_swapfile_fail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
    },
    {
      "addr": 18446744071594026938,
      "name": "iomap_swapfile_fail.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
int iomap_swapfile_fail(struct iomap_swapfile_info * isi, const char * str)
```

```json
{
  "name": "iomap_swapfile_fail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225648,
      "name": "iomap_swapfile_fail",
      "external": false,
      "loc": "fs/iomap/swapfile.c:80",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225648,
      "name": "iomap_swapfile_fail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int iomap_swapfile_fail(struct iomap_swapfile_info * isi, const char * str)
```

```json
{
  "name": "iomap_swapfile_fail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584455088,
      "name": "iomap_swapfile_fail",
      "external": false,
      "loc": "fs/iomap/swapfile.c:80",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584455088,
      "name": "iomap_swapfile_fail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int iomap_swapfile_fail(struct iomap_swapfile_info * isi, const char * str)
```

```json
{
  "name": "iomap_swapfile_fail",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584678208,
      "name": "iomap_swapfile_fail",
      "external": false,
      "loc": "fs/iomap/swapfile.c:80",
      "file": "fs/iomap/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter",
        "fs/iomap/swapfile.c:iomap_swapfile_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584678208,
      "name": "iomap_swapfile_fail",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
int iomap_swapfile_fail(struct iomap_swapfile_info * isi, const char * str)
```
</details>
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
