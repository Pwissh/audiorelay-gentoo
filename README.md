# audiorelay-gentoo
My configuration for creating a device which you can both set as a default input device and retain the general AudioRelay functionality. I'm using the flatpak version of it.

# What i'm doing?
You are esentially creating a virtual microphone that you can use to pass the input coming from your phone microphone to your linux device. This should not just work for gentoo but every device that uses pipewire-pulse. You'll need to put the audiorelay.conf file inside the "~/.config/pipewire/pipewire-pulse.conf.d/" directory.

# The official guide for pulseaudio
https://docs.audiorelay.net/instructions/linux/use-your-phone-as-a-mic-for-a-linux-pc
