Source: https://github.com/libsdl-org/SDL

# Setup
`sudo apt install build-essential git make cmake ninja-build libasound2-dev libpulse-dev libaudio-dev libjack-dev libsndio-dev libx11-dev libxext-dev libxrandr-dev libxcursor-dev libxfixes-dev libxi-dev libxtst-dev libxkbcommon-dev libdrm-dev libgbm-dev libgl1-mesa-dev libgles2-mesa-dev libegl1-mesa-dev libdbus-1-dev libibus-1.0-dev libudev-dev`

# Compile
`cmake . -B build -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=$HOME/container/SDL -DCMAKE_C_FLAGS="-O3 -DNDEBUG -s" -DSDL_VULKAN=OFF -DSDL_MMX=OFF -DSDL_JACK=OFF -DSDL_DISKAUDIO=OFF -DSDL_DUMMYAUDIO=OFF -DSDL_DUMMYCAMERA=OFF -DSDL_DUMMYVIDEO=OFF`