# Function: <code>ulpi_viewport_wait</code>

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
int ulpi_viewport_wait(void * view, u32 mask)
```

```json
{
  "name": "ulpi_viewport_wait",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500355016,
      "name": "ulpi_viewport_wait",
      "external": false,
      "loc": "drivers/usb/phy/phy-ulpi-viewport.c:21",
      "file": "drivers/usb/phy/phy-ulpi-viewport.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500355016,
      "name": "ulpi_viewport_wait",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "ulpi_viewport_wait",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "ulpi_viewport_wait",
      "external": false,
      "loc": "drivers/usb/phy/phy-ulpi-viewport.c:21",
      "file": "drivers/usb/phy/phy-ulpi-viewport.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read",
        "drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read"
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
int ulpi_viewport_wait(void * view, u32 mask)
```
</details>
</li>
</ul>
