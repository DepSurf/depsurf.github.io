# Function: <code>tick_set_oneshot_wakeup_device</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device * newdev, int cpu)
```

```json
{
  "name": "tick_set_oneshot_wakeup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580393138,
      "name": "tick_set_oneshot_wakeup_device",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:115",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580388976,
      "name": "tick_set_oneshot_wakeup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device * newdev, int cpu)
```

```json
{
  "name": "tick_set_oneshot_wakeup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580607434,
      "name": "tick_set_oneshot_wakeup_device",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:115",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580606864,
      "name": "tick_set_oneshot_wakeup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device * newdev, int cpu)
```

```json
{
  "name": "tick_set_oneshot_wakeup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580871418,
      "name": "tick_set_oneshot_wakeup_device",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:115",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580870752,
      "name": "tick_set_oneshot_wakeup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device * newdev, int cpu)
```

```json
{
  "name": "tick_set_oneshot_wakeup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580955178,
      "name": "tick_set_oneshot_wakeup_device",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:116",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580954512,
      "name": "tick_set_oneshot_wakeup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool tick_set_oneshot_wakeup_device(struct clock_event_device * newdev, int cpu)
```

```json
{
  "name": "tick_set_oneshot_wakeup_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581046762,
      "name": "tick_set_oneshot_wakeup_device",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:116",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_oneshot_offline"
      ],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_install_broadcast_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046096,
      "name": "tick_set_oneshot_wakeup_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 346
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
bool tick_set_oneshot_wakeup_device(struct clock_event_device * newdev, int cpu)
```
</details>
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
