# Function: <code>flush_sigqueue_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579422496,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:659",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579422496,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435248,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:659",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435248,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579455600,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:665",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579455600,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579443440,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:679",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579443440,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579471744,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:681",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471744,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486112,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:687",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486112,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519616,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:764",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519616,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539296,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:774",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539296,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565296,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565296,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579598800,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579598800,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579579008,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:780",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579579008,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579584688,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579584688,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:780",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658880,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    },
    {
      "addr": 18446744071592101373,
      "name": "flush_sigqueue_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:786",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756064,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071593868928,
      "name": "flush_sigqueue_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:786",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579888512,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 273
    },
    {
      "addr": 18446744071595974476,
      "name": "flush_sigqueue_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:791",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937760,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071596492085,
      "name": "flush_sigqueue_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:782",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579977088,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071597388846,
      "name": "flush_sigqueue_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490725368,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490725368,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224780904,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224780904,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283549280,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283549280,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271439786,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271439786,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541600,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541600,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470448,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470448,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579538880,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579538880,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
void flush_sigqueue_mask(sigset_t * mask, struct sigpending * s)
```

```json
{
  "name": "flush_sigqueue_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579572448,
      "name": "flush_sigqueue_mask",
      "external": false,
      "loc": "kernel/signal.c:779",
      "file": "kernel/signal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:do_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:kernel_sigaction",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal",
        "kernel/signal.c:prepare_signal"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579572448,
      "name": "flush_sigqueue_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
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
