# Function: <code>sdc_init_panel</code>

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
int sdc_init_panel(struct mx3fb_data * mx3fb, enum ipu_panel panel, uint32_t pixel_clk, uint16_t width, uint16_t height, uint16_t h_start_width, uint16_t h_sync_width, uint16_t h_end_width, uint16_t v_start_width, uint16_t v_sync_width, uint16_t v_end_width, struct ipu_di_signal_cfg sig)
```

```json
{
  "name": "sdc_init_panel",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497364320,
      "name": "sdc_init_panel",
      "external": false,
      "loc": "drivers/video/fbdev/mx3fb.c:506",
      "file": "drivers/video/fbdev/mx3fb.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/mx3fb.c:__set_par"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497364320,
      "name": "sdc_init_panel",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 984
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
  "name": "sdc_init_panel",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3230542840,
      "name": "sdc_init_panel",
      "external": false,
      "loc": "drivers/video/fbdev/mx3fb.c:506",
      "file": "drivers/video/fbdev/mx3fb.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/mx3fb.c:__set_par"
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
int sdc_init_panel(struct mx3fb_data * mx3fb, enum ipu_panel panel, uint32_t pixel_clk, uint16_t width, uint16_t height, uint16_t h_start_width, uint16_t h_sync_width, uint16_t h_end_width, uint16_t v_start_width, uint16_t v_sync_width, uint16_t v_end_width, struct ipu_di_signal_cfg sig)
```
</details>
</li>
</ul>
