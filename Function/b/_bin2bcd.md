# Function: <code>_bin2bcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583006208,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:10",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "arch/x86/kernel/rtc.c:mach_set_rtc_mmss",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/base/power/trace.c:generate_pm_trace",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583006208,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583296704,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:10",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583296704,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583415568,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:10",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583415568,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583437296,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:10",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437296,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583617216,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583617216,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583833664,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833664,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583917360,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583917360,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584097248,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584097248,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584219888,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584219888,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584625824,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584625824,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744224,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744224,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584772368,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772368,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585202256,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585202256,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586038704,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586038704,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587020960,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587020960,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587276000,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587276000,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587564736,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587564736,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496093176,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496093176,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229420112,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_alarm",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-mv.c:mv_rtc_set_time",
        "drivers/rtc/rtc-omap.c:tm2bcd",
        "drivers/rtc/rtc-omap.c:tm2bcd",
        "drivers/rtc/rtc-omap.c:tm2bcd",
        "drivers/rtc/rtc-omap.c:tm2bcd",
        "drivers/rtc/rtc-omap.c:tm2bcd",
        "drivers/rtc/rtc-omap.c:tm2bcd",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time",
        "drivers/rtc/rtc-pcf8523.c:pcf8523_rtc_set_time",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_tm_to_time",
        "drivers/rtc/rtc-pl031.c:pl031_stv2_tm_to_time",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_setalarm",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_settime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_settime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_settime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_settime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_settime",
        "drivers/rtc/rtc-s3c.c:s3c_rtc_settime",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_alarm",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_time",
        "drivers/rtc/rtc-twl.c:twl_rtc_set_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229420112,
      "name": "_bin2bcd",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290335504,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-opal.c:tm_to_opal",
        "drivers/rtc/rtc-opal.c:tm_to_opal",
        "drivers/rtc/rtc-opal.c:tm_to_opal",
        "drivers/rtc/rtc-opal.c:tm_to_opal",
        "drivers/rtc/rtc-opal.c:tm_to_opal",
        "drivers/rtc/rtc-opal.c:tm_to_opal",
        "drivers/rtc/rtc-opal.c:tm_to_opal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290335504,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275162186,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275162186,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584188624,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188624,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584123856,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584123856,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584172384,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172384,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
unsigned char _bin2bcd(unsigned int val)
```

```json
{
  "name": "_bin2bcd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584276688,
      "name": "_bin2bcd",
      "external": true,
      "loc": "lib/bcd.c:11",
      "file": "lib/bcd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-mc146818-lib.c:mc146818_set_time",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm",
        "drivers/rtc/rtc-cmos.c:cmos_set_alarm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584276688,
      "name": "_bin2bcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
