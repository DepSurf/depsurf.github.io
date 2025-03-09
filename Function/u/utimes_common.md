# Function: <code>utimes_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int utimes_common(struct path * path, struct timespec * times)
```

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581207584,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:51",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581207584,
      "name": "utimes_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int utimes_common(struct path * path, struct timespec * times)
```

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581372256,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:51",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581372256,
      "name": "utimes_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
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
int utimes_common(const struct path * path, struct timespec * times)
```

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581450048,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:51",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581450048,
      "name": "utimes_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
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
int utimes_common(const struct path * path, struct timespec * times)
```

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504112,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:47",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504112,
      "name": "utimes_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
int utimes_common(const struct path * path, struct timespec * times)
```

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581646224,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:48",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581646224,
      "name": "utimes_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581805120,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:48",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581805120,
      "name": "utimes_common.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581892128,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581892128,
      "name": "utimes_common.isra.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582017328,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582017328,
      "name": "utimes_common.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582095248,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582095248,
      "name": "utimes_common.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
int utimes_common(const struct path * path, struct timespec64 * times)
```

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582332736,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332736,
      "name": "utimes_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493631344,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493631344,
      "name": "utimes_common.isra.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int utimes_common(const struct path * path, struct timespec64 * times)
```

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227171576,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227171576,
      "name": "utimes_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287222336,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287222336,
      "name": "utimes_common.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 600
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273271230,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273271230,
      "name": "utimes_common.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582063984,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063984,
      "name": "utimes_common.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582001536,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582001536,
      "name": "utimes_common.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582055264,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582055264,
      "name": "utimes_common.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
  "name": "utimes_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582126944,
      "name": "utimes_common",
      "external": false,
      "loc": "fs/utimes.c:19",
      "file": "fs/utimes.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/utimes.c:do_utimes",
        "fs/utimes.c:do_utimes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582126944,
      "name": "utimes_common.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path * path</code> ➡️ <code>const struct path * path</code>
</li>
</ul>
</details>
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
int utimes_common(const struct path * path, struct timespec * times)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int utimes_common(const struct path * path, struct timespec64 * times)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int utimes_common(const struct path * path, struct timespec64 * times)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int utimes_common(const struct path * path, struct timespec64 * times)
```
</details>
</li>
</ul>
