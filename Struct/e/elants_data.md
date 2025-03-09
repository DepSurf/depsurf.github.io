# Struct: <code>elants_data</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    u8[169] buf;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    u8[169] buf;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    u8[169] buf;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    u8[169] buf;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    struct touchscreen_properties prop;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    u8 major_res;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    struct touchscreen_properties prop;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    u8 major_res;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    unsigned int phy_x;
    unsigned int phy_y;
    struct touchscreen_properties prop;
    enum elants_state state;
    enum elants_chip_id chip_id;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    u8 major_res;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    unsigned int phy_x;
    unsigned int phy_y;
    struct touchscreen_properties prop;
    enum elants_state state;
    enum elants_chip_id chip_id;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    u8 major_res;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    unsigned int phy_x;
    unsigned int phy_y;
    struct touchscreen_properties prop;
    enum elants_state state;
    enum elants_chip_id chip_id;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    u8 major_res;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    unsigned int phy_x;
    unsigned int phy_y;
    struct touchscreen_properties prop;
    enum elants_state state;
    enum elants_chip_id chip_id;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    u8 major_res;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    unsigned int phy_x;
    unsigned int phy_y;
    struct touchscreen_properties prop;
    enum elants_state state;
    enum elants_chip_id chip_id;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    u8 major_res;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    unsigned int phy_x;
    unsigned int phy_y;
    struct touchscreen_properties prop;
    enum elants_state state;
    enum elants_chip_id chip_id;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool keep_power_in_suspend;
    u8[169] buf;
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    u8[169] buf;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
}
```
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct touchscreen_properties prop</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>u8 major_res</code>
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
<code>unsigned int phy_x</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int phy_y</code>
</li>
<li>
<b>Field added. </b>
<code>enum elants_chip_id chip_id</code>
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
<b>Field removed. </b>
<code>bool wake_irq_enabled</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
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
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
}
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct elants_data {
    struct i2c_client * client;
    struct input_dev * input;
    struct regulator * vcc33;
    struct regulator * vccio;
    struct gpio_desc * reset_gpio;
    u16 fw_version;
    u8 test_version;
    u8 solution_version;
    u8 bc_version;
    u8 iap_version;
    u16 hw_version;
    unsigned int x_res;
    unsigned int y_res;
    unsigned int x_max;
    unsigned int y_max;
    enum elants_state state;
    enum elants_iap_mode iap_mode;
    struct mutex sysfs_mutex;
    u8[4] cmd_resp;
    struct completion cmd_done;
    bool wake_irq_enabled;
    bool keep_power_in_suspend;
    u8[169] buf;
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
