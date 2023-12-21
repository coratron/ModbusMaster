# Set the component name
set(COMPONENT_NAME "modbus-master")


# Create the component library
idf_component_register(SRCS "src/ModbusMaster.cpp"
                       INCLUDE_DIRS "src"
                                    "src/util"
                       REQUIRES "arduino"
                      )
