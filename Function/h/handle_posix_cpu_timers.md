# Function: <code>handle_posix_cpu_timers</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void handle_posix_cpu_timers(struct task_struct * tsk)
```

```json
{
  "name": "handle_posix_cpu_timers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580219712,
      "name": "handle_posix_cpu_timers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1191",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580219712,
      "name": "handle_posix_cpu_timers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
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
  "name": "handle_posix_cpu_timers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580224665,
      "name": "handle_posix_cpu_timers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1191",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work"
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
  "name": "handle_posix_cpu_timers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580373097,
      "name": "handle_posix_cpu_timers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1264",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_posix_cpu_timers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580590873,
      "name": "handle_posix_cpu_timers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1271",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_posix_cpu_timers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580853049,
      "name": "handle_posix_cpu_timers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1271",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_posix_cpu_timers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580936786,
      "name": "handle_posix_cpu_timers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1327",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "handle_posix_cpu_timers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581028178,
      "name": "handle_posix_cpu_timers",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1327",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/posix-cpu-timers.c:posix_cpu_timers_work"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void handle_posix_cpu_timers(struct task_struct * tsk)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void handle_posix_cpu_timers(struct task_struct * tsk)
```
</details>
</li>
</ul>
