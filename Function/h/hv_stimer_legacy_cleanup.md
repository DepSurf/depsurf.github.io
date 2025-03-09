# Function: <code>hv_stimer_legacy_cleanup</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_legacy_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589081915,
      "name": "hv_stimer_legacy_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:249",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589081840,
      "name": "hv_stimer_legacy_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void hv_stimer_legacy_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_legacy_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589082923,
      "name": "hv_stimer_legacy_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:249",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589082848,
      "name": "hv_stimer_legacy_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void hv_stimer_legacy_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_legacy_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588969595,
      "name": "hv_stimer_legacy_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:318",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588969024,
      "name": "hv_stimer_legacy_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_legacy_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589679660,
      "name": "hv_stimer_legacy_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:318",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592676633,
      "name": "hv_stimer_legacy_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589678880,
      "name": "hv_stimer_legacy_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_legacy_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591184777,
      "name": "hv_stimer_legacy_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:318",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594561878,
      "name": "hv_stimer_legacy_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071591184112,
      "name": "hv_stimer_legacy_cleanup",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_legacy_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592911362,
      "name": "hv_stimer_legacy_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:319",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596318700,
      "name": "hv_stimer_legacy_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071592910640,
      "name": "hv_stimer_legacy_cleanup",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_legacy_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593350594,
      "name": "hv_stimer_legacy_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:330",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596848330,
      "name": "hv_stimer_legacy_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593349984,
      "name": "hv_stimer_legacy_cleanup",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu)
```

```json
{
  "name": "hv_stimer_legacy_cleanup",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594104594,
      "name": "hv_stimer_legacy_cleanup",
      "external": true,
      "loc": "drivers/clocksource/hyperv_timer.c:330",
      "file": "drivers/clocksource/hyperv_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597773255,
      "name": "hv_stimer_legacy_cleanup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071594103984,
      "name": "hv_stimer_legacy_cleanup",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu)
```
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
