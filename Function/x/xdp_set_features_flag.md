# Function: <code>xdp_set_features_flag</code>

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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xdp_set_features_flag(struct net_device * dev, xdp_features_t val)
```

```json
{
  "name": "xdp_set_features_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594020971,
      "name": "xdp_set_features_flag",
      "external": true,
      "loc": "net/core/xdp.c:776",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_features_clear_redirect_target",
        "net/core/xdp.c:xdp_features_clear_redirect_target",
        "net/core/xdp.c:xdp_features_set_redirect_target",
        "net/core/xdp.c:xdp_features_set_redirect_target"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594018032,
      "name": "xdp_set_features_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void xdp_set_features_flag(struct net_device * dev, xdp_features_t val)
```

```json
{
  "name": "xdp_set_features_flag",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594807099,
      "name": "xdp_set_features_flag",
      "external": true,
      "loc": "net/core/xdp.c:807",
      "file": "net/core/xdp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/xdp.c:xdp_features_clear_redirect_target",
        "net/core/xdp.c:xdp_features_clear_redirect_target",
        "net/core/xdp.c:xdp_features_set_redirect_target",
        "net/core/xdp.c:xdp_features_set_redirect_target"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594804400,
      "name": "xdp_set_features_flag",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
void xdp_set_features_flag(struct net_device * dev, xdp_features_t val)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
