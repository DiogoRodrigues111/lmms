INCLUDE(BuildPlugin)

BUILD_PLUGIN(amplifier Amplifier.cpp AmplifierControls.cpp AmplifierControlDialog.cpp MOCFILES AmplifierControls.h AmplifierControlDialog.h EMBEDDED_RESOURCES artwork.png logo.png)
