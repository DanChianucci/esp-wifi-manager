cmake_minimum_required(VERSION 3.24)
idf_component_register(
    SRC_DIRS src
    REQUIRES log nvs_flash mdns wpa_supplicant lwip esp_http_server esp_wifi
    INCLUDE_DIRS "include"
    EMBED_FILES assets/style.css assets/code.js assets/index.html)
