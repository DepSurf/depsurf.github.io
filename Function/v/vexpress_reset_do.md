# Function: <code>vexpress_reset_do</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void vexpress_reset_do(struct device * dev, const char * what)
```

```json
{
  "name": "vexpress_reset_do",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500945360,
      "name": "vexpress_reset_do",
      "external": false,
      "loc": "drivers/power/reset/vexpress-poweroff.c:16",
      "file": "drivers/power/reset/vexpress-poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/reset/vexpress-poweroff.c:vexpress_restart",
        "drivers/power/reset/vexpress-poweroff.c:vexpress_power_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500945360,
      "name": "vexpress_reset_do",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
void vexpress_reset_do(struct device * dev, const char * what)
```

```json
{
  "name": "vexpress_reset_do",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233460388,
      "name": "vexpress_reset_do",
      "external": false,
      "loc": "drivers/power/reset/vexpress-poweroff.c:16",
      "file": "drivers/power/reset/vexpress-poweroff.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/power/reset/vexpress-poweroff.c:vexpress_restart",
        "drivers/power/reset/vexpress-poweroff.c:vexpress_power_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233460388,
      "name": "vexpress_reset_do",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void vexpress_reset_do(struct device * dev, const char * what)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void vexpress_reset_do(struct device * dev, const char * what)
```
</details>
</li>
</ul>
