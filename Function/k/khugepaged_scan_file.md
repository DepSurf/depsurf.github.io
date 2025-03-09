# Function: <code>khugepaged_scan_file</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581721323,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1814",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
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
void khugepaged_scan_file(struct mm_struct * mm, struct file * file, long unsigned int start, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581933968,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1940",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581933968,
      "name": "khugepaged_scan_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 821
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
void khugepaged_scan_file(struct mm_struct * mm, struct file * file, long unsigned int start, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581984320,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1977",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581984320,
      "name": "khugepaged_scan_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
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
void khugepaged_scan_file(struct mm_struct * mm, struct file * file, long unsigned int start, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582012096,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1968",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582012096,
      "name": "khugepaged_scan_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 844
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
void khugepaged_scan_file(struct mm_struct * mm, struct file * file, long unsigned int start, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582314768,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1990",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314768,
      "name": "khugepaged_scan_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 863
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
void khugepaged_scan_file(struct mm_struct * mm, struct file * file, long unsigned int start, struct page * * hpage)
```

```json
{
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582801168,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1997",
      "file": "mm/khugepaged.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582801168,
      "name": "khugepaged_scan_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 965
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493169732,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1814",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
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
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286663624,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1814",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581690059,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1814",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
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
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581629083,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1814",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
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
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581681371,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1814",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged_scan_mm_slot"
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
  "name": "khugepaged_scan_file",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581749391,
      "name": "khugepaged_scan_file",
      "external": false,
      "loc": "mm/khugepaged.c:1814",
      "file": "mm/khugepaged.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/khugepaged.c:khugepaged"
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
void khugepaged_scan_file(struct mm_struct * mm, struct file * file, long unsigned int start, struct page * * hpage)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void khugepaged_scan_file(struct mm_struct * mm, struct file * file, long unsigned int start, struct page * * hpage)
```
</details>
</li>
</ul>
