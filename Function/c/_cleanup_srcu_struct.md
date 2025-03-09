# Function: <code>_cleanup_srcu_struct</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void _cleanup_srcu_struct(struct srcu_struct * sp, bool quiesced)
```

```json
{
  "name": "_cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:370",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-mq.c:blk_mq_exit_hctx",
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911748,
      "name": "_cleanup_srcu_struct.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579906176,
      "name": "_cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void _cleanup_srcu_struct(struct srcu_struct * ssp, bool quiesced)
```

```json
{
  "name": "_cleanup_srcu_struct",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "_cleanup_srcu_struct",
      "external": true,
      "loc": "kernel/rcu/srcutree.c:375",
      "file": "kernel/rcu/srcutree.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_notifier_unregister",
        "drivers/md/dm.c:cleanup_mapped_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579959459,
      "name": "_cleanup_srcu_struct.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
    },
    {
      "addr": 18446744071579953712,
      "name": "_cleanup_srcu_struct",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void _cleanup_srcu_struct(struct srcu_struct * sp, bool quiesced)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct * ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct * sp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void _cleanup_srcu_struct(struct srcu_struct * ssp, bool quiesced)
```
</details>
</li>
</ul>
