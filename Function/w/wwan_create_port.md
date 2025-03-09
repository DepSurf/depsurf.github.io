# Function: <code>wwan_create_port</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct wwan_port * wwan_create_port(struct device * parent, enum wwan_port_type type, const struct wwan_port_ops * ops, void * drvdata)
```

```json
{
  "name": "wwan_create_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587791024,
      "name": "wwan_create_port",
      "external": true,
      "loc": "drivers/net/wwan/wwan_core.c:213",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587791024,
      "name": "wwan_create_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
    },
    {
      "addr": 18446744071587791776,
      "name": "wwan_create_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
struct wwan_port * wwan_create_port(struct device * parent, enum wwan_port_type type, const struct wwan_port_ops * ops, void * drvdata)
```

```json
{
  "name": "wwan_create_port",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588390112,
      "name": "wwan_create_port",
      "external": true,
      "loc": "drivers/net/wwan/wwan_core.c:355",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588390112,
      "name": "wwan_create_port.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    },
    {
      "addr": 18446744071588390656,
      "name": "wwan_create_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
struct wwan_port * wwan_create_port(struct device * parent, enum wwan_port_type type, const struct wwan_port_ops * ops, void * drvdata)
```

```json
{
  "name": "wwan_create_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589787696,
      "name": "wwan_create_port",
      "external": true,
      "loc": "drivers/net/wwan/wwan_core.c:421",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589787696,
      "name": "wwan_create_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
struct wwan_port * wwan_create_port(struct device * parent, enum wwan_port_type type, const struct wwan_port_ops * ops, void * drvdata)
```

```json
{
  "name": "wwan_create_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591437936,
      "name": "wwan_create_port",
      "external": true,
      "loc": "drivers/net/wwan/wwan_core.c:426",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591437936,
      "name": "wwan_create_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 594
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
struct wwan_port * wwan_create_port(struct device * parent, enum wwan_port_type type, const struct wwan_port_ops * ops, struct wwan_port_caps * caps, void * drvdata)
```

```json
{
  "name": "wwan_create_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591853008,
      "name": "wwan_create_port",
      "external": true,
      "loc": "drivers/net/wwan/wwan_core.c:430",
      "file": "drivers/net/wwan/wwan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591853008,
      "name": "wwan_create_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 679
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct wwan_port * wwan_create_port(struct device * parent, enum wwan_port_type type, const struct wwan_port_ops * ops, void * drvdata)
```
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wwan_port_caps * caps</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, type, ops, drvdata</code> ➡️ <code>parent, type, ops, caps, drvdata</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
struct wwan_port * wwan_create_port(struct device * parent, enum wwan_port_type type, const struct wwan_port_ops * ops, struct wwan_port_caps * caps, void * drvdata)
```
</details>
</li>
</ul>
