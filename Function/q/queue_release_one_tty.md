# Function: <code>queue_release_one_tty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583955520,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1647",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:proc_clear_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583955520,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584287232,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1649",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:proc_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287232,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584469328,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1649",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self",
        "drivers/tty/tty_io.c:__tty_hangup",
        "drivers/tty/tty_io.c:__proc_set_tty",
        "drivers/tty/tty_io.c:proc_clear_tty"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584469328,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584554546,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1417",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_kref_put"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584965536,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1435",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584965536,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585199056,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1453",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585199056,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585317760,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1465",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317760,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585530576,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585530576,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585671456,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671456,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586415202,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1471",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586530861,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1552",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_open_by_driver",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586415338,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1567",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586942346,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1559",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588236672,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1549",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589647263,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1544",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589951133,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1553",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590289627,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1551",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
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
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498344712,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3231036928,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291525628,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:tty_kref_put"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276025036,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276025036,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585432480,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585432480,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585302528,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585302528,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585621856,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585621856,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```

```json
{
  "name": "queue_release_one_tty",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585730176,
      "name": "queue_release_one_tty",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1467",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_open",
        "drivers/tty/tty_io.c:tty_kopen",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:release_tty",
        "drivers/tty/tty_io.c:tty_vhangup_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730176,
      "name": "queue_release_one_tty",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void queue_release_one_tty(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void queue_release_one_tty(struct kref * kref)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void queue_release_one_tty(struct kref * kref)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void queue_release_one_tty(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void queue_release_one_tty(struct kref * kref)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void queue_release_one_tty(struct kref * kref)
```
</details>
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
