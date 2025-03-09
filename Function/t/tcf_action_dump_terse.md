# Function: <code>tcf_action_dump_terse</code>

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
int tcf_action_dump_terse(struct sk_buff * skb, struct tc_action * a)
```

```json
{
  "name": "tcf_action_dump_terse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589806656,
      "name": "tcf_action_dump_terse",
      "external": false,
      "loc": "net/sched/act_api.c:770",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589806656,
      "name": "tcf_action_dump_terse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int tcf_action_dump_terse(struct sk_buff * skb, struct tc_action * a, bool from_act)
```

```json
{
  "name": "tcf_action_dump_terse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_action_dump_terse",
      "external": false,
      "loc": "net/sched/act_api.c:235",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589842816,
      "name": "tcf_action_dump_terse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
    },
    {
      "addr": 18446744071591633544,
      "name": "tcf_action_dump_terse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int tcf_action_dump_terse(struct sk_buff * skb, struct tc_action * a, bool from_act)
```

```json
{
  "name": "tcf_action_dump_terse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_action_dump_terse",
      "external": false,
      "loc": "net/sched/act_api.c:246",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589747936,
      "name": "tcf_action_dump_terse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071591576945,
      "name": "tcf_action_dump_terse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tcf_action_dump_terse(struct sk_buff * skb, struct tc_action * a, bool from_act)
```

```json
{
  "name": "tcf_action_dump_terse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_action_dump_terse",
      "external": false,
      "loc": "net/sched/act_api.c:246",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590506384,
      "name": "tcf_action_dump_terse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
    },
    {
      "addr": 18446744071592710927,
      "name": "tcf_action_dump_terse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tcf_action_dump_terse(struct sk_buff * skb, struct tc_action * a, bool from_act)
```

```json
{
  "name": "tcf_action_dump_terse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "tcf_action_dump_terse",
      "external": false,
      "loc": "net/sched/act_api.c:484",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592110928,
      "name": "tcf_action_dump_terse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    },
    {
      "addr": 18446744071594597057,
      "name": "tcf_action_dump_terse.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
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
int tcf_action_dump_terse(struct sk_buff * skb, struct tc_action * a, bool from_act)
```

```json
{
  "name": "tcf_action_dump_terse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593930848,
      "name": "tcf_action_dump_terse",
      "external": false,
      "loc": "net/sched/act_api.c:485",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593930848,
      "name": "tcf_action_dump_terse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
int tcf_action_dump_terse(struct sk_buff * skb, struct tc_action * a, bool from_act)
```

```json
{
  "name": "tcf_action_dump_terse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594307824,
      "name": "tcf_action_dump_terse",
      "external": false,
      "loc": "net/sched/act_api.c:478",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594307824,
      "name": "tcf_action_dump_terse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
int tcf_action_dump_terse(struct sk_buff * skb, struct tc_action * a, bool from_act)
```

```json
{
  "name": "tcf_action_dump_terse",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595106928,
      "name": "tcf_action_dump_terse",
      "external": false,
      "loc": "net/sched/act_api.c:478",
      "file": "net/sched/act_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/sched/act_api.c:tcf_action_dump",
        "net/sched/act_api.c:tcf_action_dump_1",
        "net/sched/act_api.c:tcf_dump_walker"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595106928,
      "name": "tcf_action_dump_terse",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
int tcf_action_dump_terse(struct sk_buff * skb, struct tc_action * a)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool from_act</code>
</li>
</ul>
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
