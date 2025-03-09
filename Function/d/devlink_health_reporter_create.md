# Function: <code>devlink_health_reporter_create</code>

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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4616",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588618373,
      "name": "devlink_health_reporter_create.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071588575632,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588792960,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4671",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588792960,
      "name": "devlink_health_reporter_create",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589675696,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:5187",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589675696,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589701440,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:5957",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589701440,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589579360,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:6160",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589579360,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590327600,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:6773",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590327600,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591916432,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:7265",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591916432,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593721472,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:7820",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593721472,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 209
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595909616,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/devlink/health.c:212",
      "file": "net/devlink/health.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595909616,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596743744,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/devlink/health.c:211",
      "file": "net/devlink/health.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596743744,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502363824,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4671",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502363824,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235101748,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4671",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3235101748,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295898592,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4671",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295898592,
      "name": "devlink_health_reporter_create",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278580060,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4671",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278580060,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588399344,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4671",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588399344,
      "name": "devlink_health_reporter_create",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588112032,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4671",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588112032,
      "name": "devlink_health_reporter_create",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588731520,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4671",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588731520,
      "name": "devlink_health_reporter_create",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```

```json
{
  "name": "devlink_health_reporter_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588871888,
      "name": "devlink_health_reporter_create",
      "external": true,
      "loc": "net/core/devlink.c:4671",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588871888,
      "name": "devlink_health_reporter_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
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
struct devlink_health_reporter * devlink_health_reporter_create(struct devlink * devlink, const struct devlink_health_reporter_ops * ops, u64 graceful_period, bool auto_recover, void * priv)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool auto_recover</code>
</li>
<li>
<b>Param reordered. </b>
<code>devlink, ops, graceful_period, auto_recover, priv</code> ➡️ <code>devlink, ops, graceful_period, priv</code>
</li>
</ul>
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
