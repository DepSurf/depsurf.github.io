# Function: <code>tty_ldisc_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583997301,
      "name": "tty_ldisc_unlock",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:337",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584330160,
      "name": "tty_ldisc_unlock",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:347",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584512096,
      "name": "tty_ldisc_unlock",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:347",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584591792,
      "name": "tty_ldisc_unlock",
      "external": false,
      "loc": "drivers/tty/tty_ldisc.c:350",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585003926,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585003440,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585238055,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:337",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585237552,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585356352,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:342",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585356352,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585569744,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585569744,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585710848,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585710848,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586439984,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:346",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586439984,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586554512,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:345",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586554512,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586439504,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:346",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586439504,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586965312,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:331",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965312,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588260656,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:321",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588260656,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589674192,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:321",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589674192,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589978336,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:320",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589978336,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590317056,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:320",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590317056,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498399192,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498399192,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231074400,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231074400,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291582432,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291582432,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276061406,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276060958,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585471872,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585471872,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585341888,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341888,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585661248,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661248,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void tty_ldisc_unlock(struct tty_struct * tty)
```

```json
{
  "name": "tty_ldisc_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585769360,
      "name": "tty_ldisc_unlock",
      "external": true,
      "loc": "drivers/tty/tty_ldisc.c:351",
      "file": "drivers/tty/tty_ldisc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_io.c:tty_reopen",
        "drivers/tty/tty_ldisc.c:tty_ldisc_hangup",
        "drivers/tty/tty_ldisc.c:tty_set_ldisc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585769360,
      "name": "tty_ldisc_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void tty_ldisc_unlock(struct tty_struct * tty)
```
</details>
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
