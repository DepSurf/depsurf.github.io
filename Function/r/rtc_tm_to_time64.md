# Function: <code>rtc_tm_to_time64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585608384,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/rtc-lib.c:119",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_show",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585608384,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586003632,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/rtc-lib.c:119",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_show",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586003632,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586199440,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/rtc-lib.c:119",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_show",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586199440,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287472,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/rtc-lib.c:119",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_show",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287472,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586750800,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/rtc-lib.c:119",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_show",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586750800,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587017312,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/rtc-lib.c:117",
      "file": "drivers/rtc/rtc-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-dev.c:rtc_dev_ioctl",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_store",
        "drivers/rtc/rtc-sysfs.c:wakealarm_show",
        "drivers/rtc/rtc-sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587017312,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587178768,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:117",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587178768,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587444208,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587444208,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647280,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647280,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588513045,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime"
      ],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588512992,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588538441,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime"
      ],
      "caller_func": [
        "drivers/rtc/interface.c:rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588538384,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588421705,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime"
      ],
      "caller_func": [
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/interface.c:rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588421648,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589089849,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:168",
      "file": "drivers/rtc/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime"
      ],
      "caller_func": [
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589089648,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590533145,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:168",
      "file": "drivers/rtc/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime"
      ],
      "caller_func": [
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/interface.c:rtc_valid_range",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590532880,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592185289,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:168",
      "file": "drivers/rtc/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime"
      ],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/interface.c:rtc_valid_range",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592184992,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592609017,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:168",
      "file": "drivers/rtc/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime"
      ],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/interface.c:rtc_valid_range",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592608768,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593353769,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:168",
      "file": "drivers/rtc/lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime"
      ],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_get_cmos_time",
        "drivers/rtc/class.c:__devm_rtc_register_device",
        "drivers/rtc/class.c:rtc_resume",
        "drivers/rtc/class.c:rtc_suspend",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/interface.c:rtc_valid_range",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_check_wkalrm",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593353520,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500799336,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_setalarm",
        "drivers/rtc/rtc-sun6i.c:sun6i_rtc_setalarm",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_set_alarm",
        "drivers/rtc/rtc-xgene.c:xgene_rtc_set_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500799336,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233305120,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-omap.c:omap_rtc_power_off_program",
        "drivers/rtc/rtc-pl031.c:pl031_set_alarm",
        "drivers/rtc/rtc-pl031.c:pl031_set_time",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_tm_to_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233305120,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294251776,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/time.c:read_persistent_clock64",
        "arch/powerpc/platforms/powernv/opal-rtc.c:opal_get_boot_time",
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294251776,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277621436,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277621436,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587331040,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587331040,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587099344,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587099344,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587598528,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587598528,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
time64_t rtc_tm_to_time64(struct rtc_time * tm)
```

```json
{
  "name": "rtc_tm_to_time64",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587709344,
      "name": "rtc_tm_to_time64",
      "external": true,
      "loc": "drivers/rtc/lib.c:115",
      "file": "drivers/rtc/lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/lib.c:rtc_tm_to_ktime",
        "drivers/rtc/hctosys.c:rtc_hctosys",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:__rtc_set_alarm",
        "drivers/rtc/interface.c:rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:__rtc_read_alarm",
        "drivers/rtc/interface.c:rtc_read_time",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/dev.c:rtc_dev_ioctl",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_store",
        "drivers/rtc/sysfs.c:wakealarm_show",
        "drivers/rtc/sysfs.c:since_epoch_show",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_resume",
        "drivers/rtc/rtc-cmos.c:cmos_aie_poweroff",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_validate_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587709344,
      "name": "rtc_tm_to_time64",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
