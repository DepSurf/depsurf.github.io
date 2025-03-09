# Function: <code>cec_received_msg_ts</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:977",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587262965,
      "name": "cec_received_msg_ts.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
    },
    {
      "addr": 18446744071587255280,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2633
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
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1022",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531746,
      "name": "cec_received_msg_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071587525936,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1266
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
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1036",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587734543,
      "name": "cec_received_msg_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587729024,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1133
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500906456,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1036",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500906456,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1044
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
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233425380,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1036",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233425380,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1028
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
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294364688,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1036",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294364688,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1280
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
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277684320,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1036",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277684320,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 876
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
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1036",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587375487,
      "name": "cec_received_msg_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587369968,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1133
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
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1036",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143711,
      "name": "cec_received_msg_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587138192,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1133
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
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1036",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690687,
      "name": "cec_received_msg_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587685168,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1133
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
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```

```json
{
  "name": "cec_received_msg_ts",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_received_msg_ts",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:1036",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-pin.c:cec_pin_thread_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587797055,
      "name": "cec_received_msg_ts.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071587791536,
      "name": "cec_received_msg_ts",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1133
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void cec_received_msg_ts(struct cec_adapter * adap, struct cec_msg * msg, ktime_t ts)
```
</details>
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
