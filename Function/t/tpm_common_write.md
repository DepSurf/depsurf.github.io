# Function: <code>tpm_common_write</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584854912,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:88",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_write",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584854912,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585274032,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:87",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_write",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585274032,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off, struct tpm_space * space)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585510944,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:81",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-dev.c:tpm_write",
        "drivers/char/tpm/tpmrm-dev.c:tpmrm_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585510944,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619376,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:128",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619376,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 441
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585840048,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:153",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585840048,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 446
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585982752,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585982752,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586723888,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586723888,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586819520,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586819520,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586699520,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:159",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699520,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 445
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:159",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592463001,
      "name": "tpm_common_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071587248864,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:165",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594332802,
      "name": "tpm_common_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588557728,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:165",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596239564,
      "name": "tpm_common_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590010352,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:165",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596767737,
      "name": "tpm_common_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590319600,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:165",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597676398,
      "name": "tpm_common_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071590660944,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 459
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498777112,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498777112,
      "name": "tpm_common_write",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231392484,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231392484,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 500
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291967984,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291967984,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276271842,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276271842,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 390
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585743728,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743728,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585602912,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585602912,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585932768,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585932768,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off)
```

```json
{
  "name": "tpm_common_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586040752,
      "name": "tpm_common_write",
      "external": true,
      "loc": "drivers/char/tpm/tpm-dev-common.c:160",
      "file": "drivers/char/tpm/tpm-dev-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586040752,
      "name": "tpm_common_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
ssize_t tpm_common_write(struct file * file, const char * buf, size_t size, loff_t * off, struct tpm_space * space)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct tpm_space * space</code>
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
