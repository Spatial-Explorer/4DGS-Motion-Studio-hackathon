# 4DGS Motion Studio Hackathon Requirement

4DGS Motion Studio lets creators animate photorealistic Gaussian splat avatars with an iPhone for games and live browser or WebXR experiences—no mocap suit or stage required.

## Inspiration

We grew up dreaming of Star Trek’s holodeck. Vision Pro made immersion feel real; Gaussian splats made places feel real. But those places were static. What if a live performer could bring them to life?

## What it does

4DGS Motion Studio brings live, motion-driven splat avatars into captured 3D sets. iPhones track a performer’s face, hands and body; our browser studio combines the feeds and animates a photoreal character. Watch on a laptop, 3D glasses or Vision Pro—or record, replay and export a take.

## How we built it

Three teammates covered the pipeline: Luca Ban led creative direction and performed, Matt Fisher captured environments, and Dan Zeitman built the software.

We turned photos into optimized splat characters and sets using Meshy, Spirula Studio, Gaussian Studio and SplatTrim. A Python bridge streams iPhone motion into a three.js + Spark studio for retargeting and rendering.

## Challenges

Venue Wi-Fi blocked local connections, so we brought our own router. Vision Pro required HTTPS, so we served the studio with a local certificate. Tracking dropouts broke poses, so we added per-camera Hold controls.

## Accomplishments

Luca performed live as his life-size splat avatar inside Matt’s captured environment on Vision Pro—with no mocap suit or render farm. The same browser app also runs on laptops and 3D glasses.

## What we learned

Animating splats was only part of the work. Making the experience dependable meant solving networking, browser security and file-size challenges. Our mix of art, photography and code brought the whole pipeline together.

## What’s next

Better live streaming in 2D and immersive 3D, plus a live music experience for our upcoming SXSW speaking engagement.




