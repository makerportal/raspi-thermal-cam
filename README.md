# Raspberry Pi Thermal Camera in Real Time with MLX90640 and Python

Full tutorial and demo at: https://makersportal.com/blog/2020/6/8/high-resolution-thermal-camera-with-raspberry-pi-and-mlx90640 <br><br>
Buy a thermal camera from our store: https://makersportal.com/shop/mlx90640-thermal-camera-for-raspberry-pi-32-x-24-pixels

The MLX90640 infrared thermal camera was introduced as a tool for visualizing the spatial distribution of temperatures across 768 (24x32) pixels. Using a Raspberry Pi, the MLX90640, and Python, a real-time temperature map was developed that operates at roughly 3-8 frames per second. The frame rate is limited by the CPU and GPU on the Raspberry Pi 4, where the upper limit of 8fps corresponds to a smaller figure display on the RPI. The thermal camera was further improved by interpolating pixels to 240x320, resulting in a smoother depiction of the temperature map. The thermal camera methods introduced in this tutorial have potential applications in non-destructive testing or experiments where distributed temperature maps are desired. Specific applications may be: electronics cooling, monitoring of moving parts with high frictions, and perhaps monitoring bodies for security or tracking. An infrared camera is particularly suitable for environments in low light because of the consistentcy of infrared radiation given off by bodies. Lastly, the MLX90640 IR sensor is a low-cost and efficient solution to monitoring spatial distributions of temperature, particularly for applications involving open-source tools that include Python, Arduino, and the Raspberry Pi platforms.

![RASPI THERM CAM](https://images.squarespace-cdn.com/content/v1/59b037304c0dbfb092fbe894/1591831961713-035L415YULEPNDV66BIH/ke17ZwdGBToddI8pDm48kNdzxjKe9o5FqqYmhbsB5QcUqsxRUqqbr1mOJYKfIPR7LoDQ9mXPOjoJoqy81S2I8N_N4V1vUb5AoIIIbLZhVYxCRW4BPu10St3TBAUQYVKcCQY6_siZwembdqfAnqJZYtDgoc9nAKV7D7OpcFu3CiVqsqv3xG-F2pu5jiI2OSCP/mlx90640_animation.gif?format=1500w)

## Raspberry Pi + MLX90640 Wiring

![Raspi MLX Wiring](https://images.squarespace-cdn.com/content/v1/59b037304c0dbfb092fbe894/1591731759228-C66M7BWPEH5KPK3UYZ9A/ke17ZwdGBToddI8pDm48kL0aU6AQOwPnD5bbw5AxIml7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0ldnepkVHAptGDUshypSjuZyJSo6UXQu3jq1vLDMsMGe5B2oEJkekO2SJjQQAHY12w/mlx90640_rpi_wiring_diagram_w_table.png?format=1500w)

## MLX90640 Viewing Configuration

![MLX90640 view](https://images.squarespace-cdn.com/content/v1/59b037304c0dbfb092fbe894/1591741314859-EJXEP3ZACIXKG8TIW7JM/ke17ZwdGBToddI8pDm48kAH-NZezfsfj0Z31US0jtG17gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1UZ2I8vD_HFhwxMY4gD2ZdqE6_9q3cUYt2EFEjLLYt9OPH3bqxw7fF48mhrq5Ulr0Hg/mlx90640_view_configuration.png?format=750w)
