# Function: <code>tasklet_clear_sched</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tasklet_clear_sched(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_clear_sched",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579547472,
      "name": "tasklet_clear_sched",
      "external": false,
      "loc": "kernel/softirq.c:749",
      "file": "kernel/softirq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547472,
      "name": "tasklet_clear_sched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
bool tasklet_clear_sched(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_clear_sched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_clear_sched",
      "external": false,
      "loc": "kernel/softirq.c:748",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579619536,
      "name": "tasklet_clear_sched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
    },
    {
      "addr": 18446744071592100390,
      "name": "tasklet_clear_sched.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
bool tasklet_clear_sched(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_clear_sched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_clear_sched",
      "external": false,
      "loc": "kernel/softirq.c:762",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579714000,
      "name": "tasklet_clear_sched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071593867967,
      "name": "tasklet_clear_sched.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool tasklet_clear_sched(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_clear_sched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_clear_sched",
      "external": false,
      "loc": "kernel/softirq.c:762",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840784,
      "name": "tasklet_clear_sched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071595973819,
      "name": "tasklet_clear_sched.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
bool tasklet_clear_sched(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_clear_sched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_clear_sched",
      "external": false,
      "loc": "kernel/softirq.c:744",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579890768,
      "name": "tasklet_clear_sched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071596491435,
      "name": "tasklet_clear_sched.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
bool tasklet_clear_sched(struct tasklet_struct * t)
```

```json
{
  "name": "tasklet_clear_sched",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tasklet_clear_sched",
      "external": false,
      "loc": "kernel/softirq.c:744",
      "file": "kernel/softirq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/softirq.c:tasklet_kill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929344,
      "name": "tasklet_clear_sched",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
    },
    {
      "addr": 18446744071597388155,
      "name": "tasklet_clear_sched.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
bool tasklet_clear_sched(struct tasklet_struct * t)
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
