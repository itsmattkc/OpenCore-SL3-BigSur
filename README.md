# OpenCore EFI for Microsoft Surface Laptop 3 (Intel)

This is the OpenCore configuration, kexts, drivers, etc. I used in my "[Installing macOS on a Microsoft laptop](https://www.youtube.com/watch?v=S15FVwbHEqo)" video. This configurion is **not** perfect, it has some issues that I outline at the end of that video, such as:

- Touch screen doesn't work (can be made to work with an SSDT according to [BigSurface](https://github.com/Xiashangning/BigSurface))
- Ambient light sensors don't work ([BigSurface](https://github.com/Xiashangning/BigSurface) claims to fix this, should ask them for help if you want this)
- Wake from sleep frequently doesn't work - occasionally it does, but usually it doesn't. This is probably the most annoying issue IMO, especially for a laptop, but sadly I never really figured out why it happened or how to fix it.

While this setup is not perfect and could therefore be considered "incomplete", I've uploaded it because it may be a good starting point for users with this laptop. Keep in mind, this will only work on the Intel model(s) of the SL3. macOS will almost certainly never run on the Ryzen model(s) due to their usage of AMD integrated graphics.

There may also be more issues that I never noticed in my testing for the video. I tried to test a lot of use cases, as you can see in the video, but overall my usage was somewhat limited because I only really did it for the fun/novelty value. Now that the video is finished, I don't really have a reason to use macOS on this laptop, so it's unlikely I'll be providing any future updates/maintenance.
