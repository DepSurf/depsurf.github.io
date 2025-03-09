# Function: <code>split_huge_pages_write</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t split_huge_pages_write(struct file * file, const char * buf, size_t count, loff_t * ppops)
```

```json
{
  "name": "split_huge_pages_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581993664,
      "name": "split_huge_pages_write",
      "external": false,
      "loc": "mm/huge_memory.c:3121",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993088,
      "name": "split_huge_pages_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071591279457,
      "name": "split_huge_pages_write.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581993664,
      "name": "split_huge_pages_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
ssize_t split_huge_pages_write(struct file * file, const char * buf, size_t count, loff_t * ppops)
```

```json
{
  "name": "split_huge_pages_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582295904,
      "name": "split_huge_pages_write",
      "external": false,
      "loc": "mm/huge_memory.c:3064",
      "file": "mm/huge_memory.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582295312,
      "name": "split_huge_pages_write.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
    },
    {
      "addr": 18446744071592224282,
      "name": "split_huge_pages_write.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071582295904,
      "name": "split_huge_pages_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
ssize_t split_huge_pages_write(struct file * file, const char * buf, size_t count, loff_t * ppops)
```

```json
{
  "name": "split_huge_pages_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "split_huge_pages_write",
      "external": false,
      "loc": "mm/huge_memory.c:3032",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582781936,
      "name": "split_huge_pages_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 761
    },
    {
      "addr": 18446744071594003432,
      "name": "split_huge_pages_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
ssize_t split_huge_pages_write(struct file * file, const char * buf, size_t count, loff_t * ppops)
```

```json
{
  "name": "split_huge_pages_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583314544,
      "name": "split_huge_pages_write",
      "external": false,
      "loc": "mm/huge_memory.c:3130",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583314544,
      "name": "split_huge_pages_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
ssize_t split_huge_pages_write(struct file * file, const char * buf, size_t count, loff_t * ppops)
```

```json
{
  "name": "split_huge_pages_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583533472,
      "name": "split_huge_pages_write",
      "external": false,
      "loc": "mm/huge_memory.c:3138",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583533472,
      "name": "split_huge_pages_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
ssize_t split_huge_pages_write(struct file * file, const char * buf, size_t count, loff_t * ppops)
```

```json
{
  "name": "split_huge_pages_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727504,
      "name": "split_huge_pages_write",
      "external": false,
      "loc": "mm/huge_memory.c:3466",
      "file": "mm/huge_memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727504,
      "name": "split_huge_pages_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
ssize_t split_huge_pages_write(struct file * file, const char * buf, size_t count, loff_t * ppops)
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
