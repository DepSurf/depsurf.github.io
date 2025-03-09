# Function: <code>rseq_update_cpu_id</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580853451,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580921915,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581017934,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581073198,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
int rseq_update_cpu_id(struct task_struct * t)
```

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581253760,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581253760,
      "name": "rseq_update_cpu_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
int rseq_update_cpu_id(struct task_struct * t)
```

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295888,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295888,
      "name": "rseq_update_cpu_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581314508,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581559745,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int rseq_update_cpu_id(struct task_struct * t)
```

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581911616,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581911616,
      "name": "rseq_update_cpu_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582347185,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:85",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336492435552,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3226311224,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055285705408,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581042046,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580989326,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581033246,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
  "name": "rseq_update_cpu_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581095164,
      "name": "rseq_update_cpu_id",
      "external": false,
      "loc": "kernel/rseq.c:84",
      "file": "kernel/rseq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/rseq.c:__rseq_handle_notify_resume"
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
int rseq_update_cpu_id(struct task_struct * t)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int rseq_update_cpu_id(struct task_struct * t)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int rseq_update_cpu_id(struct task_struct * t)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int rseq_update_cpu_id(struct task_struct * t)
```
</details>
</li>
</ul>
