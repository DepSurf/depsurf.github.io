# Function: <code>cec_transmit_msg</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587255072,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:867",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts",
        "drivers/media/cec/cec-adap.c:cec_received_msg_ts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587255072,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587524160,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:912",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587524160,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587727248,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:926",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587727248,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500904720,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:926",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500904720,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233423320,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:926",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233423320,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294362128,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:926",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294362128,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277682720,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:926",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277682720,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587368192,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:926",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587368192,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587136416,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:926",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587136416,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587683392,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:926",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587683392,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
```

```json
{
  "name": "cec_transmit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587789760,
      "name": "cec_transmit_msg",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:926",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_receive_notify",
        "drivers/media/cec/cec-adap.c:cec_feature_abort_reason"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587789760,
      "name": "cec_transmit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
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
int cec_transmit_msg(struct cec_adapter * adap, struct cec_msg * msg, bool block)
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
