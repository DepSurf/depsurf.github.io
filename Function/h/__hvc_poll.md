# Function: <code>__hvc_poll</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585445632,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585445632,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585660768,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660768,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585801744,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801744,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586532016,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:632",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532016,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586643376,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:632",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586643376,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 820
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586527328,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:632",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586527328,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 823
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587065152,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:632",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587065152,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 931
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588367920,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:632",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588367920,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:632",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589789824,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1077
    },
    {
      "addr": 18446744071596235649,
      "name": "__hvc_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:632",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590094912,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1074
    },
    {
      "addr": 18446744071596763585,
      "name": "__hvc_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:632",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590434192,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1106
    },
    {
      "addr": 18446744071597672213,
      "name": "__hvc_poll.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498522840,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498522840,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231172968,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231172968,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 832
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291738944,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291738944,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1180
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276146358,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276146358,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585562736,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585562736,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432560,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432560,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585752144,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585752144,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
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
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```

```json
{
  "name": "__hvc_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585860112,
      "name": "__hvc_poll",
      "external": false,
      "loc": "drivers/tty/hvc/hvc_console.c:643",
      "file": "drivers/tty/hvc/hvc_console.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/hvc/hvc_console.c:khvcd",
        "drivers/tty/hvc/hvc_console.c:hvc_poll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585860112,
      "name": "__hvc_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int __hvc_poll(struct hvc_struct * hp, bool may_sleep)
```
</details>
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
