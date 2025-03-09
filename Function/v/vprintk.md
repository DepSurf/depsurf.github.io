# Function: <code>vprintk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579732432,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:1825",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/compat.c:compat_printk",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ecryptfs/main.c:__ecryptfs_printk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579732432,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579751552,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:1912",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/compat.c:compat_printk",
        "fs/ext4/super.c:__ext4_abort",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579751552,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579777712,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:1804",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579777712,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770352,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:1776",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770352,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803376,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:1764",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803376,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836880,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:1925",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836880,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883808,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:1941",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883808,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917408,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:1996",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917408,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579967456,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2006",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967456,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580014416,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2031",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580014416,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992512,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2107",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992512,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580008784,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:360",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/printk/printk.c:printk",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008784,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580140432,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:29",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/printk/printk.c:_printk",
        "kernel/time/timer_list.c:SEQ_printf",
        "mm/kfence/report.c:seq_con_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140432,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580284176,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:29",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/printk/printk.c:_printk",
        "kernel/time/timer_list.c:SEQ_printf",
        "mm/kfence/report.c:seq_con_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580284176,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580493856,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:29",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/printk/printk.c:_printk",
        "kernel/time/timer_list.c:SEQ_printf",
        "mm/kfence/report.c:seq_con_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580493856,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580565696,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:29",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/printk/printk.c:_printk",
        "kernel/time/timer_list.c:SEQ_printf",
        "mm/kfence/report.c:seq_con_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580565696,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580628752,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk_safe.c:29",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/printk/printk.c:_printk",
        "kernel/time/timer_list.c:SEQ_printf",
        "mm/kfence/report.c:seq_con_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580628752,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
int vprintk(const char * fmt, va_list args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491148048,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2006",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491148048,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int vprintk(const char * fmt, va_list args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225177808,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2006",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225177808,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int vprintk(const char * fmt, va_list args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284045648,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2006",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284045648,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int vprintk(const char * fmt, va_list args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271705682,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2006",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271705682,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579936192,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2006",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579936192,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579874464,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2006",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874464,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579927728,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2006",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927728,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int vprintk(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "vprintk",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579973712,
      "name": "vprintk",
      "external": true,
      "loc": "kernel/printk/printk.c:2006",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:__warn_printk",
        "kernel/panic.c:__warn",
        "kernel/time/timer_list.c:SEQ_printf",
        "fs/ecryptfs/main.c:__ecryptfs_printk",
        "drivers/net/phy/phy_device.c:phy_attached_print"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579973712,
      "name": "vprintk",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
