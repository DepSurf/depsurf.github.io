# Function: <code>wait_for_tpm_stat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584233104,
      "name": "wait_for_tpm_stat",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:876",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis.c:recv_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis.c:tpm_tis_recv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584233104,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 540
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584572880,
      "name": "wait_for_tpm_stat",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:904",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572880,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 539
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584754784,
      "name": "wait_for_tpm_stat",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:889",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754784,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 498
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584835552,
      "name": "wait_for_tpm_stat",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1053",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584835552,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585256704,
      "name": "wait_for_tpm_stat",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:1071",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585256704,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 486
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585521504,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:51",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585521504,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585645600,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:51",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585645600,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 483
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585870528,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870528,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586013088,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586013088,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586751712,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586751712,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586845792,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586845792,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586725872,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586725872,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587277360,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 528
    },
    {
      "addr": 18446744071592465326,
      "name": "wait_for_tpm_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588586752,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 579
    },
    {
      "addr": 18446744071594334731,
      "name": "wait_for_tpm_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590042528,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 573
    },
    {
      "addr": 18446744071596239795,
      "name": "wait_for_tpm_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:64",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590352144,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    },
    {
      "addr": 18446744071596767968,
      "name": "wait_for_tpm_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:64",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590693680,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    },
    {
      "addr": 18446744071597676629,
      "name": "wait_for_tpm_stat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498811616,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498811616,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 552
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231422348,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231422348,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292006512,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292006512,
      "name": "wait_for_tpm_stat",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276309570,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276309570,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585774064,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585774064,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585633248,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585633248,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585963104,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585963104,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int wait_for_tpm_stat(struct tpm_chip * chip, u8 mask, long unsigned int timeout, wait_queue_head_t * queue, bool check_cancel)
```

```json
{
  "name": "wait_for_tpm_stat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586070848,
      "name": "wait_for_tpm_stat",
      "external": false,
      "loc": "drivers/char/tpm/tpm_tis_core.c:47",
      "file": "drivers/char/tpm/tpm_tis_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_main",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_send_data",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv",
        "drivers/char/tpm/tpm_tis_core.c:recv_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070848,
      "name": "wait_for_tpm_stat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
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
