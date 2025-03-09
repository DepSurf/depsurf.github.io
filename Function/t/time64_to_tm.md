# Function: <code>time64_to_tm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579896656,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:77",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_time_unix2fat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896656,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 980
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908336,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:77",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_time_unix2fat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908336,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 980
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916832,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:77",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_time_unix2fat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916832,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579962000,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:77",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579962000,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 972
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580009632,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:77",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580009632,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056656,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056656,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 952
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580100208,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580100208,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149184,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149184,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211184,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211184,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580195136,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580195136,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 968
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580200464,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580200464,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 970
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580347520,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:47",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580347520,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580561312,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:47",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580561312,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580820832,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:47",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580820832,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 504
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580904128,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:47",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580904128,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580994656,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:47",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time",
        "lib/vsprintf.c:time64_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994656,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 651
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491369168,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time",
        "drivers/firmware/raspberrypi.c:rpi_firmware_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491369168,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1016
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225368280,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225368280,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284306336,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284306336,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1136
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271859942,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271859942,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 478
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118384,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118384,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580063680,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580063680,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580109456,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580109456,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
```

```json
{
  "name": "time64_to_tm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580161200,
      "name": "time64_to_tm",
      "external": true,
      "loc": "kernel/time/timeconv.c:78",
      "file": "kernel/time/timeconv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/debug/kdb/kdb_main.c:kdb_summary",
        "fs/namespace.c:mnt_warn_timestamp_expiry",
        "fs/fat/misc.c:fat_time_unix2fat",
        "security/tomoyo/util.c:tomoyo_convert_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580161200,
      "name": "time64_to_tm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 982
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
void time64_to_tm(time64_t totalsecs, int offset, struct tm * result)
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
