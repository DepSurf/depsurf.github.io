# Function: <code>hpage_collapse_scan_file</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int hpage_collapse_scan_file(struct mm_struct * mm, long unsigned int addr, struct file * file, long unsigned int start, struct collapse_control * cc)
```

```json
{
  "name": "hpage_collapse_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpage_collapse_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:2131",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:madvise_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344496,
      "name": "hpage_collapse_scan_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1466
    },
    {
      "addr": 18446744071596047797,
      "name": "hpage_collapse_scan_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int hpage_collapse_scan_file(struct mm_struct * mm, long unsigned int addr, struct file * file, long unsigned int start, struct collapse_control * cc)
```

```json
{
  "name": "hpage_collapse_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpage_collapse_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:2320",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:madvise_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566256,
      "name": "hpage_collapse_scan_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1408
    },
    {
      "addr": 18446744071596570586,
      "name": "hpage_collapse_scan_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int hpage_collapse_scan_file(struct mm_struct * mm, long unsigned int addr, struct file * file, long unsigned int start, struct collapse_control * cc)
```

```json
{
  "name": "hpage_collapse_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hpage_collapse_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:2218",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:madvise_collapse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583754640,
      "name": "hpage_collapse_scan_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1387
    },
    {
      "addr": 18446744071597474739,
      "name": "hpage_collapse_scan_file.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int hpage_collapse_scan_file(struct mm_struct * mm, long unsigned int addr, struct file * file, long unsigned int start, struct collapse_control * cc)
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
