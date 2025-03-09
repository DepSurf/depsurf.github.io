# Function: <code>cec_receive_notify</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587255912,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1812",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1873",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524384,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1541
    },
    {
      "addr": 18446744071587531626,
      "name": "cec_receive_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1890",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727472,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1541
    },
    {
      "addr": 18446744071587734423,
      "name": "cec_receive_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500905008,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1890",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500905008,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1444
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
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233423604,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1890",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233423604,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1776
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
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294362480,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1890",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294362480,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2204
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
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277682954,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1890",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277682954,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1366
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
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1890",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368416,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1541
    },
    {
      "addr": 18446744071587375367,
      "name": "cec_receive_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1890",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136640,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1541
    },
    {
      "addr": 18446744071587143591,
      "name": "cec_receive_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1890",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587683616,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1541
    },
    {
      "addr": 18446744071587690567,
      "name": "cec_receive_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```

```json
{
  "name": "cec_receive_notify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_receive_notify",
      "external": false,
      "loc": "drivers/media/cec/cec-adap.c:1890",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587789984,
      "name": "cec_receive_notify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1541
    },
    {
      "addr": 18446744071587796935,
      "name": "cec_receive_notify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int cec_receive_notify(struct cec_adapter * adap, struct cec_msg * msg, bool is_reply)
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
