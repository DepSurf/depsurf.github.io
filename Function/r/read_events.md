# Function: <code>read_events</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, struct timespec * timeout)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581318720,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1260",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581318720,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, struct timespec * timeout)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485296,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:SyS_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485296,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 826
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, struct timespec * timeout)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581566368,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1285",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581566368,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 791
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, struct timespec * timeout)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581622416,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1290",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581622416,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767104,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1314",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767104,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581934784,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1238",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934784,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582019264,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582019264,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582155920,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582155920,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582233184,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582233184,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582473248,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582473248,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530288,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1272",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530288,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582558320,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1269",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582558320,
      "name": "read_events",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582874496,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582874496,
      "name": "read_events",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583440592,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1296",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583440592,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584030864,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1297",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584030864,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255184,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1289",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255184,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584468496,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1318",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584468496,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493808752,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493808752,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227318972,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_getevents"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287420160,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287420160,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273389878,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273389878,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582201920,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582201920,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582139568,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139568,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582192400,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582192400,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```

```json
{
  "name": "read_events",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582269200,
      "name": "read_events",
      "external": false,
      "loc": "fs/aio.c:1270",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:do_io_getevents"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582269200,
      "name": "read_events",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 345
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>ktime_t until</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timespec * timeout</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int read_events(struct kioctx * ctx, long int min_nr, long int nr, struct io_event * event, ktime_t until)
```
</details>
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
