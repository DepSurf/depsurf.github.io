# Function: <code>cec_notifier_get_conn</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * dev, const char * conn)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587269744,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:34",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587269744,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587538144,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587538144,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587740880,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587740880,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500917920,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500917920,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233436080,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233436080,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294378928,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294378928,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 948
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277693240,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277693240,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 302
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587381824,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587381824,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587150048,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150048,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587697024,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697024,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
```

```json
{
  "name": "cec_notifier_get_conn",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587803456,
      "name": "cec_notifier_get_conn",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:37",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/media/cec/cec-notifier.c:cec_notifier_cec_adap_register",
        "drivers/media/cec/cec-notifier.c:cec_notifier_conn_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587803456,
      "name": "cec_notifier_get_conn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 322
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
struct cec_notifier * cec_notifier_get_conn(struct device * dev, const char * conn)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * hdmi_dev</code>
</li>
<li>
<b>Param added. </b>
<code>const char * conn_name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * conn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct cec_notifier * cec_notifier_get_conn(struct device * hdmi_dev, const char * conn_name)
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
