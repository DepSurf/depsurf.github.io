# Function: <code>loop_free_idle_workers</code>

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
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void loop_free_idle_workers(struct timer_list * timer)
```

```json
{
  "name": "loop_free_idle_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587691216,
      "name": "loop_free_idle_workers",
      "external": false,
      "loc": "drivers/block/loop.c:2324",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587691216,
      "name": "loop_free_idle_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
void loop_free_idle_workers(struct loop_device * lo, bool delete_all)
```

```json
{
  "name": "loop_free_idle_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589030112,
      "name": "loop_free_idle_workers",
      "external": false,
      "loc": "drivers/block/loop.c:906",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_free_disk",
        "drivers/block/loop.c:loop_free_idle_workers_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589030112,
      "name": "loop_free_idle_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void loop_free_idle_workers(struct loop_device * lo, bool delete_all)
```

```json
{
  "name": "loop_free_idle_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590558480,
      "name": "loop_free_idle_workers",
      "external": false,
      "loc": "drivers/block/loop.c:906",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_free_disk",
        "drivers/block/loop.c:loop_free_idle_workers_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590558480,
      "name": "loop_free_idle_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void loop_free_idle_workers(struct loop_device * lo, bool delete_all)
```

```json
{
  "name": "loop_free_idle_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590886928,
      "name": "loop_free_idle_workers",
      "external": false,
      "loc": "drivers/block/loop.c:906",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_free_disk",
        "drivers/block/loop.c:loop_free_idle_workers_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590886928,
      "name": "loop_free_idle_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
void loop_free_idle_workers(struct loop_device * lo, bool delete_all)
```

```json
{
  "name": "loop_free_idle_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591231040,
      "name": "loop_free_idle_workers",
      "external": false,
      "loc": "drivers/block/loop.c:902",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:lo_free_disk",
        "drivers/block/loop.c:loop_free_idle_workers_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591231040,
      "name": "loop_free_idle_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void loop_free_idle_workers(struct timer_list * timer)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct loop_device * lo</code>
</li>
<li>
<b>Param added. </b>
<code>bool delete_all</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timer_list * timer</code>
</li>
</ul>
</details>
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
