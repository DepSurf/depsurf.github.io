# Function: <code>bsg_setup_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int bsg_setup_queue(struct device * dev, struct request_queue * q, char * name, bsg_job_fn * job_fn, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582870544,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:211",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582870544,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int bsg_setup_queue(struct device * dev, struct request_queue * q, char * name, bsg_job_fn * job_fn, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156480,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:211",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156480,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
int bsg_setup_queue(struct device * dev, struct request_queue * q, char * name, bsg_job_fn * job_fn, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583268480,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:230",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583268480,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
struct request_queue * bsg_setup_queue(struct device * dev, char * name, bsg_job_fn * job_fn, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323664,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:242",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323664,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, int dd_job_size, void (*)(struct device *) release)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583506640,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:255",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583506640,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:307",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583722015,
      "name": "bsg_setup_queue.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071583720560,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 251
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:340",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583828555,
      "name": "bsg_setup_queue.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071583827728,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:360",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584019009,
      "name": "bsg_setup_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584017952,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584122596,
      "name": "bsg_setup_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584121552,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584520680,
      "name": "bsg_setup_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584520176,
      "name": "bsg_setup_queue",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:365",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591377772,
      "name": "bsg_setup_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584628864,
      "name": "bsg_setup_queue",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:365",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591320012,
      "name": "bsg_setup_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584657024,
      "name": "bsg_setup_queue",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585070704,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:366",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585070704,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
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
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585795552,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:360",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585795552,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
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
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586576800,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:361",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576800,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586834560,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:361",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586834560,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587111680,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:361",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587111680,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 359
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
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495967632,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495967632,
      "name": "bsg_setup_queue",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229310284,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3229310284,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290189984,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290189984,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 484
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
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275070916,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275070916,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584091332,
      "name": "bsg_setup_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584090288,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_transport_fc.c:fc_remote_port_create",
        "drivers/scsi/scsi_transport_fc.c:fc_host_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584027092,
      "name": "bsg_setup_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584026048,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584075092,
      "name": "bsg_setup_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584074048,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct request_queue * bsg_setup_queue(struct device * dev, const char * name, bsg_job_fn * job_fn, bsg_timeout_fn * timeout, int dd_job_size)
```

```json
{
  "name": "bsg_setup_queue",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bsg_setup_queue",
      "external": true,
      "loc": "block/bsg-lib.c:362",
      "file": "block/bsg-lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584177668,
      "name": "bsg_setup_queue.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584176624,
      "name": "bsg_setup_queue",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 269
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
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue * q</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, q, name, job_fn, dd_job_size</code> ➡️ <code>dev, name, job_fn, dd_job_size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct request_queue *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*)(struct device *) release</code>
</li>
<li>
<b>Param type changed. </b>
<code>char * name</code> ➡️ <code>const char * name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void (*)(struct device *) release</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bsg_timeout_fn * timeout</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, name, job_fn, dd_job_size</code> ➡️ <code>dev, name, job_fn, timeout, dd_job_size</code>
</li>
</ul>
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
