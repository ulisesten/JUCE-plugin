# JUCE multiformat audio plugin

Yeah, it includes LV2 plugin format

# Building
On terminal

    git submodule update --init --recursive
    mkdir build
    cmake -S . -B build
    make -C build

# Running

You can run the standalone version or load the plugin in your DAW. They are located in `build/AudioPlugin_artefacts/`

