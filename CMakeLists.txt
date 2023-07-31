cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "src/PMW3901.cpp"
                    INCLUDE_DIRS "src/."
                    REQUIRES "arduino" # Library requires Arduino
                    )

project(PMW3901)