# SPDX-License-Identifier: Apache-2.0

zephyr_include_directories(src)

target_sources(app PRIVATE src/thingset.cpp)
target_sources(app PRIVATE src/thingset_canmsg.cpp)
target_sources(app PRIVATE src/thingset_cbor.cpp)
target_sources(app PRIVATE src/cbor.c)
target_sources(app PRIVATE src/thingset_json.cpp)
target_sources(app PRIVATE src/jsmn.c)
