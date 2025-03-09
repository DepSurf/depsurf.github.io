# Function: <code>clocksource_verify_percpu</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void clocksource_verify_percpu(struct clocksource * cs)
```

```json
{
  "name": "clocksource_verify_percpu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "clocksource_verify_percpu",
      "external": false,
      "loc": "kernel/time/clocksource.c:238",
      "file": "kernel/time/clocksource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580194528,
      "name": "clocksource_verify_percpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    },
    {
      "addr": 18446744071591254170,
      "name": "clocksource_verify_percpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void clocksource_verify_percpu(struct clocksource * cs)
```

```json
{
  "name": "clocksource_verify_percpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580343058,
      "name": "clocksource_verify_percpu",
      "external": true,
      "loc": "kernel/time/clocksource.c:326",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342432,
      "name": "clocksource_verify_percpu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    },
    {
      "addr": 18446744071592155237,
      "name": "clocksource_verify_percpu.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
    },
    {
      "addr": 18446744071580342592,
      "name": "clocksource_verify_percpu",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void clocksource_verify_percpu(struct clocksource * cs)
```

```json
{
  "name": "clocksource_verify_percpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580556461,
      "name": "clocksource_verify_percpu",
      "external": true,
      "loc": "kernel/time/clocksource.c:332",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580555728,
      "name": "clocksource_verify_percpu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071593930256,
      "name": "clocksource_verify_percpu.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 521
    },
    {
      "addr": 18446744071580555952,
      "name": "clocksource_verify_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void clocksource_verify_percpu(struct clocksource * cs)
```

```json
{
  "name": "clocksource_verify_percpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580815613,
      "name": "clocksource_verify_percpu",
      "external": true,
      "loc": "kernel/time/clocksource.c:332",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814256,
      "name": "clocksource_verify_percpu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
    },
    {
      "addr": 18446744071595997606,
      "name": "clocksource_verify_percpu.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580815088,
      "name": "clocksource_verify_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void clocksource_verify_percpu(struct clocksource * cs)
```

```json
{
  "name": "clocksource_verify_percpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580898906,
      "name": "clocksource_verify_percpu",
      "external": true,
      "loc": "kernel/time/clocksource.c:335",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580897552,
      "name": "clocksource_verify_percpu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
    },
    {
      "addr": 18446744071596515752,
      "name": "clocksource_verify_percpu.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580898384,
      "name": "clocksource_verify_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
void clocksource_verify_percpu(struct clocksource * cs)
```

```json
{
  "name": "clocksource_verify_percpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580989434,
      "name": "clocksource_verify_percpu",
      "external": true,
      "loc": "kernel/time/clocksource.c:337",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_watchdog_kthread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580988080,
      "name": "clocksource_verify_percpu.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 807
    },
    {
      "addr": 18446744071597415079,
      "name": "clocksource_verify_percpu.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580988912,
      "name": "clocksource_verify_percpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void clocksource_verify_percpu(struct clocksource * cs)
```
</details>
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
