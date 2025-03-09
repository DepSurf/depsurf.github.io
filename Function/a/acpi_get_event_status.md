# Function: <code>acpi_get_event_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583642110,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:325",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642110,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583965179,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:325",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583965179,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584106810,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:325",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106810,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584173795,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:343",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584173795,
      "name": "acpi_get_event_status",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584476226,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:343",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584476226,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700455,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700455,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 395
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584800565,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584800565,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585003356,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003356,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585139359,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585139359,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585845117,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585845117,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585966268,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585966268,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585843357,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843357,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 383
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586330068,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330068,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587576911,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587576911,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588864944,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588864944,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589154368,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589154368,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589460688,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/acpi/sysfs.c:get_status",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589460688,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
  "name": "acpi_get_event_status",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_get_event_status",
      "external": false,
      "loc": "include/acpi/acpixf.h:695",
      "file": "drivers/acpi/sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585041517,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585041517,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584957077,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584957077,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585090943,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090943,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```

```json
{
  "name": "acpi_get_event_status",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585197103,
      "name": "acpi_get_event_status",
      "external": true,
      "loc": "drivers/acpi/acpica/evxfevnt.c:309",
      "file": "drivers/acpi/acpica/evxfevnt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_enter",
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585197103,
      "name": "acpi_get_event_status",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_get_event_status(u32 event, acpi_event_status * event_status)
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
