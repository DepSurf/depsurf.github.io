# Function: <code>cec_transmit_msg_fh</code>

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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:719",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587262573,
      "name": "cec_transmit_msg_fh.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
    },
    {
      "addr": 18446744071587253616,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1443
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:732",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531177,
      "name": "cec_transmit_msg_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071587522544,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587733974,
      "name": "cec_transmit_msg_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071587725632,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500902920,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500902920,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1800
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233421632,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233421632,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1688
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294359856,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294359856,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2272
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277681162,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277681162,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1558
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587374918,
      "name": "cec_transmit_msg_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071587366576,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587143142,
      "name": "cec_transmit_msg_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071587134800,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587690118,
      "name": "cec_transmit_msg_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071587681776,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
```

```json
{
  "name": "cec_transmit_msg_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_transmit_msg_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:746",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_thread_func",
        "drivers/media/cec/cec-adap.c:cec_config_log_addr",
        "drivers/media/cec/cec-adap.c:cec_transmit_msg",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587796486,
      "name": "cec_transmit_msg_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071587788144,
      "name": "cec_transmit_msg_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1608
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
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
int cec_transmit_msg_fh(struct cec_adapter * adap, struct cec_msg * msg, struct cec_fh * fh, bool block)
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
