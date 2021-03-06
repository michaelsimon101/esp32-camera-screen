set(COMPONENT_SRCS
	app_camera.c
	app_httpd.c
	app_speech_recsrc.c
	app_speech_wakeup.c
	app_wifi.c
	app_main.cpp
	app_screen.cpp
	app_sd.cpp
    )

set(COMPONENT_ADD_INCLUDEDIRS include)

set(COMPONENT_REQUIRES
    esp32-camera
    esp-face
    nvs_flash
    esp_http_server
    fb_gfx
    esp-sr
    spiffs
    )

register_component()

