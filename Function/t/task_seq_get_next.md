# Function: <code>task_seq_get_next</code>

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
struct task_struct * task_seq_get_next(struct pid_namespace * ns, u32 * tid)
```

```json
{
  "name": "task_seq_get_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581033056,
      "name": "task_seq_get_next",
      "external": false,
      "loc": "kernel/bpf/task_iter.c:23",
      "file": "kernel/bpf/task_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581033056,
      "name": "task_seq_get_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
struct task_struct * task_seq_get_next(struct pid_namespace * ns, u32 * tid, bool skip_if_dup_files)
```

```json
{
  "name": "task_seq_get_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581041856,
      "name": "task_seq_get_next",
      "external": false,
      "loc": "kernel/bpf/task_iter.c:24",
      "file": "kernel/bpf/task_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581041856,
      "name": "task_seq_get_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
struct task_struct * task_seq_get_next(struct pid_namespace * ns, u32 * tid, bool skip_if_dup_files)
```

```json
{
  "name": "task_seq_get_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581055376,
      "name": "task_seq_get_next",
      "external": false,
      "loc": "kernel/bpf/task_iter.c:24",
      "file": "kernel/bpf/task_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581055376,
      "name": "task_seq_get_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
struct task_struct * task_seq_get_next(struct pid_namespace * ns, u32 * tid, bool skip_if_dup_files)
```

```json
{
  "name": "task_seq_get_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581280400,
      "name": "task_seq_get_next",
      "external": false,
      "loc": "kernel/bpf/task_iter.c:24",
      "file": "kernel/bpf/task_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581280400,
      "name": "task_seq_get_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
struct task_struct * task_seq_get_next(struct pid_namespace * ns, u32 * tid, bool skip_if_dup_files)
```

```json
{
  "name": "task_seq_get_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581575488,
      "name": "task_seq_get_next",
      "external": false,
      "loc": "kernel/bpf/task_iter.c:25",
      "file": "kernel/bpf/task_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581575488,
      "name": "task_seq_get_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct task_struct * task_seq_get_next(struct bpf_iter_seq_task_common * common, u32 * tid, bool skip_if_dup_files)
```

```json
{
  "name": "task_seq_get_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954416,
      "name": "task_seq_get_next",
      "external": false,
      "loc": "kernel/bpf/task_iter.c:109",
      "file": "kernel/bpf/task_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954416,
      "name": "task_seq_get_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
struct task_struct * task_seq_get_next(struct bpf_iter_seq_task_common * common, u32 * tid, bool skip_if_dup_files)
```

```json
{
  "name": "task_seq_get_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582142528,
      "name": "task_seq_get_next",
      "external": false,
      "loc": "kernel/bpf/task_iter.c:109",
      "file": "kernel/bpf/task_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582142528,
      "name": "task_seq_get_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
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
struct task_struct * task_seq_get_next(struct bpf_iter_seq_task_common * common, u32 * tid, bool skip_if_dup_files)
```

```json
{
  "name": "task_seq_get_next",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582288320,
      "name": "task_seq_get_next",
      "external": false,
      "loc": "kernel/bpf/task_iter.c:89",
      "file": "kernel/bpf/task_iter.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/task_iter.c:task_vma_seq_get_next",
        "kernel/bpf/task_iter.c:task_file_seq_get_next",
        "kernel/bpf/task_iter.c:task_seq_next",
        "kernel/bpf/task_iter.c:task_seq_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582288320,
      "name": "task_seq_get_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
struct task_struct * task_seq_get_next(struct pid_namespace * ns, u32 * tid)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool skip_if_dup_files</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_iter_seq_task_common * common</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pid_namespace * ns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
