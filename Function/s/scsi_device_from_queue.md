# Function: <code>scsi_device_from_queue</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585353856,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2155",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585353856,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585439280,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2235",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439280,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869696,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2313",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869696,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586115984,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2329",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115984,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586266688,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1923",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586266688,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586510144,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1876",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586510144,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586658080,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1922",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586658080,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587453840,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1919",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params",
        "drivers/scsi/scsi_dh.c:scsi_dh_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587453840,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587532256,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1943",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params",
        "drivers/scsi/scsi_dh.c:scsi_dh_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587532256,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587414560,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1959",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params",
        "drivers/scsi/scsi_dh.c:scsi_dh_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587414560,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587986880,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1949",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params",
        "drivers/scsi/scsi_dh.c:scsi_dh_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587986880,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589327920,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2004",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params",
        "drivers/scsi/scsi_dh.c:scsi_dh_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589327920,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590911744,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2009",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params",
        "drivers/scsi/scsi_dh.c:scsi_dh_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590911744,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591255056,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2015",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params",
        "drivers/scsi/scsi_dh.c:scsi_dh_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591255056,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591602272,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2012",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params",
        "drivers/scsi/scsi_dh.c:scsi_dh_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591602272,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499555632,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1922",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499555632,
      "name": "scsi_device_from_queue",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232019532,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1922",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232019532,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292851952,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1922",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292851952,
      "name": "scsi_device_from_queue",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276754946,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1922",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276754946,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586348560,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1922",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586348560,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586189888,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1922",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586189888,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586606048,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1922",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606048,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```

```json
{
  "name": "scsi_device_from_queue",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586718448,
      "name": "scsi_device_from_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1922",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_dh.c:scsi_dh_attached_handler_name",
        "drivers/scsi/scsi_dh.c:scsi_dh_attach",
        "drivers/scsi/scsi_dh.c:scsi_dh_set_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718448,
      "name": "scsi_device_from_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct scsi_device * scsi_device_from_queue(struct request_queue * q)
```
</details>
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
