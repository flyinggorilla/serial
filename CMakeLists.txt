idf_component_register(SRCS Serial.cpp
                       REQUIRES esp_system driver espstring log 
                       INCLUDE_DIRS "."
                       )