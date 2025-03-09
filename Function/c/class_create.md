# Function: <code>class_create</code>

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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct class * class_create(const char * name)
```

```json
{
  "name": "class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590621456,
      "name": "class_create",
      "external": true,
      "loc": "drivers/base/class.c:256",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdt_pseudo_lock_init",
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/tty/vt/vc_screen.c:vcs_init",
        "drivers/tty/vt/vt.c:vtconsole_class_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/char/tpm/tpm-interface.c:tpm_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/net/wwan/wwan_core.c:wwan_init",
        "drivers/usb/core/file.c:usb_register_dev",
        "drivers/rtc/class.c:rtc_init",
        "drivers/i2c/i2c-dev.c:i2c_dev_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/leds/led-class.c:leds_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init",
        "drivers/extcon/extcon.c:extcon_class_init",
        "drivers/extcon/extcon.c:extcon_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590621456,
      "name": "class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
struct class * class_create(const char * name)
```

```json
{
  "name": "class_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590980656,
      "name": "class_create",
      "external": true,
      "loc": "drivers/base/class.c:255",
      "file": "drivers/base/class.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/phy/phy-core.c:phy_core_init",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_init",
        "drivers/video/backlight/backlight.c:backlight_class_init",
        "drivers/video/fbdev/core/fbmem.c:fbmem_init",
        "drivers/base/power/wakeup_stats.c:wakeup_sources_sysfs_init",
        "drivers/nvdimm/bus.c:nvdimm_bus_init",
        "drivers/scsi/sg.c:init_sg",
        "drivers/gpu/drm/drm_sysfs.c:drm_sysfs_init",
        "drivers/net/ppp/ppp_generic.c:ppp_init",
        "drivers/rtc/class.c:rtc_init",
        "drivers/pps/pps.c:pps_init",
        "drivers/ptp/ptp_clock.c:ptp_init",
        "drivers/power/supply/power_supply_core.c:power_supply_class_init",
        "drivers/devfreq/devfreq.c:devfreq_init",
        "drivers/devfreq/devfreq-event.c:devfreq_event_init",
        "drivers/extcon/extcon.c:extcon_class_init",
        "drivers/extcon/extcon.c:extcon_dev_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590980656,
      "name": "class_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
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
struct class * class_create(const char * name)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
