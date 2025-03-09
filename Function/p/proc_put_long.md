# Function: <code>proc_put_long</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579400864,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2009",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579400864,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414656,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2129",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414656,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579434960,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2114",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579434960,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579420864,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2138",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579420864,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579450816,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2130",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450816,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2135",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465696,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071579471138,
      "name": "proc_put_long.cold.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2183",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499312,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071579504804,
      "name": "proc_put_long.cold.20",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2269",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517424,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071579523834,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2271",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543504,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071579549914,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:500",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579573632,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071579581530,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:499",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579555248,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 294
    },
    {
      "addr": 18446744071591278742,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:511",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579559872,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071591221640,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:520",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632448,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    },
    {
      "addr": 18446744071592100720,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:400",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579728208,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
    },
    {
      "addr": 18446744071593868292,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
void proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858368,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:402",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858368,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
void proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579908544,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:401",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579908544,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
void proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947792,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:401",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947792,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490691512,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2271",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490691512,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224759576,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2271",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224759576,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283517712,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2271",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283517712,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271421290,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2271",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271421290,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2271",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517168,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071579523578,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2271",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445968,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071579452378,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2271",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579517088,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071579523498,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int proc_put_long(void * * buf, size_t * size, long unsigned int val, bool neg)
```

```json
{
  "name": "proc_put_long",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_put_long",
      "external": false,
      "loc": "kernel/sysctl.c:2271",
      "file": "kernel/sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550048,
      "name": "proc_put_long",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
    },
    {
      "addr": 18446744071579556458,
      "name": "proc_put_long.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
