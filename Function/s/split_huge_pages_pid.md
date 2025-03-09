# Function: <code>split_huge_pages_pid</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end)
```

```json
{
  "name": "split_huge_pages_pid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581992272,
      "name": "split_huge_pages_pid",
      "external": false,
      "loc": "mm/huge_memory.c:2970",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581992272,
      "name": "split_huge_pages_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 801
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
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end)
```

```json
{
  "name": "split_huge_pages_pid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582294512,
      "name": "split_huge_pages_pid",
      "external": false,
      "loc": "mm/huge_memory.c:2913",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582294512,
      "name": "split_huge_pages_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end)
```

```json
{
  "name": "split_huge_pages_pid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582780816,
      "name": "split_huge_pages_pid",
      "external": false,
      "loc": "mm/huge_memory.c:2883",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582780816,
      "name": "split_huge_pages_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1120
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
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end)
```

```json
{
  "name": "split_huge_pages_pid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583312992,
      "name": "split_huge_pages_pid",
      "external": false,
      "loc": "mm/huge_memory.c:2983",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312992,
      "name": "split_huge_pages_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1105
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
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end)
```

```json
{
  "name": "split_huge_pages_pid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583532320,
      "name": "split_huge_pages_pid",
      "external": false,
      "loc": "mm/huge_memory.c:2992",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583532320,
      "name": "split_huge_pages_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1122
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
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end)
```

```json
{
  "name": "split_huge_pages_pid",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583726672,
      "name": "split_huge_pages_pid",
      "external": false,
      "loc": "mm/huge_memory.c:3318",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/huge_memory.c:split_huge_pages_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726672,
      "name": "split_huge_pages_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 809
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
int split_huge_pages_pid(int pid, long unsigned int vaddr_start, long unsigned int vaddr_end)
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
