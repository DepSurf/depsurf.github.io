# Function: <code>tpm_getcap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
ssize_t tpm_getcap(struct device * dev, __be32 subcap_id, cap_t * cap, const char * desc)
```

```json
{
  "name": "tpm_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584237584,
      "name": "tpm_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237584,
      "name": "tpm_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 254
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
ssize_t tpm_getcap(struct tpm_chip * chip, __be32 subcap_id, cap_t * cap, const char * desc)
```

```json
{
  "name": "tpm_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584577424,
      "name": "tpm_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:435",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584577424,
      "name": "tpm_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 247
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
ssize_t tpm_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc)
```

```json
{
  "name": "tpm_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584756224,
      "name": "tpm_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:447",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584756224,
      "name": "tpm_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
ssize_t tpm_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584837472,
      "name": "tpm_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:596",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837472,
      "name": "tpm_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
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
ssize_t tpm_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258752,
      "name": "tpm_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:614",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258752,
      "name": "tpm_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
ssize_t tpm_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```

```json
{
  "name": "tpm_getcap",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585495568,
      "name": "tpm_getcap",
      "external": true,
      "loc": "drivers/char/tpm/tpm-interface.c:733",
      "file": "drivers/char/tpm/tpm-interface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:caps_show",
        "drivers/char/tpm/tpm-sysfs.c:temp_deactivated_show",
        "drivers/char/tpm/tpm-sysfs.c:owned_show",
        "drivers/char/tpm/tpm-sysfs.c:active_show",
        "drivers/char/tpm/tpm-sysfs.c:enabled_show",
        "drivers/char/tpm/tpm-sysfs.c:pcrs_show",
        "drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585495568,
      "name": "tpm_getcap",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_chip * chip</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dev</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__be32 subcap_id</code> ➡️ <code>u32 subcap_id</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t min_cap_length</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
ssize_t tpm_getcap(struct tpm_chip * chip, u32 subcap_id, cap_t * cap, const char * desc, size_t min_cap_length)
```
</details>
</li>
</ul>
