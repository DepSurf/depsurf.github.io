# Function: <code>__hwspin_lock_request</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587305712,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:486",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587305712,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587607712,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:513",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587607712,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587735968,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:624",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735968,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588021040,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071588022847,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588228656,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071588230324,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589103072,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071589105051,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589102384,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071591615375,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588991616,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071591558462,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589705680,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071592679072,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591213456,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071594564453,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592956640,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592956640,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593407008,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593407008,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594152720,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:651",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594152720,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501684440,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501684440,
      "name": "__hwspin_lock_request",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234211200,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234211200,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295116304,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295116304,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278120820,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278120820,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587840352,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071587842020,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587547264,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071587548350,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588183136,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071588184804,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
int __hwspin_lock_request(struct hwspinlock * hwlock)
```

```json
{
  "name": "__hwspin_lock_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__hwspin_lock_request",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:646",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific",
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588301184,
      "name": "__hwspin_lock_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071588302668,
      "name": "__hwspin_lock_request.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __hwspin_lock_request(struct hwspinlock * hwlock)
```
</details>
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
