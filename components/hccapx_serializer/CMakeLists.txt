idf_component_register(
    SRCS "hccapx_serializer.c"
    INCLUDE_DIRS "interface"
    REQUIRES frame_analyzer esp_event esp_wifi esp_netif nvs_flash
)
