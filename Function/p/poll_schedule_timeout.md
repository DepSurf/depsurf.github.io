# Function: <code>poll_schedule_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int poll_schedule_timeout(struct poll_wqueues * pwq, int state, ktime_t * expires, long unsigned int slack)
```

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581076496,
      "name": "poll_schedule_timeout",
      "external": true,
      "loc": "fs/select.c:234",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_select",
        "fs/select.c:do_sys_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076496,
      "name": "poll_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int poll_schedule_timeout(struct poll_wqueues * pwq, int state, ktime_t * expires, long unsigned int slack)
```

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581239408,
      "name": "poll_schedule_timeout",
      "external": true,
      "loc": "fs/select.c:234",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581239408,
      "name": "poll_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
int poll_schedule_timeout(struct poll_wqueues * pwq, int state, ktime_t * expires, long unsigned int slack)
```

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581317280,
      "name": "poll_schedule_timeout",
      "external": true,
      "loc": "fs/select.c:235",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581317280,
      "name": "poll_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int poll_schedule_timeout(struct poll_wqueues * pwq, int state, ktime_t * expires, long unsigned int slack)
```

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581370096,
      "name": "poll_schedule_timeout",
      "external": true,
      "loc": "fs/select.c:235",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581370096,
      "name": "poll_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int poll_schedule_timeout(struct poll_wqueues * pwq, int state, ktime_t * expires, long unsigned int slack)
```

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581511584,
      "name": "poll_schedule_timeout",
      "external": true,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581511584,
      "name": "poll_schedule_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581670176,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670176,
      "name": "poll_schedule_timeout.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581756480,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756480,
      "name": "poll_schedule_timeout.constprop.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874112,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874112,
      "name": "poll_schedule_timeout.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581946368,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946368,
      "name": "poll_schedule_timeout.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582179022,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582226219,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582252584,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582570078,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583099631,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:237",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583667804,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:237",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583885157,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:237",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584092325,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:237",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493445856,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227012284,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227012284,
      "name": "poll_schedule_timeout.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287001228,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273134280,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
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
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581915104,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581915104,
      "name": "poll_schedule_timeout.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581852688,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852688,
      "name": "poll_schedule_timeout.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581906416,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581906416,
      "name": "poll_schedule_timeout.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "poll_schedule_timeout",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581976032,
      "name": "poll_schedule_timeout",
      "external": false,
      "loc": "fs/select.c:236",
      "file": "fs/select.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/select.c:do_sys_poll",
        "fs/select.c:do_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581976032,
      "name": "poll_schedule_timeout.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
int poll_schedule_timeout(struct poll_wqueues * pwq, int state, ktime_t * expires, long unsigned int slack)
```
</details>
</li>
</ul>
