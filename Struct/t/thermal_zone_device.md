# Struct: <code>thermal_zone_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct idr idr;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct idr idr;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct idr idr;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    enum thermal_device_mode mode;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    enum thermal_device_mode mode;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    long unsigned int passive_delay_jiffies;
    long unsigned int polling_delay_jiffies;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    enum thermal_device_mode mode;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    long unsigned int passive_delay_jiffies;
    long unsigned int polling_delay_jiffies;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    enum thermal_device_mode mode;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    long unsigned int passive_delay_jiffies;
    long unsigned int polling_delay_jiffies;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    enum thermal_device_mode mode;
    void * devdata;
    struct thermal_trip * trips;
    int num_trips;
    long unsigned int trips_disabled;
    long unsigned int passive_delay_jiffies;
    long unsigned int polling_delay_jiffies;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    enum thermal_device_mode mode;
    void * devdata;
    struct thermal_trip * trips;
    int num_trips;
    long unsigned int trips_disabled;
    long unsigned int passive_delay_jiffies;
    long unsigned int polling_delay_jiffies;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct completion removal;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    enum thermal_device_mode mode;
    void * devdata;
    struct thermal_trip * trips;
    int num_trips;
    long unsigned int passive_delay_jiffies;
    long unsigned int polling_delay_jiffies;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
    bool suspended;
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
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
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
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct thermal_zone_device {
    int id;
    char[20] type;
    struct device device;
    struct attribute_group trips_attribute_group;
    struct thermal_attr * trip_temp_attrs;
    struct thermal_attr * trip_type_attrs;
    struct thermal_attr * trip_hyst_attrs;
    void * devdata;
    int trips;
    long unsigned int trips_disabled;
    int passive_delay;
    int polling_delay;
    int temperature;
    int last_temperature;
    int emul_temperature;
    int passive;
    int prev_low_trip;
    int prev_high_trip;
    unsigned int forced_passive;
    atomic_t need_update;
    struct thermal_zone_device_ops * ops;
    struct thermal_zone_params * tzp;
    struct thermal_governor * governor;
    void * governor_data;
    struct list_head thermal_instances;
    struct ida ida;
    struct mutex lock;
    struct list_head node;
    struct delayed_work poll_queue;
    enum thermal_notify_event notify_event;
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
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct attribute_group trips_attribute_group</code>
</li>
<li>
<b>Field added. </b>
<code>int prev_low_trip</code>
</li>
<li>
<b>Field added. </b>
<code>int prev_high_trip</code>
</li>
<li>
<b>Field added. </b>
<code>enum thermal_notify_event notify_event</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct ida ida</code>
</li>
<li>
<b>Field removed. </b>
<code>struct idr idr</code>
</li>
</ul>
</details>
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
<code>enum thermal_device_mode mode</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>long unsigned int passive_delay_jiffies</code>
</li>
<li>
<b>Field added. </b>
<code>long unsigned int polling_delay_jiffies</code>
</li>
<li>
<b>Field removed. </b>
<code>int passive_delay</code>
</li>
<li>
<b>Field removed. </b>
<code>int polling_delay</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int forced_passive</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>int num_trips</code>
</li>
<li>
<b>Field type changed. </b>
<code>int trips</code> ➡️ <code>struct thermal_trip * trips</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct completion removal</code>
</li>
<li>
<b>Field added. </b>
<code>bool suspended</code>
</li>
<li>
<b>Field removed. </b>
<code>long unsigned int trips_disabled</code>
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
