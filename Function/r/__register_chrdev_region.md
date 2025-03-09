# Function: <code>__register_chrdev_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010912,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:74",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:register_chrdev_region",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:__register_chrdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010912,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169360,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:74",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169360,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581246336,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:74",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581246336,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581294368,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:74",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581294368,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581434048,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:100",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581434048,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:100",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581591648,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071581593562,
      "name": "__register_chrdev_region.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:100",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581676912,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 509
    },
    {
      "addr": 18446744071581679546,
      "name": "__register_chrdev_region.cold.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581794816,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071581797605,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581867424,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071581870202,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582093696,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 642
    },
    {
      "addr": 18446744071582096381,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582139952,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1215
    },
    {
      "addr": 18446744071591339449,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582164816,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1207
    },
    {
      "addr": 18446744071591282165,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582481920,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
    },
    {
      "addr": 18446744071592229170,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583003152,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1074
    },
    {
      "addr": 18446744071594008752,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583565056,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583565056,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1165
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583781472,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583781472,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 833
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583987024,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583987024,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 878
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493339632,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493339632,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226933132,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226933132,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 728
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286885216,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286885216,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273069616,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273069616,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 594
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581836160,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071581838938,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773824,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071581776602,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827472,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071581830250,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct char_device_struct * __register_chrdev_region(unsigned int major, unsigned int baseminor, int minorct, const char * name)
```

```json
{
  "name": "__register_chrdev_region",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__register_chrdev_region",
      "external": false,
      "loc": "fs/char_dev.c:97",
      "file": "fs/char_dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/char_dev.c:__register_chrdev",
        "fs/char_dev.c:alloc_chrdev_region",
        "fs/char_dev.c:register_chrdev_region"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581896752,
      "name": "__register_chrdev_region",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071581899416,
      "name": "__register_chrdev_region.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
