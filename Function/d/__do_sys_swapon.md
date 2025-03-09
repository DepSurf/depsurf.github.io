# Function: <code>__do_sys_swapon</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3112",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581258032,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4496
    },
    {
      "addr": 18446744071581263644,
      "name": "__do_sys_swapon.cold.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3090",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581340976,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4417
    },
    {
      "addr": 18446744071581346812,
      "name": "__do_sys_swapon.cold.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3102",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581451424,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4301
    },
    {
      "addr": 18446744071581457182,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3098",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581515648,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4231
    },
    {
      "addr": 18446744071581521315,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3142",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581724688,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2707
    },
    {
      "addr": 18446744071581729015,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3161",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581772848,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2606
    },
    {
      "addr": 18446744071591331865,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3132",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800208,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2800
    },
    {
      "addr": 18446744071591274512,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3127",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084624,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3174
    },
    {
      "addr": 18446744071592209577,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:2982",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582524464,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3232
    },
    {
      "addr": 18446744071593987681,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:2984",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583024000,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3316
    },
    {
      "addr": 18446744071596039251,
      "name": "__do_sys_swapon.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:2975",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583233680,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3302
    },
    {
      "addr": 18446744071596561381,
      "name": "__do_sys_swapon.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:2980",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583470192,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2970
    },
    {
      "addr": 18446744071597466995,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492938904,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3098",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__arm64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492938904,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4128
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226725100,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3098",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__se_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226725100,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4384
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286350640,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3098",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__se_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286350640,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 5728
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272856474,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3098",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__se_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272856474,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3892
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3098",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581484384,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4231
    },
    {
      "addr": 18446744071581490051,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3098",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581426640,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4231
    },
    {
      "addr": 18446744071581432307,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3098",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475696,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4231
    },
    {
      "addr": 18446744071581481363,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
```

```json
{
  "name": "__do_sys_swapon",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_swapon",
      "external": false,
      "loc": "mm/swapfile.c:3098",
      "file": "mm/swapfile.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/swapfile.c:__ia32_sys_swapon",
        "mm/swapfile.c:__x64_sys_swapon"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581540448,
      "name": "__do_sys_swapon",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 4211
    },
    {
      "addr": 18446744071581546116,
      "name": "__do_sys_swapon.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
long int __do_sys_swapon(const char * specialfile, int swap_flags)
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
