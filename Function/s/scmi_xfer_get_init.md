# Function: <code>scmi_xfer_get_init</code>

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
int scmi_xfer_get_init(const struct scmi_handle * handle, u8 msg_id, u8 prot_id, size_t tx_size, size_t rx_size, struct scmi_xfer * * p)
```

```json
{
  "name": "scmi_xfer_get_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501521896,
      "name": "scmi_xfer_get_init",
      "external": true,
      "loc": "drivers/firmware/arm_scmi/driver.c:528",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/arm_scmi/driver.c:scmi_version_get",
        "drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init",
        "drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init",
        "drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init",
        "drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init",
        "drivers/firmware/arm_scmi/base.c:scmi_base_vendor_id_get",
        "drivers/firmware/arm_scmi/base.c:scmi_base_vendor_id_get",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_config_set",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set",
        "drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init",
        "drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init",
        "drivers/firmware/arm_scmi/power.c:scmi_power_state_get",
        "drivers/firmware/arm_scmi/power.c:scmi_power_state_set",
        "drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init",
        "drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensor_reading_get",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensor_trip_point_config",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensor_trip_point_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501521896,
      "name": "scmi_xfer_get_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int scmi_xfer_get_init(const struct scmi_handle * handle, u8 msg_id, u8 prot_id, size_t tx_size, size_t rx_size, struct scmi_xfer * * p)
```

```json
{
  "name": "scmi_xfer_get_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234038264,
      "name": "scmi_xfer_get_init",
      "external": true,
      "loc": "drivers/firmware/arm_scmi/driver.c:528",
      "file": "drivers/firmware/arm_scmi/driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/arm_scmi/driver.c:scmi_version_get",
        "drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init",
        "drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init",
        "drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init",
        "drivers/firmware/arm_scmi/base.c:scmi_base_protocol_init",
        "drivers/firmware/arm_scmi/base.c:scmi_base_vendor_id_get",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_protocol_init",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_config_set",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_set",
        "drivers/firmware/arm_scmi/clock.c:scmi_clock_rate_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_protocol_init",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_domain_desc_fc",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get",
        "drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set",
        "drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init",
        "drivers/firmware/arm_scmi/power.c:scmi_power_protocol_init",
        "drivers/firmware/arm_scmi/power.c:scmi_power_state_get",
        "drivers/firmware/arm_scmi/power.c:scmi_power_state_set",
        "drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init",
        "drivers/firmware/arm_scmi/reset.c:scmi_reset_protocol_init",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensors_protocol_init",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensor_reading_get",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensor_trip_point_config",
        "drivers/firmware/arm_scmi/sensors.c:scmi_sensor_trip_point_notify"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234038264,
      "name": "scmi_xfer_get_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int scmi_xfer_get_init(const struct scmi_handle * handle, u8 msg_id, u8 prot_id, size_t tx_size, size_t rx_size, struct scmi_xfer * * p)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int scmi_xfer_get_init(const struct scmi_handle * handle, u8 msg_id, u8 prot_id, size_t tx_size, size_t rx_size, struct scmi_xfer * * p)
```
</details>
</li>
</ul>
