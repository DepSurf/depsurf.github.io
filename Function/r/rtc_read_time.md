# Function: <code>rtc_read_time</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585611904,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:46",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-proc.c:rtc_proc_show",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-sysfs.c:time_show",
        "drivers/rtc/rtc-sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585611904,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586007152,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:46",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-proc.c:rtc_proc_show",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-sysfs.c:time_show",
        "drivers/rtc/rtc-sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586007152,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586202960,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:46",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-proc.c:rtc_proc_show",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-sysfs.c:time_show",
        "drivers/rtc/rtc-sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586202960,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586290976,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:46",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-proc.c:rtc_proc_show",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-sysfs.c:time_show",
        "drivers/rtc/rtc-sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586290976,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586754448,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:46",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-proc.c:rtc_proc_show",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-sysfs.c:time_show",
        "drivers/rtc/rtc-sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586754448,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587024128,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:112",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-proc.c:rtc_proc_show",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-sysfs.c:time_show",
        "drivers/rtc/rtc-sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587024128,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587184752,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:112",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587184752,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587450288,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587450288,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587653328,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587653328,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588522608,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588522608,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588548176,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548176,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588429424,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588429424,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589097120,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589097120,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590542352,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/interface.c:rtc_initialize_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590542352,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592195264,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/interface.c:rtc_initialize_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592195264,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592620240,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/interface.c:rtc_initialize_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592620240,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593365040,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/interface.c:rtc_initialize_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593365040,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500807400,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500807400,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233311796,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233311796,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294261840,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294261840,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277625812,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277625812,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587337088,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587337088,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587105392,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587105392,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587604576,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587604576,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int rtc_read_time(struct rtc_device * rtc, struct rtc_time * tm)
```

```json
{
  "name": "rtc_read_time",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587715424,
      "name": "rtc_read_time",
      "external": true,
      "loc": "drivers/rtc/interface.c:110",
      "file": "drivers/rtc/interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/alarmtimer.c:alarmtimer_suspend",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/proc.c:rtc_proc_show",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/sysfs.c:time_show",
        "drivers/rtc/sysfs.c:date_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587715424,
      "name": "rtc_read_time",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
