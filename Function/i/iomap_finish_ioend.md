# Function: <code>iomap_finish_ioend</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void iomap_finish_ioend(struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_finish_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_finish_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1095",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_finish_ioends",
        "fs/iomap/buffered-io.c:iomap_finish_ioends"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582691968,
      "name": "iomap_finish_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    },
    {
      "addr": 18446744071582698733,
      "name": "iomap_finish_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void iomap_finish_ioend(struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_finish_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_finish_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1064",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_finish_ioends",
        "fs/iomap/buffered-io.c:iomap_finish_ioends"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582762928,
      "name": "iomap_finish_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    },
    {
      "addr": 18446744071591344935,
      "name": "iomap_finish_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void iomap_finish_ioend(struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_finish_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_finish_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1064",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_finish_ioends",
        "fs/iomap/buffered-io.c:iomap_finish_ioends"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582788816,
      "name": "iomap_finish_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071591287686,
      "name": "iomap_finish_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void iomap_finish_ioend(struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_finish_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_finish_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1033",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_finish_ioends",
        "fs/iomap/buffered-io.c:iomap_finish_ioends"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583114080,
      "name": "iomap_finish_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071592245031,
      "name": "iomap_finish_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
u32 iomap_finish_ioend(struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_finish_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_finish_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1030",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_finish_ioends",
        "fs/iomap/buffered-io.c:iomap_finish_ioends"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583597600,
      "name": "iomap_finish_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1637
    },
    {
      "addr": 18446744071594024235,
      "name": "iomap_finish_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
u32 iomap_finish_ioend(struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_finish_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_finish_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1291",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_finish_ioends",
        "fs/iomap/buffered-io.c:iomap_finish_ioends"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203424,
      "name": "iomap_finish_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1196
    },
    {
      "addr": 18446744071596059796,
      "name": "iomap_finish_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
u32 iomap_finish_ioend(struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_finish_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_finish_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1311",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_finish_ioends",
        "fs/iomap/buffered-io.c:iomap_finish_ioends"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584433360,
      "name": "iomap_finish_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1138
    },
    {
      "addr": 18446744071596583983,
      "name": "iomap_finish_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
u32 iomap_finish_ioend(struct iomap_ioend * ioend, int error)
```

```json
{
  "name": "iomap_finish_ioend",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_finish_ioend",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1479",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage_end_bio",
        "fs/iomap/buffered-io.c:iomap_finish_ioends",
        "fs/iomap/buffered-io.c:iomap_finish_ioends"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584655024,
      "name": "iomap_finish_ioend",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1167
    },
    {
      "addr": 18446744071597489005,
      "name": "iomap_finish_ioend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
void iomap_finish_ioend(struct iomap_ioend * ioend, int error)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
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
