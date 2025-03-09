# Function: <code>cec_notifier_cec_adap_register</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587539684,
      "name": "cec_notifier_cec_adap_register.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587538736,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587741472,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587741472,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500918456,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500918456,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233436540,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233436540,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294380112,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294380112,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277693696,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277693696,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587382416,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382416,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587150640,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587150640,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587697616,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587697616,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
```

```json
{
  "name": "cec_notifier_cec_adap_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587804048,
      "name": "cec_notifier_cec_adap_register",
      "external": true,
      "loc": "drivers/media/cec/cec-notifier.c:134",
      "file": "drivers/media/cec/cec-notifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587804048,
      "name": "cec_notifier_cec_adap_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
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
struct cec_notifier * cec_notifier_cec_adap_register(struct device * hdmi_dev, const char * conn_name, struct cec_adapter * adap)
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
