# Function: <code>__rtc_set_alarm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585611984,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:306",
      "file": "drivers/rtc/interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_timer_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611984,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586007232,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:316",
      "file": "drivers/rtc/interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586007232,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586203040,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:316",
      "file": "drivers/rtc/interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586203040,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586291776,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:323",
      "file": "drivers/rtc/interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586291776,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586755248,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:323",
      "file": "drivers/rtc/interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586755248,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024400,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:404",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024400,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587185024,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:400",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587185024,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587450560,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:392",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_remove",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450560,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587653600,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_remove",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587653600,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588519456,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588519456,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588545152,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588545152,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588428272,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588428272,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589095984,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589095984,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590541360,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590541360,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592194608,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592194608,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592618464,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592618464,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593363264,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593363264,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500804176,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_remove",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500804176,
      "name": "__rtc_set_alarm",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233312144,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233312144,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294262320,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294262320,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277626082,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277626082,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587337360,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_remove",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587337360,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587105664,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_remove",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587105664,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587604848,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_remove",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587604848,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
int __rtc_set_alarm(struct rtc_device * rtc, struct rtc_wkalrm * alarm)
```

```json
{
  "name": "__rtc_set_alarm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715712,
      "name": "__rtc_set_alarm",
      "external": false,
      "loc": "drivers/rtc/interface.c:409",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_remove",
        "drivers/rtc/interface.c:rtc_timer_enqueue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715712,
      "name": "__rtc_set_alarm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
