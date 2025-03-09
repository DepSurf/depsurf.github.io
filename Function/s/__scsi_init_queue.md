# Function: <code>__scsi_init_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584799376,
      "name": "__scsi_init_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:2098",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:__scsi_alloc_queue",
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799376,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585159568,
      "name": "__scsi_init_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:2014",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/scsi_lib.c:__scsi_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585159568,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585353392,
      "name": "__scsi_init_queue",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:2032",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/scsi_lib.c:__scsi_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585353392,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585438880,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2068",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/scsi_lib.c:scsi_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585438880,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869296,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2141",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/scsi_lib.c:scsi_old_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869296,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 358
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586115664,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:2156",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/scsi_lib.c:scsi_old_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115664,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586261680,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1822",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586261680,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586506144,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1769",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586506144,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586654032,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1782",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586654032,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587449504,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1778",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587449504,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587517664,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1800",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587517664,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587399264,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1811",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587399264,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587970912,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1813",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587970912,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589326752,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1870",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589326752,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590892960,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1875",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590892960,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591236400,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1879",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591236400,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591583648,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1876",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_scan.c:scsi_alloc_sdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591583648,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499551392,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1782",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499551392,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232015736,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1782",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232015736,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292846064,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1782",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292846064,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276751234,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1782",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276751234,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 284
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586344512,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1782",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586344512,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586185840,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1782",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue",
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_create",
        "drivers/scsi/scsi_transport_fc.c:fc_host_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586185840,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586602000,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1782",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602000,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void __scsi_init_queue(struct Scsi_Host * shost, struct request_queue * q)
```

```json
{
  "name": "__scsi_init_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586714272,
      "name": "__scsi_init_queue",
      "external": true,
      "loc": "drivers/scsi/scsi_lib.c:1782",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_mq_alloc_queue"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586714272,
      "name": "__scsi_init_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
