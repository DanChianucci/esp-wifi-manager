idf_component_register(
    SRC_DIRS src
    REQUIRES log nvs_flash mdns wpa_supplicant lwip esp_http_server esp_wifi json
    INCLUDE_DIRS "include"
    EMBED_FILES assets/style.css assets/code.js assets/index.html)
