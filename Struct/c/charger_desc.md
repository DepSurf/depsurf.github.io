# Struct: <code>charger_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
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
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
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
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
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
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>const struct attribute_group * * sysfs_groups</code>
</li>
</ul>
</details>
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
<b>Field removed. </b>
<code>unsigned int fullbatt_vchkdrop_ms</code>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct charger_desc {
    const char * psy_name;
    enum polling_modes polling_mode;
    unsigned int polling_interval_ms;
    unsigned int fullbatt_vchkdrop_ms;
    unsigned int fullbatt_vchkdrop_uV;
    unsigned int fullbatt_uV;
    unsigned int fullbatt_soc;
    unsigned int fullbatt_full_capacity;
    enum data_source battery_present;
    const char * * psy_charger_stat;
    int num_charger_regulators;
    struct charger_regulator * charger_regulators;
    const struct attribute_group * * sysfs_groups;
    const char * psy_fuel_gauge;
    const char * thermal_zone;
    int temp_min;
    int temp_max;
    int temp_diff;
    bool measure_battery_temp;
    u32 charging_max_duration_ms;
    u32 discharging_max_duration_ms;
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
