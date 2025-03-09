# Function: <code>bpf_seq_read</code>

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
ssize_t bpf_seq_read(struct file * file, char * buf, size_t size, loff_t * ppos)
```

```json
{
  "name": "bpf_seq_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_seq_read",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:77",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030384,
      "name": "bpf_seq_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 980
    },
    {
      "addr": 18446744071581032654,
      "name": "bpf_seq_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
ssize_t bpf_seq_read(struct file * file, char * buf, size_t size, loff_t * ppos)
```

```json
{
  "name": "bpf_seq_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_seq_read",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:89",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581038192,
      "name": "bpf_seq_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 998
    },
    {
      "addr": 18446744071591322971,
      "name": "bpf_seq_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
ssize_t bpf_seq_read(struct file * file, char * buf, size_t size, loff_t * ppos)
```

```json
{
  "name": "bpf_seq_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_seq_read",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:89",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581051616,
      "name": "bpf_seq_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
    },
    {
      "addr": 18446744071591264859,
      "name": "bpf_seq_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
ssize_t bpf_seq_read(struct file * file, char * buf, size_t size, loff_t * ppos)
```

```json
{
  "name": "bpf_seq_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_seq_read",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:89",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581276384,
      "name": "bpf_seq_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
    },
    {
      "addr": 18446744071592186281,
      "name": "bpf_seq_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
ssize_t bpf_seq_read(struct file * file, char * buf, size_t size, loff_t * ppos)
```

```json
{
  "name": "bpf_seq_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_seq_read",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:90",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581570336,
      "name": "bpf_seq_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1002
    },
    {
      "addr": 18446744071593960562,
      "name": "bpf_seq_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
ssize_t bpf_seq_read(struct file * file, char * buf, size_t size, loff_t * ppos)
```

```json
{
  "name": "bpf_seq_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946624,
      "name": "bpf_seq_read",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:94",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946624,
      "name": "bpf_seq_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
ssize_t bpf_seq_read(struct file * file, char * buf, size_t size, loff_t * ppos)
```

```json
{
  "name": "bpf_seq_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582134432,
      "name": "bpf_seq_read",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:94",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582134432,
      "name": "bpf_seq_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
ssize_t bpf_seq_read(struct file * file, char * buf, size_t size, loff_t * ppos)
```

```json
{
  "name": "bpf_seq_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582281680,
      "name": "bpf_seq_read",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:94",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582281680,
      "name": "bpf_seq_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1084
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
ssize_t bpf_seq_read(struct file * file, char * buf, size_t size, loff_t * ppos)
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
