# Function: <code>__rtc_read_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585611680,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:23",
      "file": "drivers/rtc/interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:rtc_timer_do_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611680,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586006912,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:23",
      "file": "drivers/rtc/interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586006912,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586202720,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:23",
      "file": "drivers/rtc/interface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586202720,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586290752,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:23",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586290752,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586754224,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:23",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586754224,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587023840,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:87",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023840,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587184464,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:87",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587184464,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587450000,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450000,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587653040,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587653040,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588519168,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588519168,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588544864,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588544864,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588427984,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427984,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589095552,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589095552,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590541008,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590541008,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592194224,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592194224,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592618080,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592618080,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593362880,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593362880,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500803784,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500803784,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233311528,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233311528,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294261376,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294261376,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277625580,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277625580,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587336800,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587336800,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587105104,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587105104,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587604288,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587604288,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
int __rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "__rtc_read_time",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715136,
      "name": "__rtc_read_time",
      "external": false,
      "loc": "drivers/rtc/interface.c:84",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_timer_do_work",
        "drivers/rtc/interface.c:rtc_timer_enqueue",
        "drivers/rtc/interface.c:rtc_update_irq_enable",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715136,
      "name": "__rtc_read_time",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
