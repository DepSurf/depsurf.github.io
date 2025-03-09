# Function: <code>tty_ldisc_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583996700,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:188",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584328480,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:195",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584328480,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584510432,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:195",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510432,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584589872,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:195",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584589872,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585001936,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:196",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585001936,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585236208,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:195",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236208,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585355456,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:195",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585355456,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585568656,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585568656,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585709856,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585709856,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586439328,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:199",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586439328,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553856,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:198",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553856,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586438608,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:199",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586438608,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586964160,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:184",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964160,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588259392,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:179",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588259392,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589672832,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:179",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589672832,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 105
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589980892,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:178",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
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
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590319612,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:178",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_release",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498398056,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498398056,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231073384,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231073384,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291580528,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291580528,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276059612,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276059612,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585470880,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470880,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340896,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340896,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585660256,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660256,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void tty_ldisc_put(struct tty_ldisc * ld)
```

```json
{
  "name": "tty_ldisc_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585768368,
      "name": "tty_ldisc_put",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:204",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_deinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_reinit",
        "drivers/tty/tty_ldisc.c:tty_ldisc_kill",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_failto"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585768368,
      "name": "tty_ldisc_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void tty_ldisc_put(struct tty_ldisc * ld)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void tty_ldisc_put(struct tty_ldisc * ld)
```
</details>
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
