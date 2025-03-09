# Function: <code>iomap_do_writepage</code>

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
int iomap_do_writepage(struct page * page, struct writeback_control * wbc, void * data)
```

```json
{
  "name": "iomap_do_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582697936,
      "name": "iomap_do_writepage",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1477",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582697936,
      "name": "iomap_do_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
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
int iomap_do_writepage(struct page * page, struct writeback_control * wbc, void * data)
```

```json
{
  "name": "iomap_do_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582766224,
      "name": "iomap_do_writepage",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1437",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582766224,
      "name": "iomap_do_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 282
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
int iomap_do_writepage(struct page * page, struct writeback_control * wbc, void * data)
```

```json
{
  "name": "iomap_do_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792160,
      "name": "iomap_do_writepage",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1433",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792160,
      "name": "iomap_do_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
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
int iomap_do_writepage(struct page * page, struct writeback_control * wbc, void * data)
```

```json
{
  "name": "iomap_do_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583121184,
      "name": "iomap_do_writepage",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1394",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121184,
      "name": "iomap_do_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int iomap_do_writepage(struct page * page, struct writeback_control * wbc, void * data)
```

```json
{
  "name": "iomap_do_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_do_writepage",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1427",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/iomap/buffered-io.c:iomap_writepage"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583605888,
      "name": "iomap_do_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071594025395,
      "name": "iomap_do_writepage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int iomap_do_writepage(struct page * page, struct writeback_control * wbc, void * data)
```

```json
{
  "name": "iomap_do_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_do_writepage",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1689",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210528,
      "name": "iomap_do_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 561
    },
    {
      "addr": 18446744071596060958,
      "name": "iomap_do_writepage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
int iomap_do_writepage(struct folio * folio, struct writeback_control * wbc, void * data)
```

```json
{
  "name": "iomap_do_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_do_writepage",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1708",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440336,
      "name": "iomap_do_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
    },
    {
      "addr": 18446744071596585080,
      "name": "iomap_do_writepage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
int iomap_do_writepage(struct folio * folio, struct writeback_control * wbc, void * data)
```

```json
{
  "name": "iomap_do_writepage",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iomap_do_writepage",
      "external": false,
      "loc": "fs/iomap/buffered-io.c:1889",
      "file": "fs/iomap/buffered-io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662736,
      "name": "iomap_do_writepage",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
    },
    {
      "addr": 18446744071597490547,
      "name": "iomap_do_writepage.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int iomap_do_writepage(struct page * page, struct writeback_control * wbc, void * data)
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
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio * folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page * page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
