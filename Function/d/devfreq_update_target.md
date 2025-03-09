# Function: <code>devfreq_update_target</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq * devfreq, long unsigned int freq)
```

```json
{
  "name": "devfreq_update_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589131696,
      "name": "devfreq_update_target",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:405",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:qos_max_notifier_call",
        "drivers/devfreq/devfreq.c:qos_min_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589131696,
      "name": "devfreq_update_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
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
int devfreq_update_target(struct devfreq * devfreq, long unsigned int freq)
```

```json
{
  "name": "devfreq_update_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589021408,
      "name": "devfreq_update_target",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:406",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:qos_max_notifier_call",
        "drivers/devfreq/devfreq.c:qos_min_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589021408,
      "name": "devfreq_update_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq * devfreq, long unsigned int freq)
```

```json
{
  "name": "devfreq_update_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589736992,
      "name": "devfreq_update_target",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:406",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:qos_max_notifier_call",
        "drivers/devfreq/devfreq.c:qos_min_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589736992,
      "name": "devfreq_update_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int devfreq_update_target(struct devfreq * devfreq, long unsigned int freq)
```

```json
{
  "name": "devfreq_update_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591239952,
      "name": "devfreq_update_target",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:403",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:qos_max_notifier_call",
        "drivers/devfreq/devfreq.c:qos_min_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591239952,
      "name": "devfreq_update_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int devfreq_update_target(struct devfreq * devfreq, long unsigned int freq)
```

```json
{
  "name": "devfreq_update_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592992080,
      "name": "devfreq_update_target",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:403",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:qos_max_notifier_call",
        "drivers/devfreq/devfreq.c:qos_min_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592992080,
      "name": "devfreq_update_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int devfreq_update_target(struct devfreq * devfreq, long unsigned int freq)
```

```json
{
  "name": "devfreq_update_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593443536,
      "name": "devfreq_update_target",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:403",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:qos_max_notifier_call",
        "drivers/devfreq/devfreq.c:qos_min_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593443536,
      "name": "devfreq_update_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
int devfreq_update_target(struct devfreq * devfreq, long unsigned int freq)
```

```json
{
  "name": "devfreq_update_target",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594190016,
      "name": "devfreq_update_target",
      "external": true,
      "loc": "drivers/devfreq/devfreq.c:403",
      "file": "drivers/devfreq/devfreq.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/devfreq/devfreq.c:qos_max_notifier_call",
        "drivers/devfreq/devfreq.c:qos_min_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_notifier_call",
        "drivers/devfreq/devfreq.c:devfreq_monitor",
        "drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier",
        "drivers/devfreq/governor_passive.c:cpufreq_passive_notifier_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594190016,
      "name": "devfreq_update_target",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int devfreq_update_target(struct devfreq * devfreq, long unsigned int freq)
```
</details>
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
