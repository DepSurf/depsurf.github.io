# Function: <code>__do_sys_reboot</code>

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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579591008,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:307",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579591008,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628528,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:308",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628528,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 522
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579653392,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579653392,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579690512,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579690512,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579731024,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071579731872,
      "name": "__do_sys_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579711248,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071591281539,
      "name": "__do_sys_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718656,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071591224486,
      "name": "__do_sys_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:311",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579797024,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 506
    },
    {
      "addr": 18446744071592106152,
      "name": "__do_sys_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:683",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579905968,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 559
    },
    {
      "addr": 18446744071593873828,
      "name": "__do_sys_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580058816,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:700",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058816,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 565
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580113264,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:700",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580113264,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 572
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580158448,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:715",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158448,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 586
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490869000,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__arm64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490869000,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224887096,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__se_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224887096,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283700000,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__se_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283700000,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 680
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271524266,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__se_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271524266,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579666832,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666832,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579595184,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579595184,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664064,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664064,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
```

```json
{
  "name": "__do_sys_reboot",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579698096,
      "name": "__do_sys_reboot",
      "external": false,
      "loc": "kernel/reboot.c:310",
      "file": "kernel/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/reboot.c:__ia32_sys_reboot",
        "kernel/reboot.c:__x64_sys_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579698096,
      "name": "__do_sys_reboot",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void * arg)
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
