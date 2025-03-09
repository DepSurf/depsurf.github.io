# Function: <code>cec_queue_event_fh</code>

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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587249392,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:86",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587249392,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 505
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530738,
      "name": "cec_queue_event_fh.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071587517248,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587720224,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587720224,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500897176,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500897176,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 496
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233415860,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233415860,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294352288,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294352288,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 648
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277676380,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277676380,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 462
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587361168,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587361168,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587129392,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587129392,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587676368,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587676368,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
```

```json
{
  "name": "cec_queue_event_fh",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587782752,
      "name": "cec_queue_event_fh",
      "external": true,
      "loc": "drivers/media/cec/cec-adap.c:99",
      "file": "drivers/media/cec/cec-adap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-adap.c:cec_post_state_event",
        "drivers/media/cec/cec-adap.c:cec_queue_msg_fh",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_5v_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_hpd_event",
        "drivers/media/cec/cec-adap.c:cec_queue_pin_cec_event",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_open",
        "drivers/media/cec/cec-api.c:cec_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587782752,
      "name": "cec_queue_event_fh",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 509
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
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
void cec_queue_event_fh(struct cec_fh * fh, const struct cec_event * new_ev, u64 ts)
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
