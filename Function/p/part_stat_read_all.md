# Function: <code>part_stat_read_all</code>

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
void part_stat_read_all(struct hd_struct * part, struct disk_stats * stat)
```

```json
{
  "name": "part_stat_read_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584453200,
      "name": "part_stat_read_all",
      "external": false,
      "loc": "block/genhd.c:95",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584453200,
      "name": "part_stat_read_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void part_stat_read_all(struct block_device * part, struct disk_stats * stat)
```

```json
{
  "name": "part_stat_read_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584569856,
      "name": "part_stat_read_all",
      "external": false,
      "loc": "block/genhd.c:112",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584569856,
      "name": "part_stat_read_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void part_stat_read_all(struct block_device * part, struct disk_stats * stat)
```

```json
{
  "name": "part_stat_read_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584602160,
      "name": "part_stat_read_all",
      "external": false,
      "loc": "block/genhd.c:109",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584602160,
      "name": "part_stat_read_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
void part_stat_read_all(struct block_device * part, struct disk_stats * stat)
```

```json
{
  "name": "part_stat_read_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585016432,
      "name": "part_stat_read_all",
      "external": false,
      "loc": "block/genhd.c:123",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585016432,
      "name": "part_stat_read_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
void part_stat_read_all(struct block_device * part, struct disk_stats * stat)
```

```json
{
  "name": "part_stat_read_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585733632,
      "name": "part_stat_read_all",
      "external": false,
      "loc": "block/genhd.c:127",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585733632,
      "name": "part_stat_read_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 727
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
void part_stat_read_all(struct block_device * part, struct disk_stats * stat)
```

```json
{
  "name": "part_stat_read_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586517408,
      "name": "part_stat_read_all",
      "external": false,
      "loc": "block/genhd.c:104",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517408,
      "name": "part_stat_read_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
void part_stat_read_all(struct block_device * part, struct disk_stats * stat)
```

```json
{
  "name": "part_stat_read_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764656,
      "name": "part_stat_read_all",
      "external": false,
      "loc": "block/genhd.c:100",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764656,
      "name": "part_stat_read_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
void part_stat_read_all(struct block_device * part, struct disk_stats * stat)
```

```json
{
  "name": "part_stat_read_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587037136,
      "name": "part_stat_read_all",
      "external": false,
      "loc": "block/genhd.c:100",
      "file": "block/genhd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/genhd.c:diskstats_show",
        "block/genhd.c:part_stat_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587037136,
      "name": "part_stat_read_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
void part_stat_read_all(struct hd_struct * part, struct disk_stats * stat)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct hd_struct * part</code> ➡️ <code>struct block_device * part</code>
</li>
</ul>
</details>
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
