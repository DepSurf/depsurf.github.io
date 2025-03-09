# Function: <code>posix_cpu_timers_work</code>

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
void posix_cpu_timers_work(struct callback_head * work)
```

```json
{
  "name": "posix_cpu_timers_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220032,
      "name": "posix_cpu_timers_work",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1098",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220032,
      "name": "posix_cpu_timers_work",
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
void posix_cpu_timers_work(struct callback_head * work)
```

```json
{
  "name": "posix_cpu_timers_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "posix_cpu_timers_work",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1098",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580224608,
      "name": "posix_cpu_timers_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
    },
    {
      "addr": 18446744071591254534,
      "name": "posix_cpu_timers_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void posix_cpu_timers_work(struct callback_head * work)
```

```json
{
  "name": "posix_cpu_timers_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "posix_cpu_timers_work",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1156",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580373040,
      "name": "posix_cpu_timers_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 627
    },
    {
      "addr": 18446744071592156378,
      "name": "posix_cpu_timers_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void posix_cpu_timers_work(struct callback_head * work)
```

```json
{
  "name": "posix_cpu_timers_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "posix_cpu_timers_work",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1163",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580590816,
      "name": "posix_cpu_timers_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 682
    },
    {
      "addr": 18446744071593931398,
      "name": "posix_cpu_timers_work.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void posix_cpu_timers_work(struct callback_head * work)
```

```json
{
  "name": "posix_cpu_timers_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852992,
      "name": "posix_cpu_timers_work",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1163",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852992,
      "name": "posix_cpu_timers_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 772
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
void posix_cpu_timers_work(struct callback_head * work)
```

```json
{
  "name": "posix_cpu_timers_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936720,
      "name": "posix_cpu_timers_work",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1164",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936720,
      "name": "posix_cpu_timers_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
void posix_cpu_timers_work(struct callback_head * work)
```

```json
{
  "name": "posix_cpu_timers_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028112,
      "name": "posix_cpu_timers_work",
      "external": false,
      "loc": "kernel/time/posix-cpu-timers.c:1164",
      "file": "kernel/time/posix-cpu-timers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028112,
      "name": "posix_cpu_timers_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 378
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void posix_cpu_timers_work(struct callback_head * work)
```
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
