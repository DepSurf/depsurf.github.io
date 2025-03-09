# Function: <code>prepare_seq_file</code>

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
int prepare_seq_file(struct file * file, struct bpf_iter_link * link)
```

```json
{
  "name": "prepare_seq_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581030080,
      "name": "prepare_seq_file",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:433",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/bpf/bpf_iter.c:iter_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581030080,
      "name": "prepare_seq_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int prepare_seq_file(struct file * file, struct bpf_iter_link * link, const struct bpf_iter_seq_info * seq_info)
```

```json
{
  "name": "prepare_seq_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581037440,
      "name": "prepare_seq_file",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:556",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/bpf/bpf_iter.c:iter_open",
        "kernel/bpf/bpf_iter.c:iter_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581037440,
      "name": "prepare_seq_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int prepare_seq_file(struct file * file, struct bpf_iter_link * link, const struct bpf_iter_seq_info * seq_info)
```

```json
{
  "name": "prepare_seq_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581050864,
      "name": "prepare_seq_file",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:556",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/bpf/bpf_iter.c:iter_open",
        "kernel/bpf/bpf_iter.c:iter_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050864,
      "name": "prepare_seq_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int prepare_seq_file(struct file * file, struct bpf_iter_link * link, const struct bpf_iter_seq_info * seq_info)
```

```json
{
  "name": "prepare_seq_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581275632,
      "name": "prepare_seq_file",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:579",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/bpf/bpf_iter.c:iter_open",
        "kernel/bpf/bpf_iter.c:iter_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581275632,
      "name": "prepare_seq_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
int prepare_seq_file(struct file * file, struct bpf_iter_link * link, const struct bpf_iter_seq_info * seq_info)
```

```json
{
  "name": "prepare_seq_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581569520,
      "name": "prepare_seq_file",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:578",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/bpf/bpf_iter.c:iter_open",
        "kernel/bpf/bpf_iter.c:iter_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581569520,
      "name": "prepare_seq_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int prepare_seq_file(struct file * file, struct bpf_iter_link * link, const struct bpf_iter_seq_info * seq_info)
```

```json
{
  "name": "prepare_seq_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581945728,
      "name": "prepare_seq_file",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:591",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/bpf/bpf_iter.c:iter_open",
        "kernel/bpf/bpf_iter.c:iter_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581945728,
      "name": "prepare_seq_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int prepare_seq_file(struct file * file, struct bpf_iter_link * link, const struct bpf_iter_seq_info * seq_info)
```

```json
{
  "name": "prepare_seq_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582133536,
      "name": "prepare_seq_file",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:591",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/bpf/bpf_iter.c:iter_open",
        "kernel/bpf/bpf_iter.c:iter_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582133536,
      "name": "prepare_seq_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int prepare_seq_file(struct file * file, struct bpf_iter_link * link, const struct bpf_iter_seq_info * seq_info)
```

```json
{
  "name": "prepare_seq_file",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582280784,
      "name": "prepare_seq_file",
      "external": false,
      "loc": "kernel/bpf/bpf_iter.c:591",
      "file": "kernel/bpf/bpf_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/bpf_iter.c:bpf_iter_new_fd",
        "kernel/bpf/bpf_iter.c:iter_open",
        "kernel/bpf/bpf_iter.c:iter_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582280784,
      "name": "prepare_seq_file",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
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
int prepare_seq_file(struct file * file, struct bpf_iter_link * link)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_iter_seq_info * seq_info</code>
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
