# Struct: <code>acpi_thermal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int kelvin_offset;
    struct work_struct thermal_check_work;
    struct mutex thermal_check_lock;
    refcount_t thermal_check_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int kelvin_offset;
    struct work_struct thermal_check_work;
    struct mutex thermal_check_lock;
    refcount_t thermal_check_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int kelvin_offset;
    struct work_struct thermal_check_work;
    struct mutex thermal_check_lock;
    refcount_t thermal_check_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int kelvin_offset;
    struct work_struct thermal_check_work;
    struct mutex thermal_check_lock;
    refcount_t thermal_check_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int kelvin_offset;
    struct work_struct thermal_check_work;
    struct mutex thermal_check_lock;
    refcount_t thermal_check_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int kelvin_offset;
    struct work_struct thermal_check_work;
    struct mutex thermal_check_lock;
    refcount_t thermal_check_count;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temp_dk;
    long unsigned int last_temp_dk;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_trips trips;
    struct thermal_trip * trip_table;
    struct thermal_zone_device * thermal_zone;
    int kelvin_offset;
    struct work_struct thermal_check_work;
    struct mutex thermal_check_lock;
    refcount_t thermal_check_count;
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct mutex thermal_check_lock</code>
</li>
<li>
<b>Field added. </b>
<code>refcount_t thermal_check_count</code>
</li>
<li>
<b>Field removed. </b>
<code>int tz_enabled</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct acpi_thermal_flags flags</code>
</li>
<li>
<b>Field removed. </b>
<code>struct acpi_thermal_state state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int temp_dk</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int last_temp_dk</code>
</li>
<li>
<b>Field added. </b>
<code>struct thermal_trip * trip_table</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int temperature</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int last_temperature</code>
</li>
<li>
<b>Field removed. </b>
<code>struct acpi_handle_list devices</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct acpi_thermal {
    struct acpi_device * device;
    acpi_bus_id name;
    long unsigned int temperature;
    long unsigned int last_temperature;
    long unsigned int polling_frequency;
    volatile u8 zombie;
    struct acpi_thermal_flags flags;
    struct acpi_thermal_state state;
    struct acpi_thermal_trips trips;
    struct acpi_handle_list devices;
    struct thermal_zone_device * thermal_zone;
    int tz_enabled;
    int kelvin_offset;
    struct work_struct thermal_check_work;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
