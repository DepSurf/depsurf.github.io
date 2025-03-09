# Function: <code>quota_send_warning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581427392,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:44",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581427392,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 596
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581609728,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:42",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581609728,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581698272,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:36",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581698272,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581752496,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:36",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581752496,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581899616,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899616,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084207,
      "name": "quota_send_warning.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582083680,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178335,
      "name": "quota_send_warning.cold.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582177808,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341472,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582340944,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582440608,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582440080,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_alloc_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734288,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582733760,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_alloc_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591345241,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582805488,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_alloc_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591287912,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582834304,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:__dquot_alloc_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592246973,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071583166896,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 527
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594027709,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    },
    {
      "addr": 18446744071583657968,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 546
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584264192,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584264192,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584494480,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584494480,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 613
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584717440,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:__dquot_transfer",
        "fs/quota/dquot.c:dquot_free_inode",
        "fs/quota/dquot.c:__dquot_free_space",
        "fs/quota/dquot.c:dquot_alloc_inode",
        "fs/quota/dquot.c:__dquot_alloc_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584717440,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 619
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494052592,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494052592,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227513140,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227513140,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287707872,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287707872,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 728
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273553266,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273553266,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 472
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409344,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582408816,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582347040,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582346512,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582399824,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582399296,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
void quota_send_warning(struct kqid qid, dev_t dev, const char warntype)
```

```json
{
  "name": "quota_send_warning",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "quota_send_warning",
      "external": true,
      "loc": "fs/quota/netlink.c:37",
      "file": "fs/quota/netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/quota/dquot.c:flush_warnings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582479360,
      "name": "quota_send_warning.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582478832,
      "name": "quota_send_warning",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
