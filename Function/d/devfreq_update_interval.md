# Function: <code>devfreq_update_interval</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void devfreq_update_interval(struct devfreq * devfreq, unsigned int * delay)
```

```json
{
  "name": "devfreq_update_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589126336,
      "name": "devfreq_update_interval",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:557",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589126336,
      "name": "devfreq_update_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void devfreq_update_interval(struct devfreq * devfreq, unsigned int * delay)
```

```json
{
  "name": "devfreq_update_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589124752,
      "name": "devfreq_update_interval",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:598",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589124752,
      "name": "devfreq_update_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void devfreq_update_interval(struct devfreq * devfreq, unsigned int * delay)
```

```json
{
  "name": "devfreq_update_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589014784,
      "name": "devfreq_update_interval",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:599",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589014784,
      "name": "devfreq_update_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
void devfreq_update_interval(struct devfreq * devfreq, unsigned int * delay)
```

```json
{
  "name": "devfreq_update_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_update_interval",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:599",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592685545,
      "name": "devfreq_update_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071589734016,
      "name": "devfreq_update_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void devfreq_update_interval(struct devfreq * devfreq, unsigned int * delay)
```

```json
{
  "name": "devfreq_update_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_update_interval",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:596",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594570869,
      "name": "devfreq_update_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071591245760,
      "name": "devfreq_update_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void devfreq_update_interval(struct devfreq * devfreq, unsigned int * delay)
```

```json
{
  "name": "devfreq_update_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_update_interval",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:596",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596319842,
      "name": "devfreq_update_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071592998672,
      "name": "devfreq_update_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void devfreq_update_interval(struct devfreq * devfreq, unsigned int * delay)
```

```json
{
  "name": "devfreq_update_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_update_interval",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:596",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596849485,
      "name": "devfreq_update_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071593450144,
      "name": "devfreq_update_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void devfreq_update_interval(struct devfreq * devfreq, unsigned int * delay)
```

```json
{
  "name": "devfreq_update_interval",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devfreq_update_interval",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:617",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/governor_simpleondemand.c:devfreq_simple_ondemand_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597774244,
      "name": "devfreq_update_interval.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071594196544,
      "name": "devfreq_update_interval",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void devfreq_update_interval(struct devfreq * devfreq, unsigned int * delay)
```
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
