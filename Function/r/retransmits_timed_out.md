# Function: <code>retransmits_timed_out</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool retransmits_timed_out(struct sock * sk, unsigned int boundary, unsigned int timeout, bool syn_set)
```

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586683152,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:131",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586683152,
      "name": "retransmits_timed_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
bool retransmits_timed_out(struct sock * sk, unsigned int boundary, unsigned int timeout, bool syn_set)
```

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587130080,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:151",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587130080,
      "name": "retransmits_timed_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
bool retransmits_timed_out(struct sock * sk, unsigned int boundary, unsigned int timeout, bool syn_set)
```

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587328464,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:151",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328464,
      "name": "retransmits_timed_out",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587462932,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:148",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587461456,
      "name": "retransmits_timed_out.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587984972,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:159",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587983552,
      "name": "retransmits_timed_out.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588335516,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:159",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588333952,
      "name": "retransmits_timed_out.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588524733,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:190",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588523184,
      "name": "retransmits_timed_out.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588935887,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588933808,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589160065,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157792,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590130444,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590126304,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590178177,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:209",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590173968,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590092543,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:209",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590088128,
      "name": "retransmits_timed_out.part.0",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590867774,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:209",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590862848,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071592719475,
      "name": "retransmits_timed_out.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592504430,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:209",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592499568,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
    },
    {
      "addr": 18446744071594605916,
      "name": "retransmits_timed_out.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594360528,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:209",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594355376,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 475
    },
    {
      "addr": 18446744071596341159,
      "name": "retransmits_timed_out.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594748678,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:209",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594743136,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    },
    {
      "addr": 18446744071596870463,
      "name": "retransmits_timed_out.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595554579,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:215",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout",
        "net/ipv4/tcp_timer.c:tcp_write_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595548832,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 515
    },
    {
      "addr": 18446744071597794067,
      "name": "retransmits_timed_out.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336502776900,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502773144,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3235480828,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235478616,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 400
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055296411008,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296408624,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278897590,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278895638,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588766449,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588764176,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588478385,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588476112,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589202625,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589200352,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
  "name": "retransmits_timed_out",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589242753,
      "name": "retransmits_timed_out",
      "external": false,
      "loc": "net/ipv4/tcp_timer.c:191",
      "file": "net/ipv4/tcp_timer.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ],
      "caller_func": [
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer",
        "net/ipv4/tcp_timer.c:tcp_retransmit_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589240480,
      "name": "retransmits_timed_out.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool retransmits_timed_out(struct sock * sk, unsigned int boundary, unsigned int timeout, bool syn_set)
```
</details>
</li>
</ul>
