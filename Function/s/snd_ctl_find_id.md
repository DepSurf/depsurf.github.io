# Function: <code>snd_ctl_find_id</code>

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
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
struct snd_kcontrol * snd_ctl_find_id(struct snd_card * card, struct snd_ctl_elem_id * id)
```

```json
{
  "name": "snd_ctl_find_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234354120,
      "name": "snd_ctl_find_id",
      "external": true,
      "loc": "sound/core/control.c:664",
      "file": "sound/core/control.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "sound/core/control.c:snd_ctl_ioctl",
        "sound/core/control.c:snd_ctl_ioctl",
        "sound/core/control.c:snd_ctl_ioctl",
        "sound/core/control.c:snd_ctl_ioctl",
        "sound/core/control.c:snd_ctl_elem_info_user",
        "sound/core/control.c:snd_ctl_rename_id",
        "sound/core/control.c:snd_ctl_activate_id",
        "sound/core/control.c:snd_ctl_remove_user_ctl",
        "sound/core/control.c:snd_ctl_remove_id",
        "sound/core/control.c:__snd_ctl_add_replace",
        "sound/core/ctljack.c:snd_kctl_jack_new"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234354120,
      "name": "snd_ctl_find_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct snd_kcontrol * snd_ctl_find_id(struct snd_card * card, struct snd_ctl_elem_id * id)
```
</details>
</li>
</ul>
