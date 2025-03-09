# Function: <code>tick_broadcast_oneshot_offline</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580140036,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580188180,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580253268,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580237124,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:980",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580242356,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:992",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580393097,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:1100",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
void tick_broadcast_oneshot_offline(unsigned int cpu)
```

```json
{
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607376,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:1100",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607376,
      "name": "tick_broadcast_oneshot_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void tick_broadcast_oneshot_offline(unsigned int cpu)
```

```json
{
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580871360,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:1100",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580871360,
      "name": "tick_broadcast_oneshot_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void tick_broadcast_oneshot_offline(unsigned int cpu)
```

```json
{
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580955120,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:1160",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580955120,
      "name": "tick_broadcast_oneshot_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void tick_broadcast_oneshot_offline(unsigned int cpu)
```

```json
{
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046704,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:1160",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046704,
      "name": "tick_broadcast_oneshot_offline",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491414800,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225409236,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284362560,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580156980,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580103092,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580148452,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
  "name": "tick_broadcast_oneshot_offline",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580200436,
      "name": "tick_broadcast_oneshot_offline",
      "external": false,
      "loc": "kernel/time/tick-broadcast.c:963",
      "file": "kernel/time/tick-broadcast.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/tick-broadcast.c:tick_broadcast_offline"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void tick_broadcast_oneshot_offline(unsigned int cpu)
```
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
