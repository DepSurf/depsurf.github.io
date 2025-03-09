# Function: <code>update_event_times</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void update_event_times(struct perf_event * event)
```

```json
{
  "name": "update_event_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580386432,
      "name": "update_event_times",
      "external": false,
      "loc": "kernel/events/core.c:1154",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:update_group_times",
        "kernel/events/core.c:update_group_times",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580386432,
      "name": "update_event_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void update_event_times(struct perf_event * event)
```

```json
{
  "name": "update_event_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580452656,
      "name": "update_event_times",
      "external": false,
      "loc": "kernel/events/core.c:1402",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:update_group_times",
        "kernel/events/core.c:update_group_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580452656,
      "name": "update_event_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void update_event_times(struct perf_event * event)
```

```json
{
  "name": "update_event_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580515088,
      "name": "update_event_times",
      "external": false,
      "loc": "kernel/events/core.c:1410",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:update_group_times",
        "kernel/events/core.c:update_group_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515088,
      "name": "update_event_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void update_event_times(struct perf_event * event)
```

```json
{
  "name": "update_event_times",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580546768,
      "name": "update_event_times",
      "external": false,
      "loc": "kernel/events/core.c:1402",
      "file": "kernel/events/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_read",
        "kernel/events/core.c:__perf_event_task_sched_out",
        "kernel/events/core.c:update_group_times",
        "kernel/events/core.c:update_group_times"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580546768,
      "name": "update_event_times",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
void update_event_times(struct perf_event * event)
```
</details>
</li>
</ul>
