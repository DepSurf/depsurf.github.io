# Function: <code>uevent_net_broadcast_untagged</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589142907,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:307",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589377315,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589834511,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590060655,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int uevent_net_broadcast_untagged(struct kobj_uevent_env * env, const char * action_string, const char * devpath)
```

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585055344,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585055344,
      "name": "uevent_net_broadcast_untagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
int uevent_net_broadcast_untagged(struct kobj_uevent_env * env, const char * action_string, const char * devpath)
```

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204816,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204816,
      "name": "uevent_net_broadcast_untagged",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585087835,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:309",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585535179,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:309",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586689658,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:309",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595771018,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:309",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596295578,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:309",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597180522,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:309",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_net_broadcast"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336503837800,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3236456504,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055297688660,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936279729686,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589662911,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589388735,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590106287,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uevent_net_broadcast_untagged",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590156591,
      "name": "uevent_net_broadcast_untagged",
      "external": false,
      "loc": "lib/kobject_uevent.c:308",
      "file": "lib/kobject_uevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/kobject_uevent.c:kobject_uevent_env"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int uevent_net_broadcast_untagged(struct kobj_uevent_env * env, const char * action_string, const char * devpath)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int uevent_net_broadcast_untagged(struct kobj_uevent_env * env, const char * action_string, const char * devpath)
```
</details>
</li>
</ul>
