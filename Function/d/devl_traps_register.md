# Function: <code>devl_traps_register</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devl_traps_register(struct devlink * devlink, const struct devlink_trap * traps, size_t traps_count, void * priv)
```

```json
{
  "name": "devl_traps_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593785389,
      "name": "devl_traps_register",
      "external": true,
      "loc": "net/core/devlink.c:12393",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_traps_register"
      ],
      "caller_func": [
        "net/core/devlink.c:devlink_traps_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593784256,
      "name": "devl_traps_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
    },
    {
      "addr": 18446744071596331779,
      "name": "devl_traps_register.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071593785248,
      "name": "devl_traps_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devl_traps_register(struct devlink * devlink, const struct devlink_trap * traps, size_t traps_count, void * priv)
```

```json
{
  "name": "devl_traps_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595884561,
      "name": "devl_traps_register",
      "external": true,
      "loc": "net/devlink/leftover.c:8988",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devlink_traps_register"
      ],
      "caller_func": [
        "net/devlink/leftover.c:devlink_traps_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595883392,
      "name": "devl_traps_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
    },
    {
      "addr": 18446744071596893701,
      "name": "devl_traps_register.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071595884384,
      "name": "devl_traps_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int devl_traps_register(struct devlink * devlink, const struct devlink_trap * traps, size_t traps_count, void * priv)
```

```json
{
  "name": "devl_traps_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596763857,
      "name": "devl_traps_register",
      "external": true,
      "loc": "net/devlink/trap.c:1355",
      "file": "net/devlink/trap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/trap.c:devlink_traps_register"
      ],
      "caller_func": [
        "net/devlink/trap.c:devlink_traps_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596762656,
      "name": "devl_traps_register.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 996
    },
    {
      "addr": 18446744071597819765,
      "name": "devl_traps_register.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071596763680,
      "name": "devl_traps_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int devl_traps_register(struct devlink * devlink, const struct devlink_trap * traps, size_t traps_count, void * priv)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
