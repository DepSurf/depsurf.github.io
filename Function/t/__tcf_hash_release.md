# Function: <code>__tcf_hash_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tcf_hash_release(struct tc_action * a, bool bind, bool strict)
```

```json
{
  "name": "__tcf_hash_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586477184,
      "name": "__tcf_hash_release",
      "external": true,
      "loc": "net/sched/act_api.c:56",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586477184,
      "name": "__tcf_hash_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tcf_hash_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_hash_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586924112,
      "name": "__tcf_hash_release",
      "external": true,
      "loc": "net/sched/act_api.c:53",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_hashinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586924112,
      "name": "__tcf_hash_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tcf_hash_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_hash_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587118848,
      "name": "__tcf_hash_release",
      "external": true,
      "loc": "net/sched/act_api.c:59",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_init_1",
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_hashinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587118848,
      "name": "__tcf_hash_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 227
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __tcf_hash_release(struct tc_action * p, bool bind, bool strict)
```

```json
{
  "name": "__tcf_hash_release",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587248336,
      "name": "__tcf_hash_release",
      "external": true,
      "loc": "net/sched/act_api.c:86",
      "file": "net/sched/act_api.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_destroy",
        "net/sched/act_api.c:tcf_hashinfo_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587248336,
      "name": "__tcf_hash_release",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 195
    }
  ]
}
```
</details>
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
<code>struct tc_action * p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct tc_action * a</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
int __tcf_hash_release(struct tc_action * p, bool bind, bool strict)
```
</details>
</li>
</ul>
