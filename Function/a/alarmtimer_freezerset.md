# Function: <code>alarmtimer_freezerset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void alarmtimer_freezerset(ktime_t absexp, enum alarmtimer_type type)
```

```json
{
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579871376,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:281",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579871376,
      "name": "alarmtimer_freezerset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void alarmtimer_freezerset(ktime_t absexp, enum alarmtimer_type type)
```

```json
{
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579900672,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:296",
      "file": "kernel/time/alarmtimer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579900672,
      "name": "alarmtimer_freezerset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void alarmtimer_freezerset(ktime_t absexp, enum alarmtimer_type type)
```

```json
{
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579913424,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:308",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarm_timer_nsleep",
        "kernel/time/alarmtimer.c:alarm_timer_nsleep_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579913424,
      "name": "alarmtimer_freezerset",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579922445,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:466",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579967790,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:480",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580015049,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:487",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580062409,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:484",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580106014,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:483",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580155118,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:492",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580216286,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:483",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580200537,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:483",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580205846,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:483",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580352748,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:483",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580567111,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:483",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580827450,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:507",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580911014,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:506",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581001542,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:517",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491374864,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:492",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225375508,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:492",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284315696,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:492",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271865116,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:492",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580124318,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:492",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580069614,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:492",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580115390,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:492",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
  "name": "alarmtimer_freezerset",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580167230,
      "name": "alarmtimer_freezerset",
      "external": false,
      "loc": "kernel/time/alarmtimer.c:492",
      "file": "kernel/time/alarmtimer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/alarmtimer.c:alarmtimer_do_nsleep"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void alarmtimer_freezerset(ktime_t absexp, enum alarmtimer_type type)
```
</details>
</li>
</ul>
