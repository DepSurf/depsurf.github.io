# Function: <code>__netdev_adjacent_dev_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __netdev_adjacent_dev_unlink(struct net_device * dev, struct net_device * upper_dev)
```

```json
{
  "name": "__netdev_adjacent_dev_unlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586275664,
      "name": "__netdev_adjacent_dev_unlink",
      "external": false,
      "loc": "net/core/dev.c:5323",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586275664,
      "name": "__netdev_adjacent_dev_unlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __netdev_adjacent_dev_unlink(struct net_device * dev, struct net_device * upper_dev)
```

```json
{
  "name": "__netdev_adjacent_dev_unlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586701408,
      "name": "__netdev_adjacent_dev_unlink",
      "external": false,
      "loc": "net/core/dev.c:5713",
      "file": "net/core/dev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:netdev_upper_dev_unlink",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_upper_dev_link",
        "net/core/dev.c:__netdev_adjacent_dev_unlink_neighbour"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701408,
      "name": "__netdev_adjacent_dev_unlink",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
void __netdev_adjacent_dev_unlink(struct net_device * dev, struct net_device * upper_dev)
```
</details>
</li>
</ul>
