# Function: <code>rv_disable_monitor</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int rv_disable_monitor(struct rv_monitor_def * mdef)
```

```json
{
  "name": "rv_disable_monitor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581715649,
      "name": "rv_disable_monitor",
      "external": true,
      "loc": "kernel/trace/rv/rv.c:251",
      "file": "kernel/trace/rv/rv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rv/rv.c:rv_unregister_monitor",
        "kernel/trace/rv/rv.c:enabled_monitors_write",
        "kernel/trace/rv/rv.c:monitor_enable_write_data"
      ],
      "caller_func": [
        "kernel/trace/rv/rv_reactors.c:monitor_reactors_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596012766,
      "name": "rv_disable_monitor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581714160,
      "name": "rv_disable_monitor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int rv_disable_monitor(struct rv_monitor_def * mdef)
```

```json
{
  "name": "rv_disable_monitor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874321,
      "name": "rv_disable_monitor",
      "external": true,
      "loc": "kernel/trace/rv/rv.c:251",
      "file": "kernel/trace/rv/rv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rv/rv.c:rv_unregister_monitor",
        "kernel/trace/rv/rv.c:enabled_monitors_write",
        "kernel/trace/rv/rv.c:monitor_enable_write_data"
      ],
      "caller_func": [
        "kernel/trace/rv/rv_reactors.c:monitor_reactors_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596532751,
      "name": "rv_disable_monitor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581872816,
      "name": "rv_disable_monitor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int rv_disable_monitor(struct rv_monitor_def * mdef)
```

```json
{
  "name": "rv_disable_monitor",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581997329,
      "name": "rv_disable_monitor",
      "external": true,
      "loc": "kernel/trace/rv/rv.c:251",
      "file": "kernel/trace/rv/rv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rv/rv.c:rv_unregister_monitor",
        "kernel/trace/rv/rv.c:enabled_monitors_write",
        "kernel/trace/rv/rv.c:monitor_enable_write_data"
      ],
      "caller_func": [
        "kernel/trace/rv/rv_reactors.c:monitor_reactors_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597433485,
      "name": "rv_disable_monitor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581995776,
      "name": "rv_disable_monitor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int rv_disable_monitor(struct rv_monitor_def * mdef)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
