# Function: <code>tty_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583963552,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1228",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583963552,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 720
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289520,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1236",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289520,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 748
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471616,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1236",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471616,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 743
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584557392,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1001",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557392,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 787
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584967888,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1013",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584967888,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 785
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1031",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585201392,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 814
    },
    {
      "addr": 18446744071585214656,
      "name": "tty_write.cold.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1023",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319840,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 768
    },
    {
      "addr": 18446744071585333600,
      "name": "tty_write.cold.34",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585541408,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071585547064,
      "name": "tty_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585682320,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071585687935,
      "name": "tty_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1026",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586400096,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 197
    },
    {
      "addr": 18446744071586415762,
      "name": "tty_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t tty_write(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586519541,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1122",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586517360,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t tty_write(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586405477,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1138",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402688,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t tty_write(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586932261,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1129",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586929536,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t tty_write(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588224385,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1114",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588224432,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t tty_write(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589634913,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1108",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589634976,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t tty_write(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589938561,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1117",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589938624,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
ssize_t tty_write(struct kiocb * iocb, struct iov_iter * from)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590277441,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1115",
      "file": "drivers/tty/tty_io.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590277504,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498349104,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498349104,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 920
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231045400,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231045400,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291529840,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291529840,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276027842,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276027842,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585443344,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071585448959,
      "name": "tty_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585313376,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071585318991,
      "name": "tty_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585632720,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 666
    },
    {
      "addr": 18446744071585638335,
      "name": "tty_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
ssize_t tty_write(struct file * file, const char * buf, size_t count, loff_t * ppos)
```

```json
{
  "name": "tty_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tty_write",
      "external": false,
      "loc": "drivers/tty/tty_io.c:1025",
      "file": "drivers/tty/tty_io.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_io.c:redirected_tty_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585740832,
      "name": "tty_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
    },
    {
      "addr": 18446744071585746471,
      "name": "tty_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kiocb * iocb</code>
</li>
<li>
<b>Param added. </b>
<code>struct iov_iter * from</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file * file</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t * ppos</code>
</li>
</ul>
</details>
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
