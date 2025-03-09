# Function: <code>bpf_verifier_vlog</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580645584,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:196",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580645584,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580708512,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:241",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580708512,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580782912,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782912,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580833840,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833840,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:268",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:bpf_log",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581022436,
      "name": "bpf_verifier_vlog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580963184,
      "name": "bpf_verifier_vlog",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:272",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:bpf_log",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591322934,
      "name": "bpf_verifier_vlog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580963520,
      "name": "bpf_verifier_vlog",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:bpf_log",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591264798,
      "name": "bpf_verifier_vlog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580965968,
      "name": "bpf_verifier_vlog",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:292",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:bpf_log",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592181054,
      "name": "bpf_verifier_vlog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
    },
    {
      "addr": 18446744071581174352,
      "name": "bpf_verifier_vlog",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:293",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:bpf_log",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593955018,
      "name": "bpf_verifier_vlog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581453984,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:294",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:bpf_log",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596014657,
      "name": "bpf_verifier_vlog.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071581809792,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 524
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582131168,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/log.c:57",
      "file": "kernel/bpf/log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/log.c:bpf_log",
        "kernel/bpf/log.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582131168,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582272944,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/log.c:59",
      "file": "kernel/bpf/log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/log.c:verbose_linfo",
        "kernel/bpf/log.c:bpf_log",
        "kernel/bpf/log.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582272944,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 824
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, va_list args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492157384,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492157384,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, va_list args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226054176,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226054176,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, va_list args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285368656,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285368656,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, va_list args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272317300,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272317300,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580802640,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580802640,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580748816,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748816,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580793888,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580793888,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "bpf_verifier_vlog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852272,
      "name": "bpf_verifier_vlog",
      "external": true,
      "loc": "kernel/bpf/verifier.c:233",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:verbose_linfo",
        "kernel/bpf/verifier.c:verbose",
        "kernel/bpf/verifier.c:bpf_verifier_log_write",
        "kernel/bpf/btf.c:btf_verifier_log_vsi",
        "kernel/bpf/btf.c:btf_verifier_log_member",
        "kernel/bpf/btf.c:__btf_verifier_log_type",
        "kernel/bpf/btf.c:btf_verifier_log",
        "kernel/bpf/btf.c:__btf_verifier_log"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852272,
      "name": "bpf_verifier_vlog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void bpf_verifier_vlog(struct bpf_verifier_log * log, const char * fmt, struct __va_list_tag * args)
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
