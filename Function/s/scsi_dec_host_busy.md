# Function: <code>scsi_dec_host_busy</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585876048,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:330",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876048,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586122112,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:343",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_request_fn",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586122112,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586267024,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:335",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586267024,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586510560,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586510560,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586658512,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586658512,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void scsi_dec_host_busy(struct Scsi_Host * shost, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587459629,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:321",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587454368,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void scsi_dec_host_busy(struct Scsi_Host * shost, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587522736,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:306",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587522736,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void scsi_dec_host_busy(struct Scsi_Host * shost, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587404480,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:272",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587404480,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void scsi_dec_host_busy(struct Scsi_Host * shost, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587976448,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:277",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587976448,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
void scsi_dec_host_busy(struct Scsi_Host * shost, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589325680,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:278",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325680,
      "name": "scsi_dec_host_busy",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void scsi_dec_host_busy(struct Scsi_Host * shost, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590891936,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:276",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590891936,
      "name": "scsi_dec_host_busy",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void scsi_dec_host_busy(struct Scsi_Host * shost, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591235360,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:274",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591235360,
      "name": "scsi_dec_host_busy",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void scsi_dec_host_busy(struct Scsi_Host * shost, struct scsi_cmnd * cmd)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591582608,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:274",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591582608,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499558768,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499558768,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232020408,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232020408,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292852736,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292852736,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276755834,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:__scsi_queue_insert"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276755834,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586348992,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586348992,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586190320,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190320,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586606480,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586606480,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
```

```json
{
  "name": "scsi_dec_host_busy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586718880,
      "name": "scsi_dec_host_busy",
      "external": false,
      "loc": "drivers/scsi/scsi_lib.c:332",
      "file": "drivers/scsi/scsi_lib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_queue_rq",
        "drivers/scsi/scsi_lib.c:scsi_device_unbusy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718880,
      "name": "scsi_dec_host_busy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void scsi_dec_host_busy(struct Scsi_Host * shost)
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
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scsi_cmnd * cmd</code>
</li>
</ul>
</details>
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
