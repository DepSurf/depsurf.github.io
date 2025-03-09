# Function: <code>__mddev_resume</code>

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
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void __mddev_resume(struct mddev * mddev, bool recovery_needed)
```

```json
{
  "name": "__mddev_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593592048,
      "name": "__mddev_resume",
      "external": false,
      "loc": "drivers/md/md.c:501",
      "file": "drivers/md/md.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_start_sync",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:md_ioctl",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:autorun_devices",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:serialize_policy_store",
        "drivers/md/md.c:suspend_hi_store",
        "drivers/md/md.c:suspend_lo_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:new_dev_store",
        "drivers/md/md.c:level_store",
        "drivers/md/md.c:rdev_attr_store",
        "drivers/md/md.c:rdev_attr_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593592048,
      "name": "__mddev_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void __mddev_resume(struct mddev * mddev, bool recovery_needed)
```
</details>
</li>
</ul>
