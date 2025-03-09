# Struct: <code>power_supply</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct power_supply_battery_info * battery_info;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct power_supply_battery_info * battery_info;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
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
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct power_supply {
    const struct power_supply_desc * desc;
    char * * supplied_to;
    size_t num_supplicants;
    char * * supplied_from;
    size_t num_supplies;
    struct device_node * of_node;
    void * drv_data;
    struct device dev;
    struct work_struct changed_work;
    struct delayed_work deferred_register_work;
    spinlock_t changed_lock;
    bool changed;
    bool initialized;
    bool removing;
    atomic_t use_cnt;
    struct thermal_zone_device * tzd;
    struct thermal_cooling_device * tcd;
    struct led_trigger * charging_full_trig;
    char * charging_full_trig_name;
    struct led_trigger * charging_trig;
    char * charging_trig_name;
    struct led_trigger * full_trig;
    char * full_trig_name;
    struct led_trigger * online_trig;
    char * online_trig_name;
    struct led_trigger * charging_blink_full_solid_trig;
    char * charging_blink_full_solid_trig_name;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool initialized</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool removing</code>
</li>
</ul>
</details>
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
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<b>Field added. </b>
<code>struct power_supply_battery_info * battery_info</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
