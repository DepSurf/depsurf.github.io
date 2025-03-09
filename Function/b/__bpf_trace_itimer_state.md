# Function: <code>__bpf_trace_itimer_state</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579970864,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:299",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579970864,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580017936,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:299",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017936,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580062096,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580062096,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580111152,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111152,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerspec64 * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580171808,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580171808,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerspec64 * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580157072,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580157072,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerspec64 * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580161648,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161648,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerspec64 * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580306224,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580306224,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
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
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerspec64 * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580517792,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:307",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580517792,
      "name": "__bpf_trace_itimer_state",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerspec64 * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580772512,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:307",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772512,
      "name": "__bpf_trace_itimer_state",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerspec64 * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580855440,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:311",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580855440,
      "name": "__bpf_trace_itimer_state",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerspec64 * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580945568,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:331",
      "file": "kernel/time/timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580945568,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491322312,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491322312,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225318228,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225318228,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284252464,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284252464,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580080352,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580080352,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580025168,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580025168,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580071424,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580071424,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```

```json
{
  "name": "__bpf_trace_itimer_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580121616,
      "name": "__bpf_trace_itimer_state",
      "external": false,
      "loc": "include/trace/events/timer.h:304",
      "file": "kernel/time/timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580121616,
      "name": "__bpf_trace_itimer_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    }
  ]
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const const struct itimerval * value</code> ➡️ <code>const const struct itimerspec64 * value</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __bpf_trace_itimer_state(void * __data, int which, const const struct itimerval * value, long long unsigned int expires)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
