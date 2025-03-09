# Function: <code>devlink_trap_metadata_put</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588821661,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5306",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
int devlink_trap_metadata_put(struct sk_buff * msg, const struct devlink_trap * trap)
```

```json
{
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589717408,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5895",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589717408,
      "name": "devlink_trap_metadata_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int devlink_trap_metadata_put(struct sk_buff * msg, const struct devlink_trap * trap)
```

```json
{
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589745664,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:6746",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_trap_fill"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589745664,
      "name": "devlink_trap_metadata_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589637819,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:6949",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590393177,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:7575",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591971790,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:8068",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593782574,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:8603",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595881486,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/devlink/leftover.c:5459",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596761020,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/devlink/trap.c:131",
      "file": "net/devlink/trap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/trap.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502395132,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5306",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235130500,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5306",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295937556,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5306",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278607598,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5306",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588428045,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5306",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588140733,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5306",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588760221,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5306",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
  "name": "devlink_trap_metadata_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588900749,
      "name": "devlink_trap_metadata_put",
      "external": false,
      "loc": "net/core/devlink.c:5306",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_trap_fill"
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
int devlink_trap_metadata_put(struct sk_buff * msg, const struct devlink_trap * trap)
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
int devlink_trap_metadata_put(struct sk_buff * msg, const struct devlink_trap * trap)
```
</details>
</li>
</ul>
