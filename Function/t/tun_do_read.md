# Function: <code>tun_do_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585063424,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:1399",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585063424,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585459502,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:1483",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457936,
      "name": "tun_do_read.part.37",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1478
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585663553,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:1474",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661984,
      "name": "tun_do_read.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585750702,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:1511",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585749104,
      "name": "tun_do_read.part.43",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1516
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586187882,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:1958",
      "file": "drivers/net/tun.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586186176,
      "name": "tun_do_read.part.51",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1504
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586446368,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2186",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586446368,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1716
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586593856,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2204",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593856,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1735
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2199",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847200,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1662
    },
    {
      "addr": 18446744071586852667,
      "name": "tun_do_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2203",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586981552,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1662
    },
    {
      "addr": 18446744071586998686,
      "name": "tun_do_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587818192,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2178",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587818192,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1070
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587875904,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2100",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587875904,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587754688,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2105",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587754688,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 452
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588351632,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2161",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588351632,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1101
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589740384,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2193",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589740384,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591358880,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2197",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591358880,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591719552,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2211",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591719552,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592463232,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2223",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592463232,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499974600,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2203",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499974600,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1700
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232520456,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2203",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232520456,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1888
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293319152,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2203",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293319152,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2436
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277054532,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2203",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277054532,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1464
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2203",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586738560,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1662
    },
    {
      "addr": 18446744071586755710,
      "name": "tun_do_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2203",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586605776,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1662
    },
    {
      "addr": 18446744071586622926,
      "name": "tun_do_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2203",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586936112,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1662
    },
    {
      "addr": 18446744071586953246,
      "name": "tun_do_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
```

```json
{
  "name": "tun_do_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tun_do_read",
      "external": false,
      "loc": "drivers/net/tun.c:2203",
      "file": "drivers/net/tun.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/net/tun.c:tun_recvmsg",
        "drivers/net/tun.c:tun_chr_read_iter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044240,
      "name": "tun_do_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1779
    },
    {
      "addr": 18446744071587060334,
      "name": "tun_do_read.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
ssize_t tun_do_read(struct tun_struct * tun, struct tun_file * tfile, struct iov_iter * to, int noblock, void * ptr)
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
